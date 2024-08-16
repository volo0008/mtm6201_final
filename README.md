# mtm6201_final

1. I started with the structure first.
2. It was challenging to work with Bootstrap, because it has limits. I used Layout-->Grid, Components-->(Navbar, Buttons, Carousel), Forms-->Form control. I found it inconvenient to use Grid in some places. Some rules that are set by default influenced my final design. I had to deviate from my mockups. But in some places, the result was unacceptable and I had to change settings manually. There some examples which I find as limitations (1-There are only 12 template columns available per row, 2-The margin size for Grid, ranging from 0 to 5, where each size has a corresponding value in pixels).
It can be challenging to take a target on an element inside Bootstrap's Grid. For example, I had to use something like this 
(.grid-border .container.middle-grid .row .col-7 .p-5 p {
    margin-top: 5.3rem;
  })
  Pseudo-class ":last-child" was handy and helped me to manipulate some element. Example: ".middle-grid span:last-child {
  font-size: 1.7rem;
  font-weight: bold;
}"

Pseudo-elements were also used. In particular "::before" was used to follow my original design and replace standard bullet points by squares of appropriate size. 
Example: ".missions li::before {
  content: "\25A1"; /* Unicode for empty square */
  font-size: 1.3rem; /* Size of the square */
  ...}"

3. In case of Questions part(accordion), it was difficult to make it align with the website container, it jumped out.
4. The thin rectangular line(with tools I use) was difficult to stretch to the whole website 
and place it exactly after the main welcome content, so now it has constraints and aligns with the container.
5. I still have problems with picture tag. I applied it only once to my photo, in About page.
6. As my website has designs for desktop, tablet and mobile versions, I have to use media queries. Some of them were challenging. For instance, to depict Layout(Grid) for different sizes correctly I had to copy HTML component several times and hide it in CSS. Skip-links could stop working. To solve this problem, I had to create several skip-links for different page sizes and apply media queries to them as well.


# Images, resources
1. Uxpic, uxpic2 JPG were taken from pexels.com.
2. All other images, logos, design elements were made by me.
3. In total I used IMDAC, w3schools, bootstrap library and animate.style library, Youtube, mozilla dev.  I found "animate.css" easy to work with. The official webpage is clear and friendly. All affects are shown immediately on the page.

# Result
1. It is an meh result, I won't use this website to promote myself. 
I'd rather use a ready solution from webflow.









