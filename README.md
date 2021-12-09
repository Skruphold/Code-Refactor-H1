# Code-Refactor-H1
I started with the html and changed the title so it doesnt just say website. Then I targeted the div tags and made them what I thought would be the apporiate semantic tags. Some where extra I just deleted those,
I used header, nav, main, section, article, aside, footer and made an h4 and a span catagory so I could target them in css.
I also added detailed alt"" comments on all of the pictures. 
I put the articles in their parent which was section and aside which are children of main.
On css I started with a global color because I noticed all text was white. This created a problem with the footer which I fixed later. Then removed all color: white from the texts.
I started with targeting all the different semantic tags to reconnect the what was broken when getting rid of divs.
I reduced the size by combining some semantic tags together
I made a h4 tag so it could be targeted to be made black to override the global white tag and combined it with the footer tag.
I made a span tag seperate because there is another span tag in the header that cant be 20px. It broke when I had it like this, but for some reason works with the color black in a seperate span tag. I needed it the color black to overide the global white. 
