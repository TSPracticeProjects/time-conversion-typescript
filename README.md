# time-conversion-typescript

## Description

A TypeScript program that converts seconds since the start of the day into a formatted time string (HH:MM:SS). This project demonstrates how to handle time conversion and formatting using TypeScript, along with user input handling using the [`@inquirer/prompts`](https://www.npmjs.com/package/@inquirer/prompts) library.

## Examples

- **Input 1**: `380` seconds
  - **Output 1**: `00:06:20`
- **Input 2**: `7560` seconds
  - **Output 2**: `02:06:00`

## Solution

The solution is implemented in the `src/main.ts` file. This TypeScript program takes an input in seconds from the start of the day and converts it to a formatted time string displaying hours, minutes, and seconds (HH:MM:SS). You can view and explore the complete implementation in the provided code.

## Prerequisites

Before running this project, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Nodemon](https://www.npmjs.com/package/nodemon) (for development)
- [rimraf](https://www.npmjs.com/package/rimraf) (for cleaning build artifacts)
- [`@inquirer/prompts`](https://www.npmjs.com/package/@inquirer/prompts) (for handling user input)
