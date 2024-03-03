---
title: "How to create a Minimal, Reproducible Example"

---
# How to create a Minimal, Reproducible Example

When asking a debugging question, people will be better able to provide help if you [provide code](https://meta.stackoverflow.com/q/285551) **in your question** that prospective answerers can easily understand and use to reproduce the problem.

This is variously referred to as creating a "minimal, reproducible example" (MRE), a "minimal, complete and verifiable example" (MCVE), a "minimal, workable example" (MWE), or a [reprex](https://reprex.tidyverse.org/articles/learn-reprex.html). The name "reprex" is inspired by Jenny Bryan’s reprex package for R."). Regardless of how it's communicated to you, it boils down to ensuring you have included code in your question that follows the following guidelines:

Your code examples should be:

* **Minimal**: Use as little code as possible that still produces the same problem
* **Complete**: Provide all parts someone else needs to reproduce your problem _in the question itself_
* **Reproducible**: Test the code you're about to provide to make sure it reproduces the problem

The rest of this help article provides guidance on these aspects of writing a minimal, reproducible example.

For more information on how to debug your program so that you can create a minimal example, [Eric Lippert](https://stackoverflow.com/users/88656/eric-lippert) has written a fantastic blog post on the subject: _[How to debug small programs](https://ericlippert.com/2014/03/05/how-to-debug-small-programs/)_.

## Minimal

The more code there is to go through, the less likely people can find your problem. Streamline your example in one of two ways:

1.  **Restart from scratch.** Create a new program, adding in only what is needed to see the problem. Use simple, descriptive names for functions and variables – don’t copy the names you’re using in your existing code.
2.  **Divide and conquer.** If you’re not sure what the source of the problem is, start removing code a bit at a time until the problem disappears – then add the last part back.

**…but still readable**

Don't sacrifice clarity for brevity when creating a minimal example. Use consistent naming and indentation, and include code comments if needed. Use your code editor’s shortcut for formatting code. Also, use **spaces instead of tabs**, as tabs usually are not correctly formatted on Stack Overflow, particularly for indenting.

## Complete

Make sure all information necessary to reproduce the problem is included _as text_ **in the question itself:**

*   [**DO NOT** use images of code](https://meta.stackoverflow.com/q/285551). Copy the actual text from your code editor, paste it into the question, then [format it as code](https://stackoverflow.com/editing-help#code).
*   Use _individual_ **[code blocks](https://stackoverflow.com/editing-help#code)** for each file or snippet you include. Provide a description for the purpose of each block.
*   If the problem requires some server-side code as well as some XML-based configuration, **include code for both**. If a web page problem requires HTML, some styles, and some JavaScript, **include code for all three**. The problem might not be in the code that you think it is in.
*   If you are using HTML, CSS, and/or JavaScript, you can use **[Stack Snippets](https://meta.stackoverflow.com/questions/358992/ive-been-told-to-create-a-runnable-example-with-stack-snippets-how-do-i-do)** to include _runnable_ snippet instead of just a static code block.

## Reproducible

To help you solve your problem, others will need to verify that it _exists:_

* __Describe the problem.__ "It doesn't work" isn't descriptive enough to help people understand your problem. Instead, tell other readers what the expected behavior should be. Tell other readers what the exact wording of the error message is, and which line of code is producing it. Use a brief but descriptive summary of your problem as the title of your question.
* __Eliminate any issues that aren't relevant to the problem.__ If your question isn’t _about_ a compiler error, ensure that there are no compile-time errors. Use a program such as [JSLint](https://www.jslint.com/) to validate interpreted languages. [Validate](https://validator.w3.org/) any HTML or XML.
* __Double-check that your example reproduces the problem!__ If you inadvertently fixed the problem while composing the example but didn't test it again, you'd want to know that before asking someone else to help.

It might help to shut the system down and restart it, or transport the example to a fresh environment to confirm it really does provide an example of the problem.

Original post [here](https://stackoverflow.com/help/minimal-reproducible-example).
