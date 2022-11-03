# Object oriented simulation, PKU Library

In this challenge, you will are going to practice using classes and objects in Python. Getting used to object-oriented programming will help you understand many other advanced features in python.

## Background

In 2014, people were complaining about the occupation of lockers in Peking University Library (PKUL). Although PKUL asked the students not to leave their belongings in the lockers after they left the library, not everyone observed the rules. In fact, some people would leave their belongings in the lockers overnight. As the number of lockers was limited, this behavior led to much trouble for people who were trying to find an empty locker.

At that time, PKUL announced that they were going to empty the lockers every night. Some people protested, and insisted that the utilization efficiency of the lockers would decrease, if they were emptied on a daily basis.

In this challenge, you are asked to develop a simple simulation of the situation.

## Task

- You need to use computer simulation to model the process of students (readers) using lockers in PKUL, and show the "social utility" at any moment.
- Social utility is defined by total `happiness` and `madness`. Suppose a reader goes to the library, and the reader successfully find an empty locker, then the value for `happiness` would increase by 1; instead, if the reader could not find any empty locker, the value for `madness` will increase by 1.
- Find the social utility when PKUL empties the lockers daily, or empties them once a month.

## Hints

1. You can make assumptions on:
   - The number of readers who go to PKUL; suppose each reader would only go to the library exactly once a day
   - The number of lockers in PKUL
   - The percentage of readers who take their belongings away with them when leaving PKUL ("good readers"), and accordingly, the percentage of readers who leave their belongings in the lockers ("bad readers")
   - Many other parameters
1. You may want to pay attention to the following behaviors ("method")
   - Readers come to, and leave the library;
   - Lockers occupied by readers;
   - Readers looking for lockers, they may fail or succeed;
   - Lockers being emptied (by PKUL).
1. You need to use classes and objects, and you may need to think about the following aspects:
   - What are the concepts of class, objects, polymorphism, inheritance, member function/variable and their visibility (private vs public), and how are you going to design your simulation to incorporate these concepts?
   - Draw your UML diagram describing your design of the algorithm.
