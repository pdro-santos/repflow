# Project Context

## Nome
RepFlow

## Objetivo

Plataforma para organização de repúblicas universitárias.

## Público-alvo

Repúblicas universitárias pequenas e médias.

## Principais problemas que resolve

- Organização de tarefas.
- Controle de limpeza.
- Comunicação interna.
- Gestão de compras compartilhadas.
- Controle financeiro.

## Tecnologias

- Next.js
- React
- TypeScript
- Tailwind CSS
- Supabase
- PostgreSQL

## Arquitetura

- App Router
- Mobile First
- PWA
- Feature-based structure

## Estrutura inicial

src/
├── app/
├── components/
├── features/
├── hooks/
├── lib/
├── services/
├── types/
└── utils/

## Papéis iniciais

- Decano
- Morador

## Princípios

- Simplicidade.
- Transparência.
- Facilidade de uso.
- Foco em organização.
## Decisões de Produto

- Um usuário pertence a apenas uma república.
- Uma tarefa pode ter um ou mais responsáveis.
- O sistema terá calendário semanal de limpeza.
- A lista de compras será simples, com valor total, divisão por moradores e responsável pelo recebimento.
- Penalidades já fazem parte da rotina das repúblicas e serão consideradas no MVP.
- Moradores podem sair da república e novos moradores podem entrar.
- Ex-moradores devem permanecer no histórico do sistema.
- Dívidas antigas continuam registradas até serem quitadas.