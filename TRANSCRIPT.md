# What is Cryptography (Alberto)


# Why is Cryptography important? (Alastair)
The internet is open to eavesdropping as your information travels multiple servers and nodes before it reaches your destination server.

* Banking and Finance
  * Securing financial information, from bank transfers, keeping bank accounts synchronized, stock markets and many more.
  * Ebay - February to March 2014, an employee credential was hacked, allowing hackers backdoor access to Ebay's user database. 80% of encrypted hashes (used to encrypt passwords) can be bruteforced within 48 hours.
  * Chase - Spring to Mid August 2014, JP Morgan servers compromised because it did not have two-factor authentication (think Gmail). This was because JP Morgan have been using many old systems, merged and bought from other banks.
  
* Military and Intelligence
  * December 4 2011, a Lockheed Martin RQ-170 drone was captured by the Iranian government by its cyberwarfare unit. A GPS spoofing attack gave the drone falls GPS data to make it land at what it believed was its homebase in Iran instead of Afghanistan.
  * Most weapon systems and even manually controlled jets have automation and remote controlled structures that could be hacked into if not encrypted with care.
  * Navajo Codetalkers, World War 2
  
* Personal Security
  * As we enjoy a world that is more connected and convenient, with all our data accessible from almost any computer or computing device, our private information is all the more dangerously left exposed.
  * Millions of sites are constantly attacked everyday.
  
* Video


# Personal Story: Hacking my Brother (Alastair)
A personal example of why encryption is important (sibling rivalry). I created a Visual Basic program back in the summer of 2010 to see if I can obtain the keystrokes my brother would type on his computer precisely every millisecond, every day.

I designed the program so that it would not show up in the system process (task manager). The program has 3 components:

* 2 timers
  * First timer that ran a loop every millisecond against every keyboard character to pick up what he would type.
  * Second timer that ran every 24 hours to send me an email of the stored characters he has been typing.
  
This showed me just how dangerous and vulnerable computers to the point that I wanted to counter myself by creating my own artificially intelligent antivirus and malware system which would largely use behavior to analyze how viruses and malicious software act, and destroy them while keeping the surrounding architecture intact.

With time and my resources, I gave up because this was just too hard.


# Diffie Hellman Key Exchange (Alastair)
The main strength of the Diffie Hellman is that it is about finding an algorithm/function is relatively easy to come up with an answer with, but hard to find a reverse (inverse) function for that answer.

For example, when you mix paint, it is easy to combine multiple shades of paint to get a new paint, but hard to trace paint back to its parental shades of paint.

An example of something that is relatively easy to solve but hard to have a reverse process for is prime factorization especially for huge numbers.

Write down equation of Diffie Hellman on board, conceptually, using Wikipedia image.


# SSL and TOR (Alastair)
Watch this: https://www.youtube.com/watch?v=LAcGiLL4OZU

* Secure Server Layer
* The Onion Router
