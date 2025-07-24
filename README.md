# ai_testes

Repositório de testes de IAs para geração de código.

-   A ideia é criar uma SPA de TODO List, e adicionar mais algumas funcionalidades.
-   Analisar o APP gerado inicialmente
-   Ver se ao adicionar funcionalidades, a IA mantém o contexto (mesmo layout/app ou cria outro)
-   Comparar as modificações, via commit das versões geradas.

Será copiado esse README para cada pasta com nome da IA sendo testada e os prompts adaptados acrescentando tentativas de correções, caso ocorram erros.

Será dado o mesmo prompt inicial

#### A - Prompt inicial:

```sh
Crie uma SPA de TODO List, usando html5, CSS (usando css nesting) e javascript puro.
Deve ser possível marcar as tarefas concluídas.
Deve ser possível editar tarefas e excluir.
```

#### B - Primeira modificação - dividir em 2 listas:

```sh
Gostaria também que as tarefas concluídas fossem movidas para para uma segunda lista embaixo da primeira.
E que ao desmarcar voltassem para primeira.
Resumindo: separar em duas listas uma de tarefas à fazer e outra de concluídas.
```

#### C - Segunda modificação - arrastar e soltar entre as duas listas:

```sh
Gostaria de poder mover, arrastando e soltando as tarefas entre as listas de pendentes e concluídas.
```

#### D - Terceira modificação(opcional, caso não seja assim ainda):

```sh
Gostaria de poder editar as tarefas na mesma linha, trocando para um input e tendo botões de salvar ou descartar as alterações nesse estado.
```
