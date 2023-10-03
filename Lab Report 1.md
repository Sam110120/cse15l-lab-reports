## Command ls:

* A screenshot or Markdown code block showing the command and its output
<img width="430" alt="image" src="https://github.com/Sam110120/cse15l-lab-reports/assets/71369089/e7c112ff-4d02-4136-99ec-0997bb1d208a">

* What the working directory was when the command was run
  
    - The working directory was at /home when the command was run.
  
* A sentence or two explaining why you got that output (e.g. what was in the filesystem, what it meant to have no arguments).
  
    - When there is no argument, it will list all files/folders within the current directory.
    - When we use a path to a directory as an argument, it will list all the files/folders within the argument directory (given path).
    - When we use a path to a file as an argument, it will show the relative path to the argument file.
  
* Indicate whether the output is an error or not, and if it’s an error, explain why it’s an error.

    - There is no error output.



## Command cd:

* A screenshot or Markdown code block showing the command and its output
<img width="445" alt="image" src="https://github.com/Sam110120/cse15l-lab-reports/assets/71369089/b8fc4014-3ee9-4b0f-8466-9bad841cc75e">

* What the working directory was when the command was run
  
    - The working directory was at /home when the command started to run. Then it changes to /home/lecture1 as we enter the lecture1 folder.
  
* A sentence or two explaining why you got that output (e.g. what was in the filesystem, what it meant to have no arguments).
  
    - When there is no argument, it will jump to the root directory （/home in this case） from the current directory.
    - When we use a path to a directory as an argument, it will switch the current working directory to the given path.
    - When we use a path to a file as an argument, it will show an error.
  
* Indicate whether the output is an error or not, and if it’s an error, explain why it’s an error.

    - There is an error when we use a path to a file as an argument because the command cd is used to switch the current working directory to the given path. So if the given path is not a directory (it's a file in this case), it will cause an error.

## Command cat:

* A screenshot or Markdown code block showing the command and its output
<img width="207" alt="image" src="https://github.com/Sam110120/cse15l-lab-reports/assets/71369089/d7a178d6-32f5-4fa1-a80b-8ec3225e7dc0">
    - When there is no argument, .

* What the working directory was when the command was run
  
    - The working directory was at /home when the command started to run. Then it changes to /home/lecture1 as we enter the lecture1 folder.
  
* A sentence or two explaining why you got that output (e.g. what was in the filesystem, what it meant to have no arguments).
  
    - When there is no argument, it will jump to the root directory （/home in this case） from the current directory.
    - When we use a path to a directory as an argument, it will switch the current working directory to the given path.
    - When we use a path to a file as an argument, it will show an error.
  
* Indicate whether the output is an error or not, and if it’s an error, explain why it’s an error.

    - There is an error when we use a path to a file as an argument because the command cd is used to switch the current working directory to the given path. So if the given path is not a directory, it will cause an error.
