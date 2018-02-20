# KatBot v0.1

## About
KatBot runs on the **discord.js** libaray with **Commando** support.

## Features
- Reaction based voting with :thumbsup:, :thumbsdown:, :shrug:
- Reaction based polls with :one: to :keycap_ten: options

## Requirements
npm install discord.js  
npm install discord.js-commando

## Documentation
- !vote "Do you like to vote?" "I mean who doesn't right?!" 10
  - A yes/no/don't care question to be voted on 
    - Must be 10 to 100 characters in length
  - *(Optional) Further description of the question*
    - Must be 10 to 200 characters in length
  - *(Optional) Length of vote in minutes*
    - Maximum of 60 minutes
    - defaults to 0, the vote never ends
- !poll "What's your favourite food?" "Hot Dogs,Pizza,Burgers,Fruits,Veggies"  60
  - A question to be polled on
    - Must be 10 to 100 characters in length
  - 1 to 10 polling choices, comma-separated
    - Must be more than one choice
  - *(Optional) Length of vote in minutes*
    - Maximum of 60 minutes
    - defaults to 0, the poll never closes

## Example Output
![Example Output](https://i.imgur.com/uxXg9mS.png)

## To do
- Better permissions / roles handling
- Add even more features!