# Project-4.1
My web optimization project


To optimize the site I started with index.html, and I minified all the pictures and CSS.
I synced all of the javascript tags, which is an obvious catch.

I noticed that the font was being called from a link from google versus actual script.  Being familiar with Google Fonts, I was able to replace the link with the script for better performance. 

Getting the frames per second increased on main.js came with a few challenges for me.  I was able to reduce the amount of pizzas on the screen, and reduced it down to 35, it was suggested to do 40, but I did not see an issue with the value inputed. I felt such a busy part of the site could be modified in some way. 

The most challenging part for me was modifying the loops in the code.  As I have learned with code, when editing a site its all about trial and error.  There was a moment when nothing was moving on the screen for me at all. I remained persistent and figured it out.  

Through some online research I read to replace "queryselectorall" to "getelementbyclass" to increase the speed of the page.  Honestly, I had no idea if it would work or not, I just put it in and hoped for the best.   Lucky forme it worked out VERY well for me. I hope you guys enjoy ths newly optimized site!

By playing with the site I was able to achieve the desired speed of the page. I used: https://developers.google.com/speed/pagespeed/insights/ to monitor the page's FPS.

Getting started

Part 1: Optimize PageSpeed Insights score for index.html

Some useful tips to help you get started:

Check out the repository
To inspect the site on your phone, you can run a local server

$> cd /path/to/your-project-folder
$> python -m SimpleHTTPServer 8080
Open a browser and visit localhost:8080

Download and install ngrok to make your local server accessible remotely.

$> cd /path/to/your-project-folder
$> ngrok 8080
Copy the public URL ngrok gives you and try running it through PageSpeed Insights! Optional: More on integrating ngrok, Grunt and PageSpeed.

Profile, optimize, measure... and then lather, rinse, and repeat. Good luck!

Part 2: Optimize Frames per Second in pizza.html

To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. You will find instructive comments in main.js.

You might find the FPS Counter/HUD Display useful in Chrome developer tools described here: Chrome Dev Tools tips-and-tricks.

Optimization Tips and Tricks

Optimizing Performance
Analyzing the Critical Rendering Path
Optimizing the Critical Rendering Path
Avoiding Rendering Blocking CSS
Optimizing JavaScript
Measuring with Navigation Timing. We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
The fewer the downloads, the better
Reduce the size of text
Optimize images
HTTP caching
Customization with Bootstrap

The portfolio was built on Twitter's Bootstrap framework. All custom styles are in dist/css/portfolio.css in the portfolio repo.

Bootstrap's CSS Classes
Bootstrap's Components
Sample Portfolios

Feeling uninspired by the portfolio? Here's a list of cool portfolios I found after a few minutes of Googling.

A great discussion about portfolios on reddit
http://ianlunn.co.uk/
http://www.adhamdannaway.com/portfolio
http://www.timboelaars.nl/
http://futoryan.prosite.com/
http://playonpixels.prosite.com/21591/projects
http://colintrenter.prosite.com/
http://calebmorris.prosite.com/
http://www.cullywright.com/
http://yourjustlucky.com/
http://nicoledominguez.com/portfolio/
http://www.roxannecook.com/
http://www.84colors.com/portfolio.html
