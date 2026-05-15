# POP — Adição de Membros na Conta Claude Code (Business)

## Objetivo

Este Procedimento Operacional Padrão (POP) descreve o processo para adicionar novos membros à conta empresarial (Business) do Claude Code, garantindo controle de acesso, rastreabilidade e conformidade.

---

# Pré-requisitos

- Ter acesso administrativo (owner/admin) à conta empresarial do Claude Code.
- Possuir o e-mail corporativo do novo membro.
- Estar conectado à internet.
- Ter credenciais válidas da conta administradora.

---

# Procedimento

## 1. Acessar a Plataforma

1. Abrir o navegador.
2. Acessar o portal do Claude Business (substituir pelo URL correto da sua organização):

   https://platform.claude.com/settings/members

3. Realizar login com credenciais administrativas.

> Observação: Se a organização utiliza um provedor de SSO (Okta, Azure AD, etc.), autenticar via SSO conforme o fluxo corporativo.

## 2. Acessar Configurações da Organização

1. No painel principal, localizar o menu de administração ou o ícone do perfil/organização.
2. Selecionar `Admin`, `Organization` ou `Workspace` (nome pode variar conforme a interface).

## 3. Adicionar Novo Membro

1. Abrir a seção `Members`, `Team` ou `Users`.
2. Clicar em `Invite Member` / `Add User` / `Convidar`.
3. Informar o e-mail corporativo do usuário.
4. Selecionar o papel/role apropriado:
   - `Member` — acesso padrão para colaboradores.
   - `Admin` — acesso administrativo (conceder somente quando necessário).
5. (Opcional) Atribuir permissões ou times/grupos específicos, se aplicável.
6. Enviar convite.

## 4. Atribuir Recursos e Permissões

1. Após o aceite do convite, verificar se o usuário foi adicionado ao time correto.
2. Ajustar permissões de projetos, canais ou repositórios internos conforme necessidade.

## 5. Confirmar e Documentar

1. Registrar a inclusão no inventário de acessos (planilha ou ferramenta de IAM usada pela organização).
2. Informar o gestor responsável que o acesso foi concedido.

---

# Validação

- O usuário deverá receber e aceitar o e-mail convite.
- Confirmar que o usuário aparece na lista de membros ativos.
- Verificar que as permissões atribuídas estão corretas (acesso mínimo necessário).

---

# Boas Práticas

- Utilizar apenas e-mails corporativos.
- Conceder o mínimo privilégio necessário (principle of least privilege).
- Registrar todas as mudanças de acesso em um controle centralizado.
- Remover acessos quando não forem mais necessários (offboarding).

---

# Responsabilidades

| Responsável | Atividade |
|---|---|
| Administrador da Plataforma | Conceder/Revogar acessos, gerenciar roles |
| Gestor do Time | Solicitar acessos e validar necessidade |
| Usuário Convidado | Aceitar convite e configurar MFA se necessário |
| Segurança/Compliance | Auditar acessos periodicamente |

---

# Registro de Mudanças

| Versão | Data | Descrição |
|---|---|---|
| 1.0 | 2026-05-15 | Criação do POP para Claude Code Business |

---

# Notas

- Substitua o URL do portal pelo link oficial da sua implementação do Claude Business se diferente do exemplo.
- Se sua organização usa integração SCIM/SSO automatizada, preferir o provisionamento automático via provedor de identidade.
