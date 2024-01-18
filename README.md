<h1>Introduction</h1>
This repository contains the source code and documentation for creating a custom Linux shell in the C programming language. The shell is a command-line interpreter that facilitates interaction with the Linux operating system.

<h1>Features</h1>
<li>Basic command execution</li>
<li>Input and output redirection</li>
<li>Pipe implementation</li>
<li>Custom prompt design</li>

<h1>Getting Started</h1>
<h3>Prerequisites</h3>
<li>Linux operating system</li>
<li>GCC compiler installed</li>
<li>ReadLine Library</li>

<h3>Building the Shell</h3>
1- Clone the repository: git clone https://github.com/dodobird160103/Linux-Shell.git </br>
2- Navigate to the project directory: cd Linux-Shell </br>
3- Install Readline Library: sudo apt-get install libreadline-dev </br>
4- Compile the shell: gcc main.c -o main -lreadline 

<h3>Running the Shell</h3>
1- Execute the compiled binary: ./main </br>
2- Start entering commands and exploring the shell functionalities. 

<h1>Usage</h1>
<li>Basic Commands: Enter standard Linux commands like ls, cd, pwd, etc.</li>
<li>Redirection: Use '>' for output redirection and '<' for input redirection.</li>
<li>Piping: Connect commands using the pipe operator | for data flow.</li>
  
<h1>Acknowledgments</h1>
<li>Inspired by the simplicity and power of Linux shells.</li>

Happy coding! 🚀
