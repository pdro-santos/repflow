# AI Rules

## Regras Gerais

- Nunca utilizar `any` em TypeScript.
- Sempre utilizar TypeScript estrito.
- Sempre criar componentes reutilizáveis.
- Nunca duplicar código.
- Nunca quebrar a arquitetura do projeto.
- Sempre atualizar a documentação quando houver mudanças.
- Sempre criar migrations para alterações no banco.
- Nunca apagar dados permanentemente sem necessidade.
- Priorizar código simples e legível.
- Preferir composição ao invés de herança.

## Frontend

- Utilizar Server Components por padrão.
- Utilizar Client Components apenas quando necessário.
- Componentes devem ter responsabilidade única.
- Manter componentes pequenos.

## Banco de Dados

- Utilizar UUID em todas as tabelas.
- Utilizar `created_at` e `updated_at`.
- Utilizar `deleted_at` para Soft Delete quando fizer sentido.
- Utilizar Foreign Keys em todos os relacionamentos.

## Git

- Commits pequenos e descritivos.
- Utilizar Conventional Commits.