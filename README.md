# Requirements:
* osx
* git

# How to use:
* Place git_automator in the same directory as the directory being commited
* Delete or move README.md into git_automator directory
    * create directory called 'initial_config'
    * ### `git clone https://github.com/apinanyogaratnam/automate_git.git`
    * run initial_configuration.c file (show steps how to run file)

# Follow the commands below (uninitialized git environment):
### 1. `gcc git_automator/configure.c` or `clang git_automator/configure.c`
### 2. `./git_automator/a.out`
###                          OR
### 1. `cd git_automator`
### 2. `gcc configure.c` or `clang configure.c`
### 3. `./a.out`
add steps to run configure_git exe file INCOMPLETE


# Follow the commands below (git initialized and push made): 
### 1. `gcc git_automator/main.c` or `clang git_automator/main.c`
### 2. `./git_automator/a.out`
###                          OR
### 1. `cd git_automator`
### 2. `gcc main.c` or `clang main.c`
### 3. `./a.out`
###                          OR
### 1. `cd git_automator`
### 2. `./automator`

you may choose to keep or delete the executable file after execution

issues: 
    NONE

alpha release: RELEASED
    - adding a configuration initially (create executable file for initial instructions) COMPLETE

full release:
    - adding a make file to run commands (unnecessary since exe file created but create for developers) REMOVED
    - multiplatform support (as of now works on multiplatform except readme is not updated with windows instructions) COMPLETE
    - remove requirement for comiler as ./a.out will be the executable file COMPLETE
    - move README.md file inside git_automator for configure.c (if already git initialized repo, manually move README.md) COMPLETE 
    - (might be problematic since user may already have a readme file)
    - make readme better looking

v1.1: 
    - add functionality for different branches (create new file)
    - reduce number of steps for setting up tool