# How-to-create-a-Minimal-Reproducible-Example
When asking a question, people will be better able to provide help if you provide code that they can easily understand and use to reproduce the problem. This is referred to by community members as creating a minimal, reproducible example (reprex), a minimal, complete and verifiable example (mcve), or a minimal, workable example (mwe). Regardless of how it's communicated to you, it boils down to ensuring your code that reproduces the problem follows the following guidelines:

Your code examples should be…

…Minimal – Use as little code as possible that still produces the same problem
…Complete – Provide all parts someone else needs to reproduce your problem in the question itself
…Reproducible – Test the code you're about to provide to make sure it reproduces the problem
The rest of this help article provides guidance on these aspects of writing a minimal, reproducible example.

## **Minimal**
The more code there is to go through, the less likely people can find your problem. Streamline your example in one of two ways:

  1. **Restart from scratch.** Create a new program, adding in only what is needed to see the problem. Use simple, descriptive names for functions and variables – don’t copy the names you’re using in your existing code.
  
  2.**Divide and conquer.** If you’re not sure what the source of the problem is, start removing code a bit at a time until the problem disappears then add the last part back.
  
##**Minimal and readable**
Don't sacrifice clarity for brevity when creating a minimal example. Use consistent naming and indentation, and include code comments if needed. Use your code editor’s shortcut for formatting code. Also, use spaces instead of tabs – tabs might not get correctly formatted.

##**Complete**
Make sure all information necessary to reproduce the problem is included in the question itself:

If the problem requires some server-side code as well as some XML-based configuration, include code for both. If a web page problem requires HTML, some JavaScript, and a stylesheet, include code for all three. The problem might not be in the code that you think it is in.

Use individual [code blocks](https://stackoverflow.com/editing-help#code) for each file or snippet you include. Provide a description for the purpose of each block.

Use Stack Snippets to include runnable HTML, JavaScript, or CSS.

DO NOT use images of code. Copy the actual text from your code editor, paste it into the question, then format it as code. This helps others more easily read and test your code.

##**Reproducible**
To help you solve your problem, others will need to verify that it exists:

Describe the problem. "It doesn't work" isn't descriptive enough to help people understand your problem. Instead, tell other readers what the expected behavior should be. Tell other readers what the exact wording of the error message is, and which line of code is producing it. Use a brief but descriptive summary of your problem as the title of your question.

Eliminate any issues that aren't relevant to the problem. If your question isn’t about a compiler error, ensure that there are no compile-time errors. Use a program such as [JSLint](https://www.jslint.com/) to validate interpreted languages. [Validate](https://validator.w3.org/) any HTML or XML.

Double-check that your example reproduces the problem! If you inadvertently fixed the problem while composing the example but didn't test it again, you'd want to know that before asking someone else to help.

It might help to shut the system down and restart it, or transport the example to a fresh environment to confirm it really does provide an example of the problem.

For more information on how to debug your program so that you can create a minimal example, [Eric Lippert](https://stackoverflow.com/users/88656/eric-lippert) has written a fantastic blog post on the subject: [How to debug small programs](https://ericlippert.com/2014/03/05/how-to-debug-small-programs/).

The use of “reprex” for Reproducible Example was inspired by [Jenny Bryan’s reprex package for R](https://reprex.tidyverse.org/articles/articles/learn-reprex.html).

You may have been told to include an MCVE – Minimal, Complete, and Verifiable examples is what they were referring to. MCVE was also the former name of the page you're reading now, occasionally misspelled as MVCE, before it was renamed to Minimal, Reproducible Example (sometimes called “reprex”, “min-reprex”, “repro” or just “example”).
