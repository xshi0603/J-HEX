# Clover
### Presented by J-HEX
#### Eric Li, Xing Tao Shi, Jacqueline Woo, Henry Zheng<br>SoftDev1 pd8<br>Project 02 -- The Final Frontier

## Website Link
[206.189.228.223](http://206.189.228.223)

## Demonstration Video
[Youtube [insert link here]](https://youtu.be/[insert_link_here])

## Description
J-HEX presents Clover, a financial manager where users will be able to input data about their finances, savings, and expenditures. The user will be able to see a history of their past spendings and set budgets for their future expenditures. Users will also be able to clearly see breakdowns of their expenditures and projected savings via graphs and charts generated by d3. Another feature of Clover is that users will be able to track and manage their stocks. They will be able to easily see the profit they make from their stocks via d3 charts and search up new stocks to add to their portfolio.

## Dependencies
* `from flask import Flask, render_template, request, session, redirect, url_for, flash`
  * requires `pip install flask`
* [`python2.7`](https://www.python.org/download/releases/2.7/)
* `import os, sqlite3`

## Launch Instructions
0. Enter your terminal and go into the directory that you want to have this program in
2. Enter this command to clone our repo
```
git clone https://github.com/JackieW001/J-HEX.git
```
3. Run your virtualenv from wherever you have it (if needed)
```
. <PATH_TO_VIRTUALENV>/bin/activate
```
4. Go into the softdev1-finalproj folder using this command
```
cd J-HEX/
```
5. Run the program
```
python app.py
```
6. Go to localhost:5000 in your web browser and enjoy the site!


## API Key Instructions

#### API_1
1. [insert steps here]

## Bugs and Issues
* [insert bugs and issues here]

## File Structure
```
data/
  |  database.db
static/
  css/
    |  home.css
  images/
    |  background.jpg
templates/
  |  home.html
utils/
  |  api.py
  |  database.py
app.py
changes.txt
design.pdf
devlog.txt
log.sh
README.md
```
