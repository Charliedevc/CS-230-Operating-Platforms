# CS 230 – Operating Platforms

## Draw It or Lose It – Software Design Project

This repository contains my software design document for CS 230 at Southern New Hampshire University. The project focused on designing a cross-platform application for The Gaming Room and evaluating different operating systems to determine the best approach for development and deployment.

## Project Reflection

### Briefly summarize The Gaming Room client and their software requirements.

The Gaming Room wanted to expand its existing Android game, *Draw It or Lose It*, into a web-based application that players could access from different devices. The game involves teams competing to identify images as they are gradually revealed. The system needed to support multiple teams and players, prevent duplicate names, assign unique IDs, and keep game information consistent across devices.

### What did you do particularly well in developing this documentation?

I think I did a good job comparing the different operating systems and explaining which platform would work best for the application. Instead of just choosing one, I looked at Linux, Windows, macOS, and mobile platforms to understand their advantages and limitations. I also think I did well explaining how the Java classes work together and why a centralized server makes sense for this game.

### What about the process of working through a design document did you find helpful when developing the code?

The most helpful part was breaking the application down into smaller components before focusing on the code. Creating the domain model helped me understand how the Game, Team, Player, and GameService classes connect. It made it easier to see how inheritance, encapsulation, and the Singleton pattern could be used to organize the application.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would improve the section covering scalability and database storage. The current design works as a starting point, but a larger application would need to support multiple servers and save game information between sessions. I would go into more detail about how a shared database would work and how the system could prevent conflicting updates when multiple games are running.

### How did you interpret the user's needs and implement them into your software design? Why is this important?

I focused on making sure the application could support players using different devices without affecting how the game operates. That's why I recommended keeping the main game logic on a Java server and using a responsive web interface for players. I also considered requirements like unique names, team management, and consistent timers. Understanding user needs is important because even if an application runs correctly, it isn't successful if it doesn't actually solve the client's problem.

### How did you approach designing software? What techniques or strategies would you use in the future?

My approach was to understand the requirements first, organize the application using a UML diagram, and then evaluate the platforms that could support it. I also considered things like security, scalability, cost, and maintenance instead of focusing only on getting the application running. In future projects, I would continue using UML diagrams and design documentation while also incorporating testing and performance planning earlier in the process.
