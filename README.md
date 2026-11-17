# WOPR - MK III
## a one-liner which creates a three-column notepad in your browser
  

  <img width="1920" height="1200" alt="Schermata del 2026-11-17 09-50-23" src="https://github.com/user-attachments/assets/574c1576-9f31-47ed-9c34-d0674944a205" />

### History
Who doesn't need to keep track of his thoughts, intuitions, snippets, links and more?  
For many years my memory has been overloaded with informations I couldn't just keep in mind. I started carrying with me a small Rhodia notepad and a pen, which I still do by the way; I use it as a sort of FIFO stack: I note down everything I can't handle in the immediate. Then I proceed deleting every item as soon as I've completed the task, starting from older ones. 
Sometimes, though, there are things you can't easily jot in a paper notepad. For instance, a long link, a phrase or quote, part of an article, which instead I can copy and paste on a real notepad. But this forces me to open a text editor, and paste into it, and save a file somewhere on my hard disk. Instead, WOPR is a sort of a temporary notepad which I keep open in my browser in a separate tab, and it gets saved when I exit the browser because there's a browser's feature which allows me to save windows and restore them as soon as I open the browser again. WOPR sits in my browser, and I keep in it every snippet of text I need to remember.
### Why a one-liner
Because they're beautiful! I once enjoyed coding in Perl, which is a beautiful programming language, and I was accustomed to writing snippets of code which did amazing things. So when I had to code a quick-and-dirty notepad I thought it could be fun to do that as a one-liner. A single functional line of code which fills the URL bar creating a comfortable environment.
### Features
**WOPR** MK III sports many interesting features. At first it was just a huge window with text inside of it. Then I realized that the window was really too big and dispersive, and I decided to divide it in half. The two-columns layout was born. I chose to separate tasks and sort them between the two columns so that one type of note ended up in the left-hand column and another type in the right-hand column. Modern displays, though, are pretty wide and the two-column layout was still too large. I ended up splitting the window into three parts to optimize screen usage without sacrificing readability, while also preventing the columns from becoming excessively long. The final step was adding Markdown highlighting. While I used a single color for the first two columns—intended for text and lists—to maintain readability, the Markdown interpreter in the third column (also dedicated to lists) highlights headers and other markers using different colors. 

    
The first two columns feature: 
* Markdown highlighting, with:
  * headers in bold and slightly brighter
  * list markers bright and bold as well

  
The third column features:
* Markdown highlighting, with:
  * headers in bold, three shades of blue for the three first header levels
  * bold terms in bold and off-white
  * italics terms in italics and grey
  * quotes in tan
  * list markers in magenta
  * links in yellow
  * code in green

  There's way too much for a quick temporary notepad so I found it unnecessary to further develop a more complex syntax highlighting.
  
### Usage
Open the wopr.txt file, copy its content and paste it into any browser's URL bar, then hit Enter. The tab will be transformed in your new favourite temporary notepad!
### Legacy
As you will notice, **WOPR** is mainly orange-on-black and this is a direct reference to **Plato** system, the forerunner of all our modern virtual places. Then, the name itself is a reference to the  remarkable 1983 film titled "WarGames", which all of us older folks found fascinating when we were kids, and which—even today, in the second quarter of the twenty-first century—would still be educational to show.
The placeholders that **WOPR** inserts at the top of the columns to better visualize their layout are a direct reference to the prompt that the real WOPR displayed upon login.

### License
The code is licensed under GPL 3.0
