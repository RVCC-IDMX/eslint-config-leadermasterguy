# ESLint Configuration
## Let's Learn an ESLint Rule
The "semi":"error" rule within ESLint will provide the user with an error message when they do not include a semicolon
at the end of their statements. VSCode will normally automatically insert semicolons where they are "necessary", but this can lead to unexpected behaviors within code. From reading over examples, it seems that VSCode is known to occasionally automatically place semicolons in inopportune places that may lead to unreachable code, run-time errors and other
unintended behaviors. While the automatic placement of semicolons *is* predictable, and can be worked around, its behaviors are complex enough that it is easy to overlook potential issues, so always using semicolons is safest, which is what this rule encourages you to do.
[ESLint Rule Documentation](https://eslint.org/docs/latest/rules/semi)