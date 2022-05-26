# Mane Barbershop
This is a barbershop website that utilizes responsive web-design to provide better ux on mobile platforms.

**Link to project:** https://ld-mane.netlify.app

![alt tag](https://i.imgur.com/N495YW8.png)

## How It's Made:

**Tech used:** HTML, CSS

The focus of this project was to use best practices when building a website - seperation of conerns, responsive web design, organized directory architecture, - alongside giving me experience writing dry/drier code and style modularity i.e. layering styles on elements by using classes, to keep specificity weight low, letting me add new styles easily.

## Optimizations

In terms of optimization, I could have cached my assests such as using a .htaccess file. I could have compressed my images to make the website load faster, 
refractored my css - look for repeating styles that could be made into a single class or use comma seperation (,) to add on selectors to a common rule, and also have used "Lazy Loading" to defer loading resources until they're needed.

## Lessons Learned:

A problem a ran into was that the height of my containers were being displayed oddly on mobile viewports, because I was using absolute units. Using the "vh" unit beautifully fixed this problem and allowed my containers to resize horizontally. I learned to think about the height of my containers and not just the width, when creating a responsive layout. 

I also learned how powerful the "position" property can be when set to "relative", "absolute", or "fixed" in conjuction with the "top", "right", "bottom" or "left" properties. Flexbox is extremely useful in positioning content, however elements may need finer adjustments that flexbox (or even margin and padding) doesn't handle well. 
