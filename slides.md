
class: center, middle

# Make the right product, the right way with the right team
.octo-logo[![octo logo](./img/octo-logo.png)]

---
class: center, middle

## How to make a product users need?

???

Problem:

 - Hey I got the best idea in the world, it's the next Facebook !!
 - how are you so sure
 - I know it's going to work just fine
 - How about we test that first?
 - Yeah you are right let's build it right now and we will see!

Solutions: MVP
 - get early feedback with the least amnout of energy/time/money
 - example: Dropbox create a video

---
class: center, middle
.left[
### Buffer's MVP: landing page
]

.img-full-size[![buffer landing](./img/buffer-landing.png)]

???
engage customer with landing but no product, got a few early adopters to talk to and get needs first

---
class: center, middle

.img-full-size[![buffer landing](./img/trash-symbol.jpg)]

???
Early feedback -> valuable knowledge
MVP -> trash

---

class: center, middle

## Is this solution the right one?

???

Problem:

 - Hey Thibaut, I have tons of data in different databases that I would like to ingest in my datalake! But the compliance team preconize to use encryption from end to end and we don't have a lot of engineers.
 - Ok so you don't know if this is doable and which product on the market can do it?
 - Exact also I don't know if the design of my future architecture is what I need.
 - I am hesitating between two but I like one more.
 - How about we try the technology with one db first?

Solution: make a Proof Of Concept
- it helps to convince management that this is worthwhile to invest more heavily on a particuliar solution.
- try the technology, fail quickly, get feedbacks early, learn from it then be able to use what fits the best your needs.

---

class: center, middle

## How can I make a better application for my customers?

???

Problem:

 - Hey Nick, I have an application in production since a bit of time and every time we develop a new feature.
 - Do you you spend a lot of time to fix bugs every time you implement anything?
 - Yes, and on some parts of the code it is too painful to test it.

---

class: center, middle
.left[
### How can I make a better application for my customers?
]

Fix recurring bugs

**Unit tests**

Code feedback

???

Solution:

 - To Fix the fact that you have tons of bugs to fix: add unit tests every time you have a bug
 - feedback
 - refactor

---

class: center, middle
.left[
### How can I make a better application for my customers?
]

Develop new features

**Test Driven Development**

Short-ciruit feedback loop

???

Solution:
- As it is too hard to test, the code is probably too tightly coupled, functionalities are probably mixed and design might not be adequate.
- TDD will help to simplify solution, force dev to decouple the app components and make the app modular, design should emerge step by step.
- Force to divide big problems into smaller ones.
- We know a lot more quickly if a piece of code is working. Short-ciruit feedback loop.
- Tests are not influenced by implementation.

---

class: center, middle

## How is it possible to meet the expected requirements?

???

Problem:

 - Hey Thibaut, every time I develop a Jira ticket my business analyst are rejected even though I am certain beforehands that it is completed.
 - What happens? Features don't work? Or are there some misunderstanding?
 - Sometimes I think what I am doing is what is needed but it appears that I don't meet all the key details.
 - Do you have an easy way to find out what has been developped before ?
 - Actually it is also very hard because everything is dug into a long pile of Jira Tickets.

---

class: center, middle
.left[
### How is it possible to meet the expected requirements?
]

Specification by example

Acceptance Test Driven Development

Behavior Driven Development


Solution:
- Specification by example
- ATDD / BDD
- Specs are up-to-date
- Avoid to have regression
- feedback quick and reliable when automated.


---
class: center, middle

## How to solve issues between two individuals?

???

Problem:

 - hey the devops guy just called and ask why it's a not a Java application, but 23 micro-services?
 - Oh it's because I started to rewrite this critical part in RUST so it can be fast for our customer. I get shit done.
 - Yes but no one can understand it, no one can maintain it and people are struggling to deploy it
 - yes but the experience is better for our customer, plus Rust is DOPE. Actually we should rewrite everything in RUST.
 - ...
 - Actually JS is a useless language. Let's rewrite everything in Elm, I have read so many success story on Medium and HN.

 He's going to kick my ass...

Solutions: apply Non violente communication

---
layout: true
class: center, middle, non-violent-slide
.left[
### Nonviolent Communication
]

.non-violent-pic[![Nonviolent Communication](./img/nonviolent-communication-communication-skills.png)]

---


---
count: false


> You are an assh*le

---
count: false

> ~~You are an assh*le~~

---
count: false


> I felt you broke the team's trust,


---
count: false

> When you introduced RUST without telling anyone in the team,

> I felt you broke the team's trust,

---
count: false

> When you introduced RUST without telling anyone in the team,

> I felt you broke the team's trust,

> We expect much more from a senior

---
count: false

> When you introduced RUST without telling anyone in the team,

> I felt you broke the team's trust,

> ~~We expect much more from a senior~~

---
count: false

> When you introduced RUST without telling anyone in the team,

> I felt you broke the team's trust,

> I need to be able to trust you,

---
count: false

> When you introduced RUST without telling anyone in the team,

> I felt you broke the team's trust,

> I need to be able to trust you,

> Next time you need to share your idea with the team

---
count: false

> When you introduced RUST without telling anyone in the team,

> I felt you broke the team's trust,

> I need to be able to trust you,

> Next time you need to share your idea with the team

---
count: false

> When you introduced RUST without telling anyone in the team,

> I felt you broke the team's trust,

> I need to be able to trust you,

> Next time you ~~need to~~ share your idea with the team

---

count: false

> When you introduced RUST without telling anyone in the team,

> I felt you broke the team's trust,

> I need to be able to trust you,

> Next time you **should**  share your idea with the team
