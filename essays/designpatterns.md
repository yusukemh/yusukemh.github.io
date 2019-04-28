---
layout: essay
type: essay
title: Prototype Your Code
# All dates must be YYYY-MM-DD format!
date: 2019-04-27
labels:
  - Design Patterns
  - MongoDB
---

One of the most amazing features of software engineering is that we can code however we want, yet working completely. In other words, there are always other ways to code besides the "correct" answer, or the solution you just came up with. Well, is it really amazing? I would say no, because you could end up with the worst solution after dozens of trial of coding, not knowing there is one beautiful solution. What if there is already a guid which leads you to very rough, but yet an effective solution? Wouldn't you start from the guide?

Design patterns are patterned types of structures of code, to cope with repetitive recurrence of problem solving. It describes some of the most commonly used approach towards problems solving in software engineering. Each design pattern has pros and cons that are well studied over time, so we as a coder can choose which design pattern to apply depending on the goal of your project. 

One of the well known design patterns is Publish Subscribe Design Pattern. The way it works is first, what we call publisher "publishes" data, not necessarily knowing which component of the project would refer to it. Then, in order to retrieve the published data, each component has to "subscribe" the publication. This greatly enhances flexibility of use of data. 

MongoDB directly applies this idea to its functionality, and I have experienced the design pattern over the course of this semester of Spring 2019 at UH Manoa. When dealing with data using MongoDB to make a web application, each bundle of data is called collection. Collections have to be published, and each component where you want to manipulate with the data has to subscribe the publication so that the component can actually access the collection. This is exact replication of Publish Subscribe Design Pattern and it helps us follow the pattern, rather than trying to figure out by ourselves.

Design pattern, again, really enforces flexibility and reusability of codes if applied properly, and it provides us with various choices of programming structures.