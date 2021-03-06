---
layout: essay
type: essay
title: Cleaning out the ESLint
# All dates must be YYYY-MM-DD format!
date: 2018-02-07
labels:
  - Code
  - Standards
  - ESLint
---

Code linters are a popular choice for many people. These tools allow people to constantly "lint" code as it is written, checking for possible errors and making sure that it adheres to the style standard. A linter can seem like an absolute must-have, especially when working in groups, because it can make sure that everyone's code remains fairly consistent. However, despite their obvious utility, can they become a consistent pain in the neck?

<img class="ui small left floated image" src="../images/eslint.svg">
ESLint, along with JSHint and JSLint, are all popular linting tools for JavaScript. Many of these can be run in IDEs (integrated development environment), checking and re-checking code after every little change that is made, allowing users to constantly keep their code in check. They can make sure that all of your braces are put in the right place, make sure that everything is indented ever so nicely, and ensure the placement of a spaces between operators and keywords.

At first glance, this seems like a neccesity. After all, it makes sure that at any point in time, your code remains consistent with the chosen coding style standard. This should be absolutely stellar, especially since one of the most important skills with coding is to keep all of the code readable and consistent. However, many IDEs convey any errors or warnings generated by these linters by using red and yellow markers, either in the sidebar or as underlines in the code itself. This can be very distracting, as the code is not in a final state at all while you're modifying a code base or adding new code. When the errors and warnings present themselves constantly, we are slowly trained to treat them as signals that we subconciously block out and ignore. In today's digital world, where our personal devices are always begging and nagging for our attentiong, just like those certain notifications that you block out every day, so will you begin to ignore the warnings and errors. Besides, you probably wouldn't want somebody peering over your shoulder, pointing out *every single* misplaced character and mistake you make, *as you make each one*.

Instead, I prefer to only lint my code files after I finish a major chunk of code, or after finishing a file. This allows you to work without distractions, getting down all the logic that you need to, without having to worry over every space you add (or miss). At the end, you can lint the file(s) that you've worked on, and fix any errors and warnings that appear. And eventually, if you practice those standards enough, they will become second nature, and you won't need to fix as many style errors at the end.

In short, code linters are great! They help keep code clean, easy on the eyes, and consistent with the rest of the code base. However, it all boils down to personal preference when it comes to constantly linting while actively writing code, or only linting after finishing a significant chunk of code.
