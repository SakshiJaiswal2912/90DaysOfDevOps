# Day 4 Task: Basic Linux Shell Scripting for DevOps Engineers.

 ## What is Kernel

 The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system.
 
 ## What is Shell

 A shell is special user program which provide an interface to user to use operating system services. Shell accept human readable commands from user and convert them into something which kernel can understand. It is a command language interpreter that execute commands read from input devices such as keyboards or from files. The shell gets started when the user logs in or start the terminal.
 
 ## What is Linux Shell Scripting?

 A shell script is a computer program designed to be run by a linux shell, a command-line interpreter. The various dialects of shell scripts are considered to be scripting languages. Typical operations performed by shell scripts include file manipulation, program execution, and printing text.

 **Tasks**

 - Explain in your own words and examples, what is Shell Scripting for DevOps.
 - What is `#!/bin/bash?` can we write `#!/bin/sh` as well?
 -     Ans: bang command to give path to interpreter.
 - Write a Shell Script which prints `I will complete #90DaysOofDevOps challenge`
 -     Ans: vi <filename>.sh
 -          insert i
 -          #!/bin/sh
 -          echo 'I will complete #90DaysOofDevOps challenge'
 -           :wq
 -           chmod +x <filename>.sh
 -           ./<filename>.sh
 -       
 - Write a Shell Script to take user input, input from arguments and print the variables.
 -    Ans:vi <filename>.sh
 -          insert i
 -          #!/bin/sh
 -          read var1
 -          echo $var1
 -          :wq
 -           chmod +x <filename>.sh
 -           ./<filename>.sh
 -       
 - Write an Example of If else in Shell Scripting by comparing 2 numbers
 -     ans: if[$a \>$b ]
            then
            echo "a is greater than b"
            else
            echo"b is greater than a"
            fi

 Was it difficult?
 
 - Post about it on LinkedIn and Let me know :)

 Article Ref
 erence: [Click here to read basic Linux Shell Scripting](https://devopscube.com/linux-shell-scripting-for-devops/)

 YouTube Vedio: [EASIEST Shell Scripting Tutorial for DevOps Engineers](https://www.youtube.com/watch?v=_-D6gkRj7xc&list=PLlfy9GnSVerQr-Se9JRE_tZJk3OUoHCkh&index=3)
