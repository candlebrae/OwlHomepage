A custom homepage featuring a functional search bar, 12 custom buttons, and a violet color scheme by default. Designed to be changed and tweaked to your liking. Colors can be customized in the colors.cfg file.

---
To set the button links to something you'll actually use:

1. Open the homepage.html file.

2. There are a bunch of <a href="(link)"> tags. Replace the links with whatever you want the button to link to (keep the quotes though!).
	- Likewise, the button labels are inside the <p> tags. Feel free to change them!

3. Save the file.

---
Other customization help:

- If you want to replace the middle image, its dimensions are 1920 x 670px. If you choose a different name, make sure to change the filename on line 62 of the HTML file.

- If you change the button colors, make sure you also change the hover colors. Otherwise you'll be in for some color weirdness when hovering over a button. Just make it a shade or two lighter or darker than your main color and it'll look great.

- The search engine is on line 68 of the HTML file. To change it, change the link after "action=" to your search engine of choice. A few privacy-respecting options are listed starting at line 60.

---
To set this as your homepage:

1. Unzip this folder and place it somewhere that your web browser can access it and where it won't be overwritten (I put it inside of my web browser's .config folder and haven't had any issues).

2. Open the HTML file in your web browser, either through your file explorer or through the browser itself.
	-How to open your filesystem in the web browser:
		- On Firefox: In the URL bar, type in file:/// 
			- If that doesn't work, try file://///
			- If you're on Windows and the above isn't working, try C: , file:///c:/ , or file://C:/
		- On Chrome: Hit Control + 0 (zero) on your keyboard or follow the Firefox directions.
		- On Edge: There's no way to do this without compromising security. If you REALLY want to do it:
			- Open up your Internet options and click on the Security tab.
			- Choose local intranet and click on sites.
			- Uncheck the “include all local (intranet) sites not listed in other zones” box.
			- Uncheck the “Include all sites that bypass the proxy server" box.
		- Other browsers: Follow the directions for Firefox.
		
	- Even if you know the location and think you can type it in correctly, open the file before setting it as your homepage to make sure you have it right. An invalid homepage can crash web browsers in a way that's harder to fix (source: I made the mistake of mistyping the file location and my browser refused to start up until I found its config files and manually fixed it). It's best to make sure you have it right.

3. Copy the contents of the url bar and set that as your homepage through your normal settings menu (or config files, if you prefer that).

---
Licensed under GPL 3.0 or later.
