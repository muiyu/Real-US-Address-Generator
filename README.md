# Real US Address Generator

***Please do not use this project for illegal purposes!***

This is a simple web application that generates random real US addresses, names, genders, and phone numbers. You can also specify a state to generate addresses from that particular state.

**This repo is a fork from the [origin repo](https://github.com/chatgptuk/Real-US-Address-Generator), and it allows you to run with Node.js instead of Cloudflare Workers.**

By the way, use this repo on Docker is what I really love. You know, as a Perfectionism, I really work on closing off env!

*I just be crazy for configing the development env for my DataScience courses.*

## Features

- Generates a random US address including house number, street, city, state, and ZIP code.
- Displays a randomly generated name and gender.
- Provides a randomly generated phone number corresponding to the state.
- Allows users to specify a state to generate the address.
- Includes a Google Maps iframe showing the location of the generated address.
- Clickable name, gender, phone number, and address to copy the details to the clipboard.

## How to Use

1. Open the application in your web browser.
2. A random address, name, gender, and phone number will be displayed.
3. Click on any of the details (name, gender, phone number, address) to copy them to the clipboard.
4. Use the dropdown menu to select a specific state and generate a new address from that state.
5. Click the "Get Another Address" button to generate a new set of details.

## Installation

Please make sure that you have `node` and `npm` on your device. You can use `node --version` and `npm --version` to ensure it.

1. Use `git clone https://github.com/muiyu/Real-US-Address-Generator.git` to clone this repo
2. Use `cd Real-US-Address-Generator` to enter the project folder
3. Use `npm install` to load the dependency
4. Use `PORT=3000 node worker.js` to run

## Example

Here's an example of what the application looks like:

<img width="804" alt="sources" src="https://github.com/user-attachments/assets/4a4f75d7-c766-4b43-90de-094445e8f81f">


## Personal Website

For more information or other projects, you can visit origin author's website: [chatgpt.org.uk](https://chatgpt.org.uk).

## License

This project is licensed under the MIT License.

---

© chatgpt.org.uk All rights reserved.
