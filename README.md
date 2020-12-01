@@@@@@@@@@@@@@@@
Initial Idea:
@@@@@@@@@@@@@@@@
I will work on developing an idea I came up with for the Innovation Methods assignment as a Solution to achieve food security and improved nutrition and sustainable agriculture.

My solution is not a technical one, it is an approach that requires society dare take a look at current structures in society and how they can be re-organised in order for us to all work together with the goal of improving life on this planet.

In the Innovation Methods Assignment I came up with a solution that went as following:

"Sentence non-violent offenders to serve their time working on re-forestation projects as an alternative to wasting their time in prison."

I want to imagine this solution in the form of an organization actively working to achieve this goal in countries all over the world.
And as such the main purpose of the website is not to present a brilliant, and perhaps hard-to-explain, technical solution to the average person.

The goal I want to achieve when visitors access this website is that they get this idea presented in a well thought out and precisely worded manner which explains in as simple terms as possible what the obvious benefits of this approach will be. I aim to make the site as light on text as possible, but I realise that this might be a hard challenge as I am selling a "philosphy" more than a product and in this regard the visitor might a thorough explanation of what inspired this idea and why adopting it might be an essential step towards achieving this UN Sustainable Development Goals.

@@@@@@@@@@@@@@@@
Concept:
@@@@@@@@@@@@@@@@
When a person is sentenced to prison, you can look at it as he owes society a portion of his time. However, todays prison system (or industry) is poorly suited to make sure that the time someone spends in jail is actually invested in a manner that is beneficial to the society in general.

Just keeping someone locked in a cell does the population of a nation no real service, unless that person poses an actual threat to their surroundings.

However, in many cases we know that offenders that have no violent history, and is sentenced to prison for a non-violent offence, will spend the entirety of their sentence behind prison walls - when there is an entire planet outside these walls in desperate need of someone able to dedicate a significant portion of their time to aid the environment and help fortify it against threats like climate change, pollution, erotion, deforestation and so on.


@@@@@@@@@@@@@@@@@@@@@@@@
Idea/Brainstorming Phase:
@@@@@@@@@@@@@@@@@@@@@@@@
Accessibility Features:
Always text alternative to images.
Text-to speech? (Amazon Polly)
Focus on contrast, font size, legibility. (WCAG Guidelines 1.4.3).
Remember Text on Menu Icons!

@@@@@@@@@@@@@@@@
Implementation:
@@@@@@@@@@@@@@@@
I wasted a lot of time on getting to know and learn how to implement Amazon Polly, for adding a text-to-speech feature on the site, only to realize later that GitHub Pages does NOT support Amazon Polly - or rather, it does not support Python which is a Requirement for Amazon Polly.

Note to future-self: always check server environment *before* working on any fancy features which later turns out to be impossible to implement.

Had some trouble brainstorming how I wanted the layout for the site to be and I feel I ended up with something that was less polished than I had hoped.
First and foremost the Nav-bar is not very "fancy" - Initially I had planned for a "drop-down" menu for the sub sites but I found that working alone put too much restrictions on the content I would be able to produce, and a drop down menu with dead links would be weird so I dropped that approach.

Although I did not plan to spend much time on making the site "look cool" - I did actually fall into that trap once I got the idea that I wanted some sort of visual feature of a chain breaking. I had intended to work something out with the help of parallax effects, but I found that I could use the FlexGrid instead. However it does not look as cool as I had hoped.

I went on to use parallax effects on the "About" a.k.a. "Our Philosophy" page. I hope this did not collide with the criteria that the website should be cohesive in style and presentation, considering that I only used parallax effects on the About page. This was the only Page I found it to be suitable as a little "breather" in between the rather large portions of text - which I found hard to avoid considering the solution I chose to present.

In retrospect I should perhaps have chosen another solution/product/feature/service to present as the one I'm delivering here leans heavily on text. This was also why I wanted to implement Amazon Polly, but alas .. I fell down that rabbit hole and got stuck for a while before realising that I would not be able to use Python on Github. So I'm left with a lot of text with no added accessibility function to compensate - which I realise would be a huge plus.

@@@@@@@@@@@@@@@@
Code Review:
@@@@@@@@@@@@@@@@
I Guess this code could benefit from more commenting. I see that my CSS file ended up a bit messy (will minify if I get the time) - due to the fact that I borrowed fixes from earlier assignments into this file. I have not copied any code from any other source than myself, with one exception : The Parallax Effect on the About Page is implemented exactly as found on this page:

https://www.w3schools.com/howto/howto_css_parallax.asp

Considering that there are few lines of code and that I did see the point in renaming the classes just to make it look like my own I thought it would be best to mention this here.

I am also wondering if I did something which is poor CSS practice when I used both Flex- and Grid view simultaneously on the main page? I dont really why it ended up this way and if I'd had the time I'd sort it out but I'm short on time as I'm writing this so I'll just have to leave it.


@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
Conclusion
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

I'm not very impressed with the work I'm delivering here now, I just have to admit it. I dont think the layout is very pretty. The navbar is directly ugly. And there are features I'd wanted to implement that I did not find the time to do due to wasting time on not getting Amazon Polly up and running and also trying to work out an unnecessary Parallax animation for the chain on the main page.

I should have focused my time better because I wanted to implement a "dark mode" for the website to make it easier on the eyes in poor lighting, also I wanted to add a feature to increase / decrease font sizes and maybe even font types but as you can see those features are not present.

Personally I give myself 50% score on the finished product. I had a lot of great ideas initially but most of them are absent.




Media Credits:
Image: https://www.pngegg.com/en/png-bbyjq/download
Parallax1: https://unsplash.com/photos/NXBhUscR_gg
Parallax2: https://unsplash.com/photos/JUKqr-nhjzw
Parallax3:https://unsplash.com/photos/XN_CrZWxGDM
