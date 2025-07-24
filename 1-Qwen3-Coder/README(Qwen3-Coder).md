# ai_testes

Teste do Qwen: Qwen3 Coder (free) via:  
https://openrouter.ai/chat

#### A - Prompt inicial:

```sh
Crie uma SPA de TODO List, usando html5, CSS (usando css nesting) e javascript puro.
Deve ser possível marcar as tarefas concluídas.
Deve ser possível editar tarefas e excluir.
```

Resultado: Achei o layout bonito e tudo está funcionando conforme esperado.

#### B - Primeira modificação - dividir em 2 listas:

```sh
Gostaria também que as tarefas concluídas fossem movidas para para uma segunda lista embaixo da primeira.
E que ao desmarcar voltassem para primeira.
Resumindo: separar em duas listas uma de tarefas à fazer e outra de concluídas.
```

Resultado: Muito bom, pois manteve o mesmo contexto de layout e código inicial, fazendo apenas as modificações necessárias para a implementação nova.

#### C - Segunda modificação - arrastar e soltar entre as duas listas:

```sh
Gostaria de poder mover, arrastando e soltando as tarefas entre as listas de pendentes e concluídas.
```

Resultado: Bom, manteve o mesmo contexto de layout e código anterior, fazendo apenas as modificações necessárias para a implementação nova.  
Tem um pequeno erro na borda do drag and drop, faz as listas tremerem um pouco. Mas funciona normal.
