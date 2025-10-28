# Faciltador-de-tarefas.
Faciltador de tarefas com calculadora, lista de compras e lista de afazeres.

Explicando as funções e suas utilidades:

1. Calculadora

  A função calcular() lê dois números e a operação escolhida (somar, subtrair, multiplicar ou dividir) e exibe o resultado no elemento msg. Trata divisão por   zero mostrando erro. É acionada geralmente por um botão “Calcular”.

2. Lista de Compras

  adicionarItem(): adiciona o item digitado no input à lista (<ul>) e limpa o input.

  limparLista(): remove todos os itens da lista.
  Usadas em botões “Adicionar” e “Limpar” para gerenciar a lista de compras.

3. Lista de Tarefas

  Permite adicionar tarefas, marcar como concluídas clicando sobre elas e limpar toda a lista.

  atualizarLista(): atualiza a lista no HTML a partir do array tarefas.

  Botão “Adicionar”: adiciona nova tarefa e atualiza a lista.

  Botão “Limpar”: limpa todas as tarefas e atualiza a lista.
