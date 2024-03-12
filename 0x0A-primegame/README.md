# 0x0A. Prime Game
:open_file_folder: Specializations - Web Stack programming ― Back-end  
:bust_in_silhouette: by Carrie Ybay, Software Engineer at Holberton School  
:copyright: **[Alx School](https://https://intranet.alxswe.com/projects/1223/)**  
:bookmark: Algorithm | Python

## Resources
### Read or watch:
* ### Prime Numbers and Sieve of Eratosthenes:
    * [Khan Academy: Prime Numbers:](https://www.khanacademy.org/math/cc-fourth-grade-math/imp-factors-multiples-and-patterns/imp-prime-and-composite-numbers/v/prime-numbers) Introduction to prime numbers.
    * [Sieve of Eratosthenes in Python:](https://www.geeksforgeeks.org/sieve-of-eratosthenes/) A step-by-step guide to implementing the sieve algorithm in Python.

* ### Game Theory Basics:
    * [Game Theory Basics:](https://www.investopedia.com/terms/g/gametheory.asp) An introduction to dynamic programming with Python examples.

* ### Dynamic Programming:
     * [What Is Dynamic Programming With Python Examples:](https://skerritt.blog/dynamic-programming/) An introduction to dynamic programming with Python examples.

* ### Python Official Documentation: 
    * [Python Lists:](https://docs.python.org/3/tutorial/introduction.html#lists) Managing lists in Python, useful for tracking the game state.


By grasping these concepts and making use of the recommended resources, you will be well-equipped to approach the problem with a solid understanding of both the mathematical and programming challenges involved. The key to success in this project lies in applying efficient algorithms to manage the game’s state and making optimal decisions based on the game’s rules.

## Additional Resources
* [Mock Technical Interview](https://www.youtube.com/watch?feature=shared&v=Jw2pniZCLi8)

## Requirements
### General
Allowed editors: ```vi```, ```vim```, ```emacs```
All your files will be interpreted/compiled on Ubuntu 20.04 LTS using ```python3``` (version 3.4.3)
All your files should end with a new line
The first line of all your files should be exactly ```#!/usr/bin/python3```
A ```README.md``` file, at the root of the folder of the project, is mandatory
Your code should use the ```PEP 8``` style (version 1.7.x)
All your files must be executable


## Tasks
* [x] 0. Prime Game

Maria and Ben are playing a game. Given a set of consecutive integers starting from 1 up to and including n, they take turns choosing a prime number from the set and removing that number and its multiples from the set. The player that cannot make a move loses the game.

They play x rounds of the game, where n may be different for each round. Assuming Maria always goes first and both players play optimally, determine who the winner of each game is.

* Prototype: def isWinner(x, nums)
* where x is the number of rounds and nums is an array of n
* Return: name of the player that won the most rounds
* If the winner cannot be determined, return None
* You can assume n and x will not be larger than 10000
* You cannot import any packages in this task

Example:
  * x = 3, nums = [4, 5, 1]

First round: 4
* Maria picks 2 and removes 2, 4, leaving 1, 3
* Ben picks 3 and removes 3, leaving 1
* Ben wins because there are no prime numbers left for Maria to choose

Second round: 5
* Maria picks 2 and removes 2, 4, leaving 1, 3, 5
* Ben picks 3 and removes 3, leaving 1, 5
* Maria picks 5 and removes 5, leaving 1
* Maria wins because there are no prime numbers left for Ben to choose

Third round: 1
* Ben wins because there are no prime numbers for Maria to choose

#### Result: Ben has the most wins

## Software engineer
Contact me @ [Ameh Jacob Elijah](https://www.starjakes.com.ng)
