# 100 Days of Code Log
---
## Day 6: 6/18/18

### Today's Progress:
Created this repo, fixed CSS for the navbar

### Reflection:
I knew I wanted to use Flexbox to format everything for this site instead of
using Bootstrap. Thankfully after a bit of review of Flexbox from CreativeBloq
I was able to get the nav bar to look the way I want.

The colors might be the colors I want though.

I also learned that `<ul>` have some default padding, which confused me for a
while because I was seeing this space that I couldn't account for when I added a
border to everything.

### Next Step:
I need to add some media queries to make the nar bar responsive. I've decided on
`600px`, `900px`, and `1200px` as my breakpoints after reading an article on 
Medium.


## Day 16: 06/28/18

### Today's Progress:
* Moved off of Codepen
* Set up local deployment with Jekyll
* Figured out how to override the default layout and theming
* Picked a new color scheme, but it might not stick

### Reflection:
My decision to use Flexbox instead of Bootstrap is slowly me down significantly
I believe. The main issue is that in Bootstrap I can quickly make things fluid
and resize as needed, but I'm having trouble figuring that out with Flexbox.

Having read `Responsive Web Design` by Ethan Marcotte, I feel the need to make
a mockup of the site first, measure everything in pixels, and proceed from
there. I think that would greatly help with my palette choice as well. 

I also went through the freeCodeCamp Sass curriculum today. I thought it would
give me enough knowledge to deal with the Sass file in the Jekyll theme; 
however, for that file, I just needed to create another file of a similar name
and I could fill it however I want.

### Next Step:
Either figure out how to make the navbar fixed at the top- the example I looked 
up today did not do it for me. Or work on making the entire site responsive and
test it with `div`'s as placeholders.


## Day 17: 06/29/18

### Today's Progress:
* Switched to a mobile-first approach
* Got to a good (working) draft of the mobile site; for a 320px wide viewport

### Reflection:
Today was quite a bit of confusion that turned into a victory as a result of
a breakthrough in understanding. 

An issue I was having was trying to reconcile having the fixed navbar and make
that work with the CSS grid somehow. I definitely lacked a clear understanding 
of how to use the CSS grid; however, after reading `[1]`, things made enough 
sense for me to ask my own questions and google what I wanted to do.

As evidenced by the notes I take on my process of designing this site, I jump
between designing the Desktop view and the Mobile view too often. While it is
helpful for me to know what I want the end product to look like, I was pretty
lost as far as approaching the implementation. Do I write the larger site first
and then use media queries to force smaller versions of it to look good? Do I
start small and go up from there? Is there a right way? Is there a wrong way?

The breakthrough for this came from watching another developer work. Namely, I
was inspired by `[2]`. I don't remember if Brad (TraversyMedia) answered any of
the questions I had. While I was watching the video however, I kept thinking,
"Oh, I know how to do that" and "That makes sense". So I gained the 
self-confidence that no matter what approach I take in implementing this site,
I can do it.

It's not the prettiest thing right now. I'll fix the styling for sure, but this
has been a great learning day!


### References
1. [How To Efficiently Master The CSS Grid In A Jiffy](https://medium.com/flexbox-and-grids/how-to-efficiently-master-the-css-grid-in-a-jiffy-585d0c213577)
2. [Grid CSS Responsive Website Layout - "Mobile First" Design](https://www.youtube.com/watch?v=M3qBpPw77qo)


## Day 23: 07/08/18

### Today's Progress:
* Updated the video to span the viewport width
* Revamped the style of the whole page
* Added media queries for scaling up to a iPad resolution

## Day 24: 07/09/18

### Today's Progress:
* Finalized desktop view
* Added a Grid in one section
* Removed unused CSs
* Removed most `px` in favor of `em`

### Reflection:
I forgot to update this log yesterday, so today's entry is a double reflection.

The project is more or less done! I remember waking up yesterday and thinking I
want to sit down for a bit and just work on this page. So I did, but then when 
I checked the time, about 5 hours had passed and I had everything except the
desktop view done. It felt like everything just clicked yesterday, I didn't
have to google too many things. I was just writing the CSS that I wanted and
things were happening like they were in my head. Having done this for so long,
I am well aware that these good feelings are rare with coding. It's not
discouraging, more motivating actually. It gives me something to strive for.

Today, although I knew there wasn't too much more to do, I put off working on
the project all day. I got a lot of other things done, but I was definitely
choosing to avoid this project. Perhaps it was because I didn't know if it
would be like yesterday. Regardless, I reminded myself that the point is to get
something out that is "good enough", not perfect. With that in mind and the
Chrome Dev Tools in hand, I played with the resolution until I was satisfied
that every pixel was in its place. 

I also uploaded this project on the feedback forums. Hopefully someone gives me
some feedback, but in the mean time, I'm starting the next project.

---
Template:

## Day NUM: MM/DD/YY

### Today's Progress:

### Reflection:
