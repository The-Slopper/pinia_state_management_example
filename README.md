# Store de Usuários (Pinia)

Gerência de estado de usuários com Pinia em uma aplicação Vue 3.

## Metadados

| Campo | Valor |
|-------|-------|
| Linguagem | TypeScript |
| Biblioteca | Pinia |
| Versão | 1.0.0 |
| Licença | MIT |
| Responsável | Equipe de Frontend |

## Descrição

Define a store de usuários com estado, getters (total e primeiro) e actions (adicionar e
salvar token), além de um helper que lê o contador.

## Estrutura

```
frontend/pinia/
└── src/store.ts
```

## Uso

```ts
import { useUserStore } from './src/store';
```
