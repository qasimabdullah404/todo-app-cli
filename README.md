## Todo App

### Install all dependencies

- clone the repository
- activate your virtualenv
- run: <code>pip install -r requirements.txt</code> in your shell

### Usage

- To show all todos <code>python todo.py show</code>
- To create a todo - task and category <code>python todo.py add "Test Todo 2" "Study"</code>
- To update the todo (task & category) - <code>python todo.py update 1 --task "Test" --category "Study"</code>
- To update the todo (task only) - <code>python todo.py update 1 --task "Test"</code>
- To update the todo (category only) - <code>python todo.py update 1 --category "Study" </code>
- To mark todo as completed - <code>python todo.py complete 1</code>
- To delete a todo - <code>python todo.py delete 1 </code>
