# Lab Report 4
> * [Link of my repository](https://github.com/Jiaying6429/markdown-parser)
> * [Link of reviewed repository](https://github.com/hpdinh/markdown-parser.git)
> 
> I used VSCode Preview:\
> ![Image](lab4(1).png)\
> This is how tests are added: \
> ![Image](lab4(2).png)\
> This is output for my test:\
> ![Image](lab4(3).png)\
> This is output for reviewed test: \
> ![Image](lab4(4).png)

## Questions
> * Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.
> 
> _My code passed for this snippets_
>
> * Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.
>
> _Yes, so the code should check for the first "(", then check for the last ")" instead of checking the first ")"_
>
> * Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.
>
> _Yes, when we have problem like snippets 3, we can replace all the `\n` with empty string. That will give us a new snippets that has no lines in between brackets. Also, check after "(" if there is any "[" or "]" before finding ")". If there is, then this can't be a link. This will probably take very close to 10 lines depend on the way written_

