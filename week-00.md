# Week 0 — Getting Ready to Learn IT

## Accomplishments

- Set up Bitwarden for password management and 2FAS for two-factor authentication (2FA).
- Enabled 2FA on Google, Bitwarden, and GitHub and saved recovery codes.
- Created my GitHub learning journal repository and its README.
- Created a TryHackMe account and put together a YouTube IT course playlist.
- Completed Module 1 of *Learning How to Learn*.
- Studied password reuse, unique passwords, password managers, and how 2FA works.
- Worked through security authorization scenarios and practiced deciding whether I had permission to proceed.
- Chose a flexible routine of five study sessions per week instead of fixed calendar blocks.

## Reflections

### Understanding what protects my accounts

I used to reuse passwords because I worried I'd forget them. When Google offered to save a password or a site prompted me to enable 2FA, I'd accept and assume my account was safe. Once I looked at what those features actually do, I understood how a password exposed on one site could put my other accounts at risk if I'd reused it.

A password manager helps me use a different password for every account without having to memorize them all. Two-factor authentication adds a separate check when I sign in. Using both Google Password Manager and Bitwarden does not by itself make my accounts more secure. The protection comes from strong, unique passwords and a second factor where available. I now understand the role each tool plays.

### Using AI to learn

I put too much trust in Gemini early on. I was following Git commands in the terminal to upload my Markdown files to GitHub before I'd learned Git. When I tried to correct my mistakes, I was frustrated that I couldn't tell when my credits had run out or why the responses had changed. I switched back to ChatGPT and rebuilt PogoOS after making mistakes in the original setup.

That experience helped me understand my own responsibility for how I learn. I have a better sense of what to ask and how to ask it now. I want my course to guide what I learn and AI to help me work through questions. When I get to Git, I want to understand what a command does before I run it.

---

The original Day 0 assessment follows. It preserves my initial answers, tutor feedback, and study targets as a record of where I started.


# Week 0 Baseline Quiz & Gap Analysis

## Question 1: What is the difference between hardware and software?
My Answer: Hardware is the physical aspect of a computer. Software is the data protocol of what you want the hardware to do.

*Tutor Feedback: Strong. Clear distinction between the physical machine and the instructions telling it what to do.*
**Target Phase: Week 1**

## Question 2: What does an operating system do?
My Answer: It's the "language" of the computer. It manages all the commands of what you want to do.

*Tutor Feedback: Gap. Mixes up the OS with binary/programming languages. Focus on how the OS acts as the middleman managing hardware resources and software processes.*
**Target Phase: Week 2**

## Question 3: What is an IP address?
My Answer: Your internet's network address.

*Tutor Feedback: Partial. Good intuition, but needs the distinction between a device's private IP (inside your home/shop) and your router's public IP (on the internet).*
**Target Phase: Week 3**

## Question 4: What is a file path?
My Answer: The path it takes to get to your file. IE: Desktop to Emulators to NES to Super Mario Bros.

*Tutor Feedback: Strong. Spot-on practical understanding of nested folder hierarchies.*
**Target Phase: Week 2 & Phase 2**

## Question 5: What is a password manager for?
My Answer: A storage for your database of passwords.
*Tutor Feedback: Partial. Correct on encrypted storage, but also note that it generates unique, high-entropy passwords for every account.*
**Target Phase: Week 0 & Week 26**

## Question 6: What does it mean to "encrypt" something?
My Answer: To secure and protect it against attacks.

*Tutor Feedback: Gap. Describes the goal of security rather than the mechanism. Focus on how encryption scrambles readable data (plaintext) into unreadable ciphertext using a mathematical key.*
**Target Phase: Week 12 & Week 26**

## Question 7: What is a server?
My Answer: A computer that is mainly used to hold data.

*Tutor Feedback: Partial. Servers do store data, but their defining job is actively running services and responding to requests from other computers (clients) over a network.*
**Target Phase: Week 3**

## Question 8: What is the cloud, in one sentence?
My Answer: A collection of servers that hold data that you can access without taking up space in your computer.

*Tutor Feedback: Strong. Great grasp that the cloud is remote servers accessed over the internet, which you will expand beyond storage to rented compute and networking.*
**Target Phase: Phase 6**

## Question 9: What is a bug?
My Answer: A part in code that is incorrect or that is causing an issue in an application.
*Tutor Feedback: Strong. Exact definition of a software defect.*
**Target Phase: Phase 4**

## Question 10: Name one way attackers trick people into giving up access.
My Answer: By pretending to be a legit company and having you download their fake software which is actually a software that gives them access to your computer.

*Tutor Feedback: Strong. Accurately describes social engineering (phishing/impersonation) combined with a Trojan/RAT (Remote Access Trojan).*
**Target Phase: Phase 5**

## Phase 1 Watch List (Weeks 1-3 Focus Areas)
* **Week 1 (Inside the Machine): Separate the computer's true "language" (binary 0s and 1s) from the physical hardware parts (CPU, RAM, storage).**

* **Week 2 (OS & Files): Watch how the Operating System sits between your applications and hardware like a shop manager assigning chairs and supplies.**

* **Week 3 (The Internet & Web): Track how a server actively listens for requests, and compare your computer's private IP address to your router's public IP address.**