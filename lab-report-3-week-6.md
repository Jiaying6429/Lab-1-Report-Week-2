# Lab Report 3
## Choice 1
>![Image](lab3(1).png)\
>![Image](lab3(2).png)\
>![Image](lab3(3).png)\
>![Image](lab3(4).png)\
>![Image](lab3(5).png)\
>For this choice, ssh/config saved user from remembering all the command, names and etc that are required to connect to remote system from SSH. \
I did the following in order:\
`~/.ssh/config`\
Then copied this\
`Host ieng6`\
`HostName ieng6.ucsd.edu`\
`User cs15lsp22als`
Then\
`ssh ieng6`\
`scp`

## Choice 2
>![Image](lab3(6).png)\
>![image](lab3(7).png)\
>![Image](lab3(8).png)\
>![image](lab3(9).png)
> ### Update
>![image](lab3(15).png)\
>![image](lab3(16).png)\
>After `git push origin main`, I have:\
`remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.`\
`remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.`\
`fatal: Authentication failed for 'https://github.com/Jiaying6429/markdown-parser.git/'`\
The private key is stored in .ssh directory. The private key is stored in the file id_rsa.


## Choice 3
>![Image](lab3(10).png)\
>![Image](lab3(11).png)\
>![Image](lab3(12).png)\
>![Image](lab3(13).png)\
>![Image](lab3(14).png)\
For this choice, I first used `pwd` and `ls` to check directory. Then I used\
`scp -r . cs15lsp22@ieng6.ucsd.edu:~/markdown-parse`\
to copy directory to remote server. Then I logged into the remote server to see all copied files\
`scp -r . ieng6:markdown-parse `\
`ssh cs15lsp22@ieng6.ucsd.edu`.\
After that, I combined with scp,ssh to copy and run test of the directory. 



