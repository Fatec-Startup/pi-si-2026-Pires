# Modelagem da Lógica – Adoção Lins

## 1. Regra de negócio: validação do formulário de contato

```mermaid
flowchart TD
    A([Início]) --> B[Usuário clica em Enviar]
    B --> C[Captura nome, e-mail e mensagem]
    C --> D{Nome vazio?}
    D -- Sim --> E[Exibe erro no campo nome]
    D -- Não --> F{E-mail válido?}
    F -- Não --> G[Exibe erro no campo e-mail]
    F -- Sim --> H{Mensagem vazia?}
    H -- Sim --> I[Exibe erro no campo mensagem]
    H -- Não --> J[Exibe mensagem de sucesso]
    J --> K[Limpa o formulário]
    E --> L([Fim])
    G --> L
    I --> L
    K --> L
```

## 2. Filtro da listagem de animais

```mermaid
flowchart TD
    A([Início]) --> B[Usuário altera busca, tipo, idade ou porte]
    B --> C[Lê os valores dos filtros]
    C --> D[Percorre o array de animais]
    D --> E{Animal atende a todos os filtros?}
    E -- Sim --> F[Adiciona ao resultado]
    E -- Não --> G[Ignora]
    F --> H{Há mais animais?}
    G --> H
    H -- Sim --> D
    H -- Não --> I{Resultado vazio?}
    I -- Sim --> J[Mostra 'Nenhum animal encontrado']
    I -- Não --> K[Renderiza os cards na tela]
    J --> L([Fim])
    K --> L
```

## 3. Tipos de dados, variáveis e estruturas

| Elemento | Tipo | Exemplo |
|---|---|---|
| Lista de animais | Array de objetos | `const animais = [...]` |
| Animal | Objeto | `{ nome: "Mel", tipo: "Cachorro", idade: 3, porte: "Médio", foto: "mel.webp" }` |
| Nome, e-mail, mensagem | String | `"contato@email.com"` |
| Idade | Number | `3` |
| Filtros ativos | Objeto | `{ busca: "", tipo: "todos", idade: "todas", porte: "todos" }` |
| Formulário válido | Boolean | `true` / `false` |

**Estruturas condicionais:** `if/else` na validação de cada campo e na decisão de exibir "nenhum resultado".

**Estruturas de repetição:** `for...of` / `forEach` / `filter` para percorrer o array de animais e gerar os cards.

**Funções previstas:** `validarFormulario()`, `emailValido(email)`, `filtrarAnimais(animais, filtros)`, `renderizarCards(lista)`, `mostrarErro(campo, mensagem)`.
