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

    - There is an error when we use a path to a file as an argument because the command cd is used to switch the current working directory to the given path. So if the given path is not a directory (a file in this case), it will cause an error.

## Command cat:

* A screenshot or Markdown code block showing the command and its output
<img width="279" alt="image" src="https://github.com/Sam110120/cse15l-lab-reports/assets/71369089/67368d0a-8614-4a1e-8c8a-af40b2a31d28">
    
    - When there is no argument, the program will somehow crush (no longer able to input command line next). I have to open up a new terminal in order for me to keep working.

<img width="694" alt="image" src="https://github.com/Sam110120/cse15l-lab-reports/assets/71369089/94ec83d3-4f0f-49ae-8543-e2c5c3cda454">
    
    - The command cat is used to print the contents of one or more files given by the paths. I created another folder within the directory "lecture1" and use the command cat. Since both of them are directories, it will cause an error saying that given path is directory.

<img width="638" alt="image" src="https://github.com/Sam110120/cse15l-lab-reports/assets/71369089/ac447405-e2c5-4a06-ad78-0daead63f7d9">
    
    - When we use a path to a file as an argument (two files for concatenate in this case), it print the contents of both files given by the paths. There is no error.

* What the working directory was when the command was run
  
    - The working directory was at /home when the command started to run. Then it changes to /home/lecture1 as I enter the lecture1 folder for convinence.
