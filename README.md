# Part 1 - Before the Project

This project appears to be a recreation of the Google homepage, given the title of the project folder we were told to create. I will do my best to complete the project as well as it can be completed, but will use the experience to learn from my mistakes. I will reflect upon whatever mistakes I made and discuss what I learned from them after completing this project.

# Part 2 - During the Project

I had a really hard time getting the favicon to work for some reason. Eventually, after several changes to the file type and extension, as well as the html code and pathway, I went back to the orginial way I had it just to see, and it magically worked. I'm almost 100% positive I had already done it that way (as I had done in previous sites), but somehow it just worked even though it hadn't been working before.

The biggest challenge has been getting the page to look as identical to the actual Google homepage as possible. I'm trying hard to figure out how to get the searchbar to have the same box-shadow effect without affecting the nearby elements. Specifically, on hover, the box shadow is looking correct, but is shifting upward strangely, which pulls the search buttons below it up as well.

I've finalized the general layout, and figured out a bit of a "hacky" way to get around the .searchbox:hover issue. I used "box-sizing: border-box:", but that shrunk the element before hover, and caused it to grow on hover. So I applied a "transform: scale(0.996)" property on hover (that number was achieved after several tries while tinkering around with it) and it now applies the box shadow correctly (at least visually correctly; I'm sure there are better ways to do this). The box shadow now looks about as similar to Google's as I think I'd ever be able to get it.

# Part 3 - After the Project

I definitely learned a lot while doing this project. It seemed so simple at first, but as I dug in, I quickly realized it wasn't quite as easy as I expected. I thought making a basic layout like that would be simple, and I guess now that I've done it, it would be simpler now. 

My biggest struggles were getting the header and footer to split, with some links on the left and some on the right. Learning to appropriately nest elements and correctly use Flexbox to achieve an identical look to Google's took some time, but ended up not being so difficult. I think I tried a bit *too* hard to perfect it, but I'm happy I did. I'm quite proud of the finished product, even though it's not quite 100% identical. But how could it be? Of course, Google has found a way to take such a beautifully simple page design and perfect it, with each element being perfectly placed. In the future, I plan to spend more time on responsive design so the page will work on any device or browser.

Things I now know I still don't know:

- The *actual* correct way to nest elements and use Flexbox. I'm better at it now, and have a more general understanding of it than I did before, but I can tell from using the DevTools on Google's actual page that I still have a lot to learn.
- How to get a text alert to appear on hover over an element, like Google has over the microphone within the searchbar. I'm sure this is not terribly difficult, so I may look into adding that at some point soon when I have the time.
    - Edit: I ended up deciding to go ahead and look this up. I found a helpful guide and it took about 10 minutes!
- I already knew I didn't know much about browser compatibility, but I think while searching for various answers during this project, I came across lots of CSS properties that, in the tutorial, were noted to only work with certain browsers. That's scary, and I know I'll need to learn more about how to deal with that.