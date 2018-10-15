# PixiProj
This is a Project Created in PIXIJS, just to demonstrate my understanding of the technologies we plan on using for our Game for CSCE 490. 

So the steps to running my code is to first get all of the files. Which are given above. The purpose of this project was for me to get a practice of spawning in characters into the map, along with differnet items. This includes things like position, altering size so that they fit the screen properly. Also having characteristics based on the canvas/map. 

1) So first you need to collect all the files and put them into one directory. For me mine was in the main directory called Farmer. You can name the directory whatever you want, I just choose to name mine "Farmer for some weird reason." You should have a one folders called "images" . Along with the file "index.html", "package-local.json", "package.json", "pixi.js", and "styles.css". The "images" directory should have 3 files called "knight.png", "Knightlife.json", and "Knightlife.png". 

When you have all these files. then you move to step 2.

The things I used for this project is Nodejs and PIXIJS. Node was used primarily because I had to host my own local server in order to test the html files and make sure everything was working properly. 

2) So all you need to do to run the code is to host your own Web Server. Using Node Js and the Http Server Module that comes with it. It sounds intimidating but all you have to do is to open terminal, depending on what operating system you are using. 

If you do not have Node Js already installed on your computer. You can install it from this site. https://nodejs.org/en/ 
The installation process is pretty simple, and doesn't take long. Once you have it downloaded and install, move to step 3. 

3) So since I was using terminal because I'm on a Mac, I had to cd to the main directory I was using for this project. Which is the "Farmer" directory. Which you have access to above. 

Then I ran this command in Terminal. 

"npm init"
Run this while you are in the directory you wish to host the server in. So I ran this command while I was cd into my Farmer directory. Using this command will ceate "package.json" which you will need to run the server later. It will bring up some statements that you just press the enter key to get through. It has no real importance. 

"http-server" is a simple light weight http server package for Node.js.

4) Step 4, while in that same directory you need to run this next command in terminal.  
"npm install http-server" 

You will get a few warnings when it goes through, but ignore them as they are not important either. Now you should have a folder called "node_modules" inside of your main directory or in my case. My "Farmer" directory. 

5) Last step is you have to run this line next in terminal, alter the "Farmer" in this line based off your name for the main directory. You need to have this to the exact, as it is necessary as the thing used to run the server is located in the http-server directory.

"/Users/kendrickdubose/Desktop/Farmer/node_modules/http-server/bin/http-server" 

So for example if your main directory was name "Character" it would be.
"/Users/kendrickdubose/Desktop/Character/node_modules/http-server/bin/http-server" 


When this code is ran, you will recieve a list of possible local servers that you can copy and paste into your browser.To use the file. Use the lowest one.

For example: 
Starting up http-server, serving ./
Available on:
  http://127.0.0.1:8080
  http://10.183.229.189:8080
Hit CTRL-C to stop the server

You would copy "http://10.183.229.189:8080" and paste it into search bar on your browser. Which will open the file in the browser of your choose and there you go. Complete, you can now view the file off your local brower. In order to stop hosting just go to your terminal and do CTRL+C. 

You should have this show on your browser.
https://i.imgur.com/rl5i87e.png
