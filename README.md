# Budget-Tracker

## Description

A simple budget tracker where users can post new transactions to add or subtract funds.

This app uses a service worker and indexedDB to function offline.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

Installation requires the user to run "npm i" to install all neccessary packages, and then run "node server.js" to launch the server. Dependencies used include: express, mongoose, morgan, and compression.

## Usage

To use the app, visit [link to deployed app](https://evening-bastion-62363.herokuapp.com/).

Fill out the two input fields with the name of the transaction and the transaction amount, and then click either the add funds button or the subtract funds button. The transaction will then be either added or subracted from the displayed total at the top of the page. Additionally, a table displays all transactions, and a graph displays the total over time.

This app will function offline, and when the user reconnects, the offline entries will be added to the database.

[gif of usage](./assets/budget-tracker.gif)

## Credits

My study group helped me troubleshoot my application: Alex Jrugs, Chip Long, Jared Sutch, Lauren Gabaldon, Tarik Maggio, and Josh Lee.

## License

MIT License

Copyright (c) [2021] [Lacey Pape]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
