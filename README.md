# Reddit Pokedex Bot
Pokedex bot for Reddit! 

## Project Abstract

The project that I will be implementing this semester is a reddit bot that can be be called via reddit comment. The bot will be able to provide a various amount of stats that can be fetched from the pokemon API (https://pokeapi.co/). The stats that are fetched will then be replied to the comment that requested the pokemon's stats. There is a huge amount of Pokemon currently (894) and will only continue to go up. With the sheer amount of stats and information it can be really hard to keep track of who does what in the game. This will be able to help people among various subreddits be able to access the information without having to travel to another site. 


![Use Case Image](PokeDexBot.png)

## Project Relevance

This project will tie in a various amount of of topics covered in the course such as Object Oriented Design, Debugging, and Access to a Database. In my experience in working with accessing databases is that it can be very difficult to access the specific nested data inside of the JSON, so that will require extensive debugging as well as Object Oriented Design. My group will also use UML to model the flow of information within the program so we can accuratly show how our bot achieves reaching these stats. 

## Conceptual Design

Since this is not an open source project, this will be built from the ground up. The basic design for the bot is outlined in the diagram above. The bot will be able to call an API using parameters specified in the user's comment who called the bot. The information returned by the API will be then be formatted by the bot into a proper string and then the bot will reply to the user who originally called it with the formatted string containing the data.

## Required Resources

- Python
- PokeAPI
- Reddit API

