# Hack Your Programmer Career:
# Getting Your Foot in the Door with Test Case Automation

<a href="#license">Copyright / License Info</a>

## Chapter 1
## Making a Beginning

This is a book about getting started in programming as a career. It's also a book about software testing and test automation. That may seem a bit strange to you, that a book about a career in programming would also be a book about software testing. You may well imagine that programming is creative and fun, a chance to solve problems all day long, right? Testing, on the other hand, is repetitive and tedious, and the folks in QA (Quality Assurance) are not the most popular guys on the team because they are the bringers of bad news. You might be thinking, "Shouldn't I be reading a book about something creative and fun, not something repetitive and tedious?"

Well, yes and no.

### Testing is Part of What Makes Programming Fun

First of all, implicit in the last paragraph is a sharp distinction between programming and testing that's really a little bit fuzzy the longer you examine it.  The software industry's move in recent years toward the idea of "agile programming" has brought with it a heavy emphasis on "test driven development" (TDD, with a capital TDD no less). The idea of test driven development is that as you're writing code you first write a small test that won't even compile or that fails, then you write just enough code to make that test pass, and you repeat throughout your project.

Test driven development doesn't give you the advantages of having a really great QA engineer pounding on your code, but what it does give you is:

* A suite of tests you can run before checking in new changes to the code, therefore helping you find bugs when they're easy to fix (because you just changed the code).

* Because you have this test suite, you gain a sort of reasonable confidence that you can make changes to the code without breaking anything. 

To me, the idea that programming is fun begins with that kind of confidence. In contrast, being asked to hack away (in the bad sense of hacking) at an untested body of code -- introducing new bugs and going back and fixing them again -- is the kind of fun I would save you from if I can.

### First Things First: Get the Job You Can Get

Paradoxically, another reason to focus on test automation as you're beginning your software career is precisely because programming is considered a relatively more "glamorous" job. In the move "A Beautiful Mind", there's a great scene in the bar room where John Nash (played by Russel Crowe) and some of his college buddies are in a bar, looking at three women they're hoping to take home. One of these women is a stunning blonde, clearly the most beautiful woman of the group, and Nash realizes that if they all go after the most beautiful woman, they'll alienate the other women and block each others efforts, whereas if they focus first on the less desirable ones, in Nash's words, they'll "all get laid."

The story of how John Nash learned to get laid is related to another story that didn't appear in the movies.

### How I Became a Programmer

About twenty-three years ago, I had a few things going for me. First, I was thirty, which I'm not any more. The other thing I had going for me twenty-three years ago was a Master of Arts degree, in, of all unlikely things, "The History and Philosophy of Science." 

If you don't have a degree in something like the History and Philosophy of Science, let me assure you: employers will not beat a path to your door.

However, because I also knew how to make certain modest things happen with a keyboard like being a power Word Processor and Spreadsheet user, I was able to get a job as an administrative assistant.I was making about $22,000 per year. $22,000 wasn't a lot of money then, and it's not a lot of money now, but I was happy to have it. That is, I was happy to have it until I started reading the want ads.

(That's right, go on, you can gasp or giggle a bit now if you want. I don't mind. When I was thirty, the Internet had hardly been invented, and people went looking for jobs from ads printed on dead trees. True story.)

When I started reading the want ads, I saw ads for computer programmers who knew skills like C, C++, and Windows. These jobs paid about $55,000 per year. Even with my wits dulled by a Masters Degree in the History and Philosophy of Science, I was still mathematically astute enough to be impressed by the significant difference between $22,000 and $55,000.

So I started to learn C, and C++, and Windows. To give my graduate degree its due, the thing it gave me (besides student loans) was the conviction that if I worked hard at learning something I could learn it. I read about C in the morning before work. I did the written exercises on my lunch break. I came home and tried things out on the compiler. When I finished my first two books on C, I started to learn Windows programming and C++.

### The Missing Insight

I had no idea how long it would take to break into the software industry, but as it turned out it took three. A friend of mine from graduate school (this degree is about to pay off) had gotten a job as a QA engineer, first in Indiana and later in Silicon Valley at Borland International, the same folks who made several of the compilers I had used to teach myself C and C++. My first job there was in technical support, helping folks with their usability problems on the C and C++ compiler. This was my entry level job. Two years later I had the job I started out to get �� software developer.

I might have gotten through this whole process quicker, but during the three years between beginning to learn programming and getting a job as a support engineer, I was focused on the programming job. Like all of John Nash's friends, I had my eyes on the blonde and was ignoring the other women in the room.

My missing insight was that not all jobs that let you do and learn programming are called programming jobs. In my case I was able to find a job called "Senior Tech Support Engineer", in which what I was Senior-Tech-Supporting was a programming language tool. This meant I got to continue writing sample code, but now I was getting paid for it. Sweet! And as if that didn't help me master my craft fast enough, part of my job was trying to answer questions from people with lots more experience than I had. 

Two years later I got the job I wanted as a programmer.

### Career Hacking Tip #1

If you want a job you're not yet qualified for, target your learning to another job that's __like__ that job you want, and that lets you do the job you want at least part of the time.

### Test Automation:  A Programmer's Answer to Career Hacking #1

To understand why test automation is such a killer app for your resume, it helps to understand the difference between "black box testing" and "white box testing".

## Chapter 2
## Let's Git Going 

Almost all professional development teams -- and in any case all of the ones where going every day won't quickly start to feel like you're being water-boarded -- use some kind of software version control system. Version control systems have a number of major benefits:

* They make sure that multiple developers can work on all the files in the same project simultaneously, allowing changes to be merged seamlessly.

* They make sure that a given release (or version) of the software can be reliably built, even after the software has undergone subsequent changes.

* They allow you to track changes to the product, for example, to measure improvements over time.

* They allow you to compare one version of a file to another to see (for example)where a bug was introduced.

* They allow you to roll back a single file, a set of files, or a whole project to an earlier state.

One version control system that's become quite popular in recent years is Git.Git works by letting you have your own full copy of your version control repository stored on your local machine. This allows remote teams to work independently without always being in touch with a central repository server. Because of this, Git has gained a rapid following on open source projects. Many of these are hosted on a very popular service, Github, which allows free accounts for open source projects and their contributors.

Having a Github account allows you to learn about how to use version control in a software team environment, but just as importantly, it allows you to demonstrate that you can use version control in a team environment.

### Setting Up an Account

To get started using Github and Git, point your browser to Github.com. There you'll see a sign up form where you can get started:

Pick a username you can live with (remember that you may show this to a future employer, so keep it clean and professional -- your name is a good choice), and enter your email address and password.

Once you've signed in by creating your account, you'll want to click the button that says Set Up Git.

On their setup page, GitHub now features a link to GitHub for Windows, which is currently these easiest way to install and configure Git on a Windows environment.  Click this link and run the installer.

[JCL More Needed]

### Forking a Repository

<div style="border:1px solid gray; padding:1em;">
<a href="#license" /><a rel="license" href="http://creativecommons.org/licenses/by-nc/2.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc/2.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/2.0/">Creative Commons Attribution-NonCommercial 2.0 Generic License</a><br />All copies of this work must retain the following copyright notice and links intact:  <a href="https://github.com/JohnLockwood/HackYourProgrammingCareer">Hack Your Programming Career</a> Copyright 2013 John Lockwood and <a href="http://www.particlewave.com">ParticleWave.com<a>.
</div>
