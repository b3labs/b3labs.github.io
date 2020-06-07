- [About this website](#about-this-website)
- [Learning to Program / Becomming a Developer](#learning-to-program--becomming-a-developer)
  - [First steps - recommended for people who are new to programming](#first-steps---recommended-for-people-who-are-new-to-programming)
  - [Tutorials - A guided exercise](#tutorials---a-guided-exercise)
  - [Questions - You can submit them back to test your understanding](#questions---you-can-submit-them-back-to-test-your-understanding)
  - [Tasks - Getting your hands dirty](#tasks---getting-your-hands-dirty)
  - [Other Things](#other-things)

## About this website

- Goal 
   > This website (repo) was designed to provide anyone with the basic building blocks to start learing programming. 

- The name 
    > I am a big fan of [Lego](https://www.lego.com) blocks, and I am facinated with their `system`. Visualizing computer programs and systems as these simple building `blocks` which you can combine to create useful applications / systems, is what I aspire to teach you.
    > The name is also a fun reference to [w3schools](https://www.w3schools.com), a popular tutorial website. This website, is designed to be a precursor to **w3schools**.

- Issues
    > If you have any recommendations or problems, please create an issue [here](https://github.com/b3labs/b3labs.github.io/issues)

- Learning Methods
    > Various learning styles/methods are used to teach: reading, watching videos, doing turorials, answering questions and doing small projects

## Learning to Program / Becomming a Developer

If you don't have any programming background, it is RECOMMENDED to go through and understand the **First steps** below...

### First steps - recommended for people who are new to programming

Some things to read before we get to the exercises

1. [How a computer works](./reading/1-How-a-computer-works.md)
1. [Basic programming building blocks](./reading/2-Basic-programming-building-blocks.md)

### Tutorials - A guided exercise

To complete these tutorials, just follow the steps in the tutorial.

1. bash: [Getting started with Bash](./tutorial/bash-tutorial.md)
2. git: [Getting started with Git](./tutorial/git-tutorial.md)

### Questions - You can submit them back to test your understanding

> IMPORTANT NOTE: DO NOT WORK ON MASTER, I.E. NEVER COMMIT ONTO MASTER, RATHER CREATE YOUR OWN BRANCH AND WORK ON IT
> To answer these questions, create a branch off from master with the same name as the excercise marked in **bold**. [This will show you how](./cheatsheets/git.md#Create-a-branch)

[After you create a new branch](./cheatsheets/git.md#Create-a-branch), you can edit the quesion's `.md` file with your answers, and commit and push it when you are done.

1. GIT (questions): create a branch called **understand-git-commands**
   - Have a look at the [git-cheatsheet](./cheatsheets/git.md)
   - _Complete the questions_ by modifying and commiting the changes in [git-questions](./questions/understand-git-commands-questions.md)
1. SBT (questions): create a branch called **understand-sbt-project-excercise**
   - Have a look at the [sbt-cheatsheet](./cheatsheets/sbt.md)
   - _Complete the questions_ by modifying and commiting the changes in [sbt-questions](./questions/understand-sbt-project-excercise.md)

### Tasks - Getting your hands dirty

> IMPORTANT NOTE: DO NOT WORK ON MASTER, I.E. NEVER COMMIT ONTO MASTER, RATHER CREATE YOUR OWN BRANCH AND WORK ON IT
> To answer these questions, create a branch off from master with the same name as the excercise marked in **bold**. [This will show you how](./cheatsheets/git.md#Create-a-branch)

[After you create a new branch](./cheatsheets/git.md#Create-a-branch), you can complete the task by commiting your changes to the source files.

1. Scalatest (task): **add-scala-tests-for-functions-excercise**
   - Create more tests for the cubed function
   - Add tests for the multiply and add functions
   - _Complete this exercise_ by modifying and commiting the file [ToTestOrNotToTestSpec.scala](../src/test/scala/ToTestOrNotToTestSpec.scala)

### Other Things

1. [Useful](./USEFUL.md)
2. [Extra](./EXTRA.md)
