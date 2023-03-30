# Aplicação Web de Lista de Tarefas

- Este é o código JavaScript para uma aplicação web de lista de tarefas. Ele permite adicionar novas tarefas, marcá-las como concluídas, editá-las e excluí-las, além de realizar buscas e filtros.

- O código começa definindo vários elementos do DOM, como o campo de entrada e os botões para adicionar, editar e excluir tarefas, e o contêiner div para exibir a lista de tarefas. Ele também define funções que lidam com a adição, atualização e exclusão de tarefas, e com a gravação e carregamento de dados do armazenamento local.

- A função saveTodo é responsável por criar um novo elemento de item de tarefa e anexá-lo ao contêiner de lista de tarefas. Ela recebe um parâmetro de texto para a descrição da tarefa e parâmetros opcionais de done e save para especificar se a tarefa está concluída e se deve ser salva no armazenamento local.

- A função toggleForms oculta/mostra os formulários de edição e adição ao alternar entre eles.

- A função updateTodo lida com a atualização da descrição de uma tarefa quando ela está sendo editada. Ela recebe o novo parâmetro de texto como entrada e procura o item de tarefa que tem a descrição da tarefa antiga (oldInputValue) e a atualiza no DOM e no armazenamento local.

- A função getSearchedTodos lida com a busca de tarefas na lista de tarefas. Ela recebe o parâmetro de busca como entrada e itera por todos os itens de tarefa, verificando se a descrição da tarefa inclui o termo de busca. Se sim, exibe o item de tarefa, caso contrário, o oculta.

- A função filterTodos lida com a filtragem da lista de tarefas pela opção de filtro selecionada. Ela recebe o parâmetro de valor do filtro como entrada e itera por todos os itens de tarefa, definindo sua propriedade de estilo de exibição como flex ou nenhum, dependendo da opção de filtro.

- O código também define ouvintes de eventos para adicionar, editar e excluir tarefas, além de buscar e filtrar. Ele também carrega quaisquer tarefas salvas do armazenamento local quando a página da web é carregada.

## Input

- O arquivo principal de execussão é o `index.html`.

## Output

- O output é a Aplicação Web de Lista de Tarefas