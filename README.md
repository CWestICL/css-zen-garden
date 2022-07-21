# CSS Zen Garden

[CSS Zen Garden](http://www.csszengarden.com/) is a famous project where participants show what they can achieve through css alone.

Without editing the html, developers use css to show how the same content can be styled and structured in very different ways.

Have a go at creating a css file to see what you can come up with!

## Getting started

Open a terminal and `npm install`, then `npm run dev` to start a live server. Create your css file and have fun hacking!

## Working as a team

In order to work on this project as a team, here is what you should do:

 1. In your team, nominate a Project Owner (PO).
 1. The PO **Forks** the repo. Then, withing their fork, they add the other members of the team as collaborators by clicking on the **Settings** tab in github.com and providing their GitHub username or email address.
 1. Each member of the team can now **clone** the **fork** from VS Code.

Now you have some options:

**Option 1: Round robin**: Everyone works on the Master. The PO makes a change and pushes it. Everyone else pulls. Then the next person makes a change and pushes it. Everyone else pulls. And so on.

**Option 2: Branches**: You work on separate features. In this scenario, you should ideally all be working in separate files. You make a branch for the feature you want to make (e.g. style-headers), make a file called `headers.css` and work on your code in your branch. You can publish the branch, and then make a pull request to bring it into the main branch.

If two developers edit the same line of code, you will get a **merge conflict** which means git doesn't know which change you want to keep. One good tip is to "fetch and rebase" from the master before trying to push your changes. It will help prevent some merge conflicts (but not all). Making frequent small commits is also good practice, and running fetch and rebase often.

On a big project, it should be unlikely that two developers change the same line of code because they'll be working on different things or pair coding. Good communication is the key here: if there is anarchy and everyone is changing the same file, of course there will be many conflicts to resolve.

https://stackoverflow.com/questions/16490873/how-to-avoid-git-conflicts-in-a-team

https://dev.to/github/how-to-prevent-merge-conflicts-or-at-least-have-less-of-them-109p

