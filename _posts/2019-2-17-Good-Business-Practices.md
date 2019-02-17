---
layout: post
title: Good Business Practices
---

Over the summer, I was working on a codebase alongside 40 other engineers. There were many subgroups working on different parts of the product, all having their hands interwoven in parts of the code. While writing code, however, you want to maintain a strong understanding of the entire codebase and how your code will be be integrated. Let's say that one team has been working on a large project for a month. If they haven't been merging their code to master incrementally, when they've completed their work, they're going to merge a large change into master. This may change functionality of the product, how certain functions are called, etc. As a result, many of the other engineers should know how the codebase is changing to be more informed while working on their projects.

Code tours. Our company recommended when large PRs were being merged that the lead engineers would host a code tour. An entire room and web conference would be booked and the engineer would get about 30-45 minutes to explain their additions. This also acts as a code review by the entire team addressing any concerns and questions. The most important aspect of the code tours to me is the team cohesion gained (Alpert). Rather than subgroups working individually, doing code tours make subgroups feel as though they're a part of the larger organization. Giving their say, putting a hand in, and learning more about what others are working on. 

One limitation of code tours is the time required. The issue of having too many meetings and less individual time is growing in the tech industry. The idea of being in meetings where you're not needed, therefore wasting your time, and stopping and starting your mental track while making progress on actual work (Huffington Post). With that said, code tours should not be used too extensively but rather up to the engineers when they see its value and invite only those who are necessary.

Alpert, S. (n.d.). Why review code? Retrieved from https://sophiebits.com/2018/12/25/why-review-code.html

Why Having Too Many Meetings Destroys Productivity. (2017, December 21). Retrieved from https://www.huffingtonpost.com/entry/why-having-too-many-meetings-destroys-productivity_us_5a3b1fc2e4b06cd2bd03d7f2
