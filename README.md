# XStart

a project generator!

![XStart-logo](https://i.imgur.com/O3RVw0E.png)


## What is XStart?

XStart is a cli tool that lets you generate a project base on json file.

# Instructions

Install XStart by running `npm install -g XStart` on your terminal or Windows CMD. This will install XStart globally.

- To create a project, type `XStart`, or simply type `XStart new <name of project>`

- Follow the steps and enter your Bot Token and Prefix.

- Once done, `cd` into your project by typing `cd <name of project>`

- To run the bot, type `npm run dev`. This will run the bot using `nodemon`, you MUST have `nodemon` installed, otherwise, use `npm run start`

You must have TypeScript installed. However, if you don't, during the installation process, if you selected TypeScript, XStart will ask you if you would like to install TypeScript, ts-node, and setup a basic tsconfig.json file. If you enter n (no), you will have to install these manually.

ts-node is a TypeScript interpreter for Node.JS, the dev script uses it along with nodemon, so be sure you have nodemon installed.

Otherwise, if you have TypeScript installed, you can skip this part and just run `npm run build` and then `npm run start`

## Will XStart support Python?

- Soon
