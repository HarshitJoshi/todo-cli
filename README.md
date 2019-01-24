## todo-cli
A todo script written in Ruby.

### Prerequisites
ruby v2.3.0+

*nix based OS

### Features
* displaying your todo list
* adding goals to the list
* removing goals from the list
* checking off the goals on the list
* unchecking the goals on the list
* swapping the location of 2 goals
* editing the goals on the list
* sorting the goals from unfinished to finished
* purging(wiping) the list of goals
* logging of todo list (meant to be used in conjunction with cron jobs for purge)
* a help option to list the types of commands and argument(s)

### Ease of use
In the spirit of a quick access script, instructions for easy todo calls are listed below:

1. rename the *todo.rb* file to just *"todo"*
2. run: `chmod +x todo`
3. add directory of script to $PATH environment so that it can be accessed anywhere
4. (optional) create or add a symbolic link to the *todo.rb* to a scripts directory and add the scripts directory to $PATH

So now you can just type `todo` in your terminal and either your list or the help page will be displayed!
