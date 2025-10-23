# Micro-CMS v1 Flag2
## Problem Statement
No mention Just Find the Flag
<img width="443" height="105" alt="image" src="https://github.com/user-attachments/assets/6aca8c05-e31a-4a8a-ac88-c5c482c444fd" />

## Information
Category: 

EASY  

Web

## Hints
* Make sure you tamper with every input
* Have you tested for the usual culprits? XSS, SQL injection, path injection
* Bugs often occur when an input should always be one type and turns out to be another
* Remember, form submissions aren't the only inputs that come from browsers

## Solution

<img width="430" height="194" alt="image" src="https://github.com/user-attachments/assets/e60664e3-302a-48e5-a898-4fed0a423b27" />

* So Lets try SQLi at URL
<img width="655" height="121" alt="image" src="https://github.com/user-attachments/assets/73259456-453a-4dd7-aeb4-ca951dd336a4" />


* Now on Edit Page
<img width="524" height="61" alt="image" src="https://github.com/user-attachments/assets/a1336d03-75f0-4950-8df4-b13fb4e8963f" />
Boom Found another Flag

## Flag
^FLAG^f935965a79465561e8b74f96e17b77446d4999ca89bc92ea798f7893eff00539$FLAG$
