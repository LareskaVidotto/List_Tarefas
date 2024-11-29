# Aplicativo de Lista de Tarefas

# Objetivos do Projeto
O objetivo deste projeto é criar um aplicativo de lista de tarefas onde os usuários possam adicionar, remover e marcar tarefas como concluídas.

# Funcionalidades
- Adicionar novas tarefas
- Remover tarefas
- Marcar tarefas como concluídas
- Armazenar tarefas no local storage do navegador

# Cronograma de Desenvolvimento
- Estruturação do projeto e criação do layout (HTML/CSS)
- Implementação da lógica de adicionar e remover tarefas (JavaScript)
- Implementação da funcionalidade de marcar tarefas como concluídas e armazenamento no local storage
- Testes, ajustes e documentação

# Explicação do Código

- Estrutura HTML (index.html): O HTML fornece um campo de entrada para que o usuário digite novas tarefas, um botão para adicionar tarefas e uma lista não ordenada (<ul>) para exibir as tarefas adicionadas.

- Estilos CSS (styles.css): Aplica um estilo básico ao aplicativo, centralizando o conteúdo e fornecendo uma aparência limpa.

- Lógica JavaScript (script.js):
  - Adicionar Tarefa: Quando o botão "Adicionar Tarefa" é clicado, a função addTask cria um novo item de lista com a tarefa e adiciona botões para "Concluir" e "Remover".
  - Concluir Tarefa: O botão "Concluir" alterna a classe completed, que aplica um estilo riscado à tarefa, indicando que foi concluída.
  - Remover Tarefa: O botão "Remover" remove a tarefa da lista e atualiza o local storage.
  - Salvar Tarefas: A função saveTasks salva o estado atual das tarefas (texto e se estão concluídas) no local storage.
  - Carregar Tarefas: A função loadTasks recupera as tarefas do local storage quando a página é carregada e as exibe na lista.