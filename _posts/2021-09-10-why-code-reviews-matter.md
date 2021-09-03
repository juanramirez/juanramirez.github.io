---
title: "Why code reviews matter: 5 reasons"
date: 2017-08-25 20:30:00 +0200
tags:
  - code review
#twitter-card-image: "/assets/images/posts/2017-08-23-7-tips-to-have-your-code-better-reviewed.png"
#excerpt: "Code reviews are a fantastic way to keep all the team on the same page and encourage everybody to Excluding files for being versioned in Git is easy through the use of the widely known .gitignore file. But maybe you don't really want to use it."
published: false
---
Code reviews take time. Of course. But they are helpful. Very helpful. They

1. It makes everybody in the team to be in the same page. Gives everybody context Provides context

1. **Create reviews for all the code you push**. No, seriously: _do it_. Some companies or teams have this process semi-automated or very established as part of its tech culture. If they don't, ask your manager to do so (and if he responds that it's a bad idea, run out of that company!! _NOW!!_). Remember: _optional_ code reviews means _no code reviews_.

2. **Create those reviews _early and often_**. Don't wait to have a monster with a million of lines of code. Several small, specific changesets, are way easier to review than one big changeset with lots of changes. Also, your changes will more likely be accepted if you divide them into several smaller steps.

3. **Review your own code** before giving it to your teammates. Imagine you receive that code to be reviewed for the first time. Be your best reviewer, be critical with your code. Take your time.

4. In order to avoid noise, use your IDE to identify possible bugs. Most IDEs analyze your code in order to find possible warnings or bugs. If your IDE does not analyze it automatically, **pass the code through a static code analyzer** and, if your team uses a code formatting standard, use an automatic tool to format it. This will allow your teammates to concentrate on the really important things and will avoid silly comments about style.

5. **_Prepare_ your review**. I mean, not only add the code or the changesets you want to review. Link the review to the corresponding ticket and/or explain the feature you're trying to add, focusing on implementation details that maybe are _not_ in the ticket, but are relevant. If there is some piece of code which is not obvious, you should explain _why_ you did it that way and not differently.

6. Carefully **select the people you want to review your code**. If there is a policy for that, follow it. Most of the cases, however, not everybody in your team needs to review your code. People who probably needs to be there includes your manager, some person with experience in the product domain, the original author of the piece of code you're touching (or just someone who touched the code before), someone who is paralelly developing another related feature, etc.

7. **Don't take it personally**. It's _your code_ that is being reviewed, not _you_. Long comment threads in a review doesn't mean someone hates you or wants to annoy you. More probably, it will mean she disagrees with you in something specific. Be nice, assume the best intentions on the reviewer and answer all the comments pleasantly. Be ready to learn from others. Be grateful on the good suggestions and express your arguments clearly, but with politeness, if there's something you honestly don't agree with.
