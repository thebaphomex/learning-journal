# Week 1 — Inside the Machine

## Accomplishments

- Drew a PC hardware diagram and explained what the CPU, RAM, storage, motherboard, and power supply do.
- Explained the difference between RAM and storage using a power-loss scenario.
- Practiced converting between binary and decimal and worked through AND, OR, NOT, and XOR truth tables.
- Practiced tracing signals through multiple gates and explained the sum and carry outputs of a half adder.
- Used Task Manager to compare CPU activity before opening Calculator, Clock, and Paint, while they were running, and after closing them.

## Reflections

### Making sense of logic gates

The AND gate clicked when I thought about a door that needs two keys. If Mae and I each have a key, the door only opens when we both use ours. In a truth table, that’s the one row where both inputs are 1. Tracing one gate at a time also helped me work through longer problems because each gate’s output becomes the next gate’s input.

### Watching what happens when I open an app

I used Task Manager to watch CPU activity as I opened and closed three Windows apps. Checking before, during, and after gave me a baseline to compare against and let me see what changed when the apps closed.

I thought the memory would be the the one to spike, but to my surprise it was the disk that jumped. I tried it with a few apps and every time it was something different. Sometimes the CPU would spike and blip. Sometimes it was the memory or storage. And then the CPU and Memory both dipped upon closing. I know there were many factors to consider like processes running and applications still in cache, but it was interesting seeing different things get affected and the mystery and wonder behind what was going on behind the scenes that affected the changes. 

## Checkpoint

I passed the practical checkpoint on November 16, 2026, and scored 8/8 on the hardware and binary quiz. I used my PC diagram, explained RAM versus storage, converted binary numbers, and worked through what happens to unsaved work when a computer loses power.

## Additional Thoughts

Although it wasn't in my curriculum, there were a few things that I did outside of it that were IT Training related:

- **AI Assistant**

I use a ChatGPT project I call Pogo to track my progress, follow the daily plan, and keep lessons from slipping through the cracks. After a few frustrating days, I realized I was getting different guidance on my Windows PC, on my iPhone, and in ChatGPT Voice. Through trial and error, I wrote an AGENTS.md file and added custom project instructions so Pogo would use the same teaching guidelines and training records wherever I picked up a lesson.

- **Remote Access**

I’d been doing all my training on my Windows PC, but I wanted to get more comfortable with macOS by using my MacBook Air. I also wanted to be able to get to something on my desktop if I was away from home.

I put together a setup using Python, Apple Shortcuts, and OpenVPN so I could wake my Windows PC from my Mac. Then I used RustDesk to connect to it. I tested the setup over my phone’s hotspot so I could verify it worked from outside my home network. It took about seven hours of troubleshooting, including changes to my router and fiber equipment, but I finally got it working.

- **Input Device Debate**

I got into a debate with Mae and Lyric over what makes something an input device. My argument was that a device can send and receive information, so I didn’t see why we’d call it one or the other. I finally conceded after a “Eureka!” moment. The label describes the role the device is playing from the computer’s perspective. A touchscreen made that distinction easy to picture. It provides output when it displays an image and input when it sends my taps back to the computer.

- **iPhone Apps**

Candy Crush had a pretty solid grip on my downtime between clients, so I downloaded a few learning apps, including Mimo, Code Life, and TryHackMe. I wanted to keep the fun part of playing on my phone while using some of that time to practice what I’m learning.

- **Commute Quizzes**

Mae and Lyric started quizzing me on IT topics during commutes. They’re at different stages in their own IT experience, so they ask different kinds of questions and explain things in different ways. Hearing both perspectives gets me to explain my reasoning out loud and helps me catch where my understanding is still fuzzy