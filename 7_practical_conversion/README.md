# How to manipulate a stream in NodeJS

In this folder you'll find the end result of what we learned in this article. Hear you'll find two main files:

- **make_1g.js**: this file uses the Chance module to create a txt file of a certain size. The file will be filled with the following data: `Name Last Name <email@exampl.ecom>, `.
- **converter.js**: this is the interesting one, where we are going to take the file created using `make_1g.js`, and create a new one with new content. We are going to change the `,` to `;`, so the end result will look like this: `Name Last Name <email@exampl.ecom>; `.

## Important

Generating the big file will will take some time depending on you system, so be patient. While converting on the other hand, will be super fast 😊.