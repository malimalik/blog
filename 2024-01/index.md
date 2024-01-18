# The importance of written communication in tech 

![cover](cover_6.png)

One of the things that is not talked about enough is the importance of written communication as a software engineer. If you can code but are unable to communicate your ideas effectively to the outside world, it can hold your professional career back significantly. I definitely learned the importance of written communication the hard way but in hindsight I am glad it happened because it made be a significantly better engineer.

It can be easy to think that our documentation is good because we are explaining our own code and writing from our own perspective. But, documentation should be written in a way that makes it easy for the reader to grasp your ideas. It's not easy to put together elegant documentation, which is organized and flows well. This is especially true for getting across extremely technical concepts. 

That's why in this post, I am going to be covering why written communication is important, my own experiences, and what makes a good design document. 

P.S. This post is actually inspired by one of the many experiences I had while I was working at Google.

## The Impact of Honest feedback

The way I came to realize the importance of written communication was when I was working at Google and my tech lead went out of his way to "roast" me on my poorly written documentation. I use air quotes when saying "roast" because even though the feedback stung at the time, I am grateful for it because it taught me a lot.

It all started when I sent over my design document to be reviewed by one of the smartest engineers I ever worked with. This design document was really long, about 15 pages with diagrams and everything. From a technical standpoint, the document was accurate but it was super messy and unorganized. Around half an hour later, I got pinged by that same engineer who offered to give me qualitative feedback on my work.

Though I knew he was going to go hard on me, I only found out the shortcomings of my design doc during the meeting. Comparing my design docs to his, the difference was night and day. His design documents were extremely elegant and detailed while being concise even though they were about complicated stuff. 

This was excellent documentation because it seamless to read and flowed extremely well. If you have ever read bad documentation before, you know that it just reads like a wall of text, super messy and unorganized.

What I am trying to get across is that it is a blessing to have someone more experienced give honest feedback on your work because you assume you are doing everything right if no one points out the flaws in your work. This is one of the reasons why I admired this engineer so much. At Google, people are really nice and they don't want to step on your toes but that can sometimes mean that they won't be honest with you. This engineer, however, cared very deeply and that's why I liked him so much.

I don't want to bore you too much with the details of the story so let me now dive into what I learned from that meeting and what goes into writing good design documents.

## The Art of Writing Effective Design Documents

### Avoiding Assumptions About Reader's Knowledge

I am sure you have come across a technical video where the author assumes some level of knowledge, which leaves you to do your own research trying to understand the ten different fancy terms they mentioned within the first thirty seconds of the video. Writing documentation as a software engineer is very similar. When you are writing documentation for a project you are working on, you are in the weeds and naturally you may assume a certain level of knowledge from the reader. But just because it is obvious to you doesn't mean it is obvious to the reader, especially when we don't know who is going to be reading our documentation.

This is why if you introduce terms or concepts that the reader might be unfamiliar with, it is your responsibility as the author to give the reader some context. This doesn't have to be extensive as nobody wants to spend an hour reading a preamble, so the aim should be to get the reader on the same page. Something along the lines of, "if you are unfamiliar with X, here is a link that explains it well" and depending on the reader, they might choose to click on the link or keep reading the documentation.

This leads me on to my second point of being concise while still providing detail.

### Balancing Detail with Conciseness

When someone starts reading your document, they might be completely unfamiliar with the problem and as the author, it is your job to provide a preamble while balancing detail and conciseness. For example, if you are writing documentation for software that uses microservices, it is unnecessary to go into low level detail on what each microservice comprises of and how it works. Instead, a simple URL that links the reader to the microservice would be more appropriate.

You might choose to provide more detail later on in the document but it should be up to the reader whether they wish to read the document further.

Striking a balance between detail and conciseness also ensures that the person who maintains the codebase in the future can understand the thought process that went into the design relatively easily. When they are reviewing your work, they don't need to know the exact details. 

Unlike a homework assignment that can be written and forgotten about, code is never really a finished product and someone will be maintaining it in the real world, and you need to make sure that when they read your documentation, it gets the point across well.

To drive this point home even more and this may sound harsh, nobody really cares about your work as much as you do. At Google, I gave presentations in front of very senior people like directors and I learned that nobody is paying as much attention to you as you are. This also goes to highlight the importance of keeping your documentation short.

In fact, you might not believe this but there might be times when a reviewer just rubber stamps your work because it's written poorly and they don't understand it. Even in a scenario like this, the responsibility falls on the person who submitted the work. 


### Practical application from NeetCode

Unfortunately, I don't have examples of documentation I wrote at Google, but the closest thing I have is the [Design a YouTube Clone](https://neetcode.io/courses/lessons/design-youtube) design doc on this website, which is also part of the [Full Stack Development](https://neetcode.io/courses/full-stack-dev/) course.

I designed this document so that if I ever have to go back and refresh my memory on what the project entails, I can do that within 10 minutes. The document also adheres to the two points I mentioned in the section above.

In the design document, I have an architecture diagram (shown below) which contains terms specific to the projects. You might not know what Cloud Run or Pub/Sub is when you are glancing at the diagram. Therefore, instead of assuming this knowledge and letting the reader do their own research, I give a high level overview of all these terms in the design document to bring the reader on to the same page so they aren't confused when I use the same terms later on in the article.

![architecture](/2024-01/public.webp)

> If I wanted to take it a step further, I could have also included external links which would provide the reader with the option to explore the terms further, should they choose to do so.

I also aimed to strike a balance between detail and conciseness. The introduction section covers what the reader can expect in the document and the goal of the design doc. I then have "Background" and "Requirements" sections which take about 2 minutes to read and help the reader understand the scope of the project.

![requirements](requirements-background.png)

The document then goes into more detail in the section called "Detailed Design". Notice that I did not start with the "Detailed Design" because the reader might not care and is simply looking to understand what the design document covers in the first place. So, by the time they reach the "Detailed Design" section, they already have a solid understanding of what they can expect in the rest of the document and decide whether they would like to read further.

The image below demonstrates the difference between high level design and detailed design. Notice how concise the high level design is, but a balance is achieved through the inclusion of the detailed design.


![design-comparison](design-comparison.png)

### Self-Improvement Through Constructive Criticism

While constructive criticism is never easy to digest, I think it helps to be self-critical to a certain degree. To improve, you need to be honest with yourself. In my case, every time my lead would send in a design document of his for review, I would read them even though I wasn't the reviewer. I wanted to improve and was willing to put in that effort.

Feedback is not always the easiest to process when you are on the receiving end but it is a great way to skyrocket your learning.


### The unwritten rule

Before I end this post, I do want to mention that nobody really tells you how essential written communication is for promotions. The higher the level of an engineer, the more important written communication becomes because you have more influence and the only way to get promoted is to be able to demonstrate that you can do the job before you even get the job.


## Closing Thoughts

Hopefully this post was able to shed some light on the importance of written communication and you learned from the experience I shared as much as I did. I am very glad that I got to experience this because in the real world, people don't always tell you the shortcomings of your work. Even with YouTube, if I make a LeetCode video and it doesn't do as well, people don't always leave a comment. 

At the end of the day, it is your job to be proactive and look for ways to improve.



<!-- 

- Next objectives:
  - Make it more concise
  - Add images with labels



 -->