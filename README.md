# Blinky Board / 555 LED Chaser

This is my first hardware project I made for Hack Club's Stasis event. It's a classic 555 LED chaser that lights up LEDs in a set sequence at a set speed. I made it following the beginner project guide.

## Custom Feature
I added a pause button that stops the LEDs from rotating when held down and continues when the button is let go.

## Schematic
The schematic design was my first step, and the spot where I felt the most lost. It felt like I was thrown into the cockpit of a plane and was just told what to click without knowing what it actually does. I took it really slowly, however, and I constantly asked my Stasis sidekick questions, dropped a few in the #stasis channel and got Claude and ChatGPT to explain a few things, and I started getting familiar with it! About a day or two later I was finished with my schematic prepared with my own feature.

<img width="1898" height="1059" alt="image" src="https://github.com/user-attachments/assets/323e3321-1f61-4bda-8875-f07281ab8d53" />

## PCB
The second step was the PCB design. This part was also confusing, but not as before since I now knew what each circuit did and just did my best with following the beginner guide. I kept falling down the rabbit hole of routes getting in the way of each other and not being able to finish until a long time later, I learnt that I had 2 layers I could route on, which made this thousands of times easier. I used much less AI while making the PCB and would just search up something like a keyboard shortcut to make my life easier, but the biggest help was the lock in call I joined where I learnt a lot from the people in there and saved myself lots of pain and suffering. From that call I learnt about fill zones and how to use vias for grounding.

<img width="1502" height="1031" alt="image" src="https://github.com/user-attachments/assets/b7add8ed-78a8-4de6-9dfc-f93e082bb68c" />

## 3D Render
After finally finishing the PCB I then added my signature near the bottom (Mark. M). It felt really rewarding to look at the render, and it felt even better that the Design Rules Check passed on the first try.

<img width="1068" height="602" alt="image" src="https://github.com/user-attachments/assets/3fc176f3-8be2-44a8-bcc4-b83e4f41ae1e" />
