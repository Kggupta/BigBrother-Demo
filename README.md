# Big Brother - DEMO

## The Problem

There is a popular Discord Bot which simulates the real-life stock market with game currency. We found that the players didn't understand how it worked and were getting frustrated by losing all their money. This wasn't enjoyable for the users so our team released an assistant bot, _Big Brother_, which will do the complex analysis of the (simulated) stock market so you don't have to!

## Overview

Big Brother is a Discord bot that watches a stock market game to track stock and user data. It gives intuitive user analytics and maximizes user profit. The project has been in active development since 2020. The bot now supports over **100,000 users**.

It's primary purpose is to analyze trends in stock market data such as stock prices, sentiment analysis, volume, and more. It also analyzes trends in user data such as stock purchases/sells, online periods, and play habits to give users the highest possible profits. We put an emphasis on seamless automation so the inner workings are entirely hidden from the user and requires very little human intervention. Set it and forget it!

The name is inspired by George Orwell's _1984_, where "Big Brother" is always watching.

_The best software should do everything it's required to (and more) without being noticed!_

## My Team

I could not have done this myself, I have two amazing teamates.

| Role              | Teammate                          |
| ----------------- | --------------------------------- |
| Quality Assurance | https://github.com/seanfromonline |
| Graphic Artist    | https://github.com/cpizzapasta    |

We all participate in project management and the 4 week sprints.

## Development Details

This project was made using the DiscordJS library, based on NodeJS to develop the bot.

The backend server was developed using NodeJS and Express, it connects to a MongoDB database.

I use Docker to bundle the projects into containers. They are deployed in an AWS EC2 instance, we used Heroku and DigitalOcean as well.

You can access the code for the **DEMO REST API** in this [repository](https://github.com/Kggupta/BigBrother-Server). The repo shows a couple of the basic endpoints our API provides to the client.

The project is supported by our generous patrons, the project would not be possible without them. Our Patreon page can be found [HERE](https://www.patreon.com/bigbrotherbot).

You can invite the bot to your server using this [link](https://discord.com/oauth2/authorize?client_id=801210683483619438&permissions=347200&scope=bot).

Use this [link](https://top.gg/bot/801210683483619438) to view some of the reviews by our users.

## Note

Please note that this project is closed source. To view the full code, contact me directly by email.

## Key Features

### Stock Market

The bot analyzes stock market trends of a simulated stock market and buys/sells shares for its users. It customizes its suggestions based on how the user plays, such as risk tollerance, so every user gets the best possible profit according to their preferences.

We saw that the feature **Doubled user profit** on average, and **nobody took a loss**.

### User Tracking

The bot will also track users in the server and learn how they play the game, giving them useful statistics and reminders to maximize profit and efficiency. We also build graphs to rank them against all other **+100k users** in real time.

### Reminders

The bot also notifies users about tasks they can do in the game, so they can rise in leaderboards and compete with their friends more effectively.
