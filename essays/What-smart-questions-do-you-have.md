	---
layout: essay
type: essay
title: What smart questions do you have?
# All dates must be YYYY-MM-DD format!
date: 2019-09-12
labels:
  - Questions
---

<img class="ui tiny right spaced image" src="../images/question.jpeg">*Questions: we all do it, but how can we do it smart?*

There are many endeavors in life that cannot be taken on without the help of other people’s knowledge and wisdom – software development is definitely one of those endeavors. When faced with trying to solve a difficult problem, asking for help can be an invaluable experience because it will promote learning that may stick with you forever. 

Whether it is the forums, Reddit, or Slack group, it is important to ask these questions in a smart way. One should not look immediately to the forums the next time they find that a program crashed on their computer. An effective person would first do everything they can reasonably do to diagnose and troubleshoot the issue themselves. If the problem still persists, existing resources should be searched. If the problem has yet to be resolved, it is at this point that one may consider reaching out for help. Below is an excellent example of asking a question.


## What does a smart question look like?

<a href="https://stackoverflow.com/questions/1678122/must-override-a-superclass-method-errors-after-importing-a-project-into-eclips">Smart question on Stack Overflow</a>

“'Must Override a Superclass Method' Errors after importing a project into Eclipse. Anytime I have to re-import my projects into Eclipse (if I reinstalled Eclipse, or changed the location of the projects), almost all of my overridden methods are not formatted correctly, causing the error: The method must override a superclass method
This becomes quite a pain having to manually recreate ALL my overridden methods by hand. If anyone can explain why this happens or how to fix it… “

The question is precise and informative in regard to what the user is trying to accomplish. Also, the user has included example excerpts of code that can be used to help troubleshoot the errors. Lastly, the question is sent in a standard form that correctly utilizes the formatting of code in the post. Providing the relevant information in the question post has made it possible for a dozen quality responses from people. The one below is the top response.

“Eclipse is defaulting to Java 1.5 and you have classes implementing interface methods (which in Java 1.6 can be annotated with @Override, but in Java 1.5 can only be applied to methods overriding a superclass method).

Go to your project/IDE preferences and set the Java compiler level to 1.6 and also make sure you select JRE 1.6 to execute your program from Eclipse.” 



## Okay but how does a not-so-smart question look?

To contrast this style of smart question followed by a smart answer, this is an example of a <a href="https://stackoverflow.com/questions/57919978/dropdown-value-not-getting-inserted-in-database">not-so-smart question on Stack Overflow</a>

“I've a dropdown where the values are from an array, whenever I try to submit the form the value is not getting inserted into the database, I've tried to check all the possible errors but nothing helped… I've tried many time, the background field in database remains empty. Its datatype is VarChar.”

The quality of this question is poor because the user has not specified enough information about the problem that they’re having and what they have already done to troubleshoot. Also, the issue is hardly reproducible for someone to help. The lacking areas of this question are made apparent by the response provided below.

“ There are a couple of issues here.
You haven't specified what user->background_type() does. We can infer that it is getting the background type from the array you specified, but we can't see you passing any parameters so I'm unsure as to how you're getting this, therefore an error could lie there.
Secondly, in the same line as user->background_type() you have the following , rather than .
Lastly, you haven't specified the contents of $dbqueries, so an issue could lie there also. “

Notice that the volunteer above is having a difficult time providing concrete solutions to the problem. Background information is not made readily available by the person asking the question, and as a result users are not able to make significant progress in helping the person out.


## How has this experience affected me?

Being in a technical field, I understand that I will have a lot of problems to solve, troubleshooting to do, and questions to be asking. Knowing the characteristics of smart questions will be of tremendous help in developing my personal and professional skill set. On the other hand, recognizing a not-so-smart question will be just as valuable, as I will be able to be self-aware.
