# Lab report 4 week 8

[My markdown-parse](https://github.com/derekcheung11/markdown-parser)

[Reviewed one](https://github.com/mdsflyboy/markdown-parser)

## Q/A

Q: Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.

> A: I believe it can be less than 10 lines if taking backticks to an account. It should be done by adding two variables for counting the indexes of the backticks, also by adding an if statement.

Q: Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.

> A: Adding 4 variables for nest parentheses and escaped brackets. Look for nearby brackets by adding an if statement. So I believe this would need more than 10 lines code changes.

Q: Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.

> A: For snippet 3, I think it would require more than 10 lines of code changes. Since the brackets are not in the same line, thus it needed to be kept tracked. Extra spacing needed to be excluded.
