# 42 Porto - minishell

#### Project done in collaboration with <a href="https://github.com/richardmarcela">Marcela Richard </a>

![Screenshot from 2023-08-15 12-49-43](https://github.com/reomelo/42Porto-minishell/assets/73884501/bb1d43c3-da7f-4844-a7c1-702e394f2743)

### Installing and running the project:
1- Installing minishell dependencies:  

	sudo apt-get install make libreadline-dev
2- Clone this repository:  

	git clone https://github.com/reomelo/42Porto-minishell.git
3- Enter the repository and run the program:

	cd 42Porto-minishell
	make run

###  Useful links:
1 - https://indradhanush.github.io/blog/writing-a-unix-shell-part-1/

2 - https://indradhanush.github.io/blog/writing-a-unix-shell-part-2/

3 - https://indradhanush.github.io/blog/writing-a-unix-shell-part-3/
#### Makefile Available Targets:  
`make` or `make all` - compiles minishell      
`make clean` - wipes all object files   
`make fclean` - deletes minishell and all object files   
`make re` - fclean  + all   
`make run` - re + ./minishell

