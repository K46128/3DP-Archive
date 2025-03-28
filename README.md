# The Prototype Project
This project was started back in early 2023 as a way to build an affordable, and fast 3D printer that undergoes updates and changes once in a while.

## Inspiration
I originally based the project around the Ender 3, but I realized the abilities of the electronics of the printer were really, *really* underpowered for the speed of printing I was aiming for. There were many problems.

# Problems with Planning
After realizing the scale of the project, I realized the problems that I was going to encounter. At the time, I did not have much engineering experience, and even less programming experience.

## Mechanical Issues
Since I was not that good of an engineer back in 2023, I did not have a good base for making a full 3D model of the printer. I was originally planning to just make a 3D model of the full printer, but halfway through doing this I just decided to design it kind of like a driven dimension in Fusion 360. It took up to *10 tries* to correctly design a model for the ... *motor mount???*

>[!NOTE]
>I was not a very experienced person with Fusion 360 at this time...

## Software Issues
I am by no means a software engineer. However, when it comes to things like this, I can at least try.
When I found out about how hard it was to make firmware for a 3D printer, I basically gave up on that. It requires lots of experience with software engineering. So, I bought a raspberry pi and decided to test with Marlin firmware. After testing and debugging issues, rewiring stepper drivers, I managed to get it to work. So, I moved to Klipper.

### Configuring Klipper
I will not go into detail of what I did to configure Klipper for a custom printer. It took months of debugging and long 3-4 hour sessions on my computer. But in the end, I got it to work. I know that if you're reading this you might be an experienced software engineer or someone who just has experience with the Klipper firmware. I know this seems easy, but it was a huge accomplishment at a time, because there was nothing like this printer. I had no youtube tutorials to help, just the VS Code debugger and my own mind.

> [!IMPORTANT]
I am currently working on exporting all of the files from the Fusion 360 3D model.
