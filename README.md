# CloudHostnig
Video Demo: https://youtu.be/9Rrd4GU0mf8

NimCloud is a Cloud Hosting Website, You Can Deploy Your Website Less Then 60 Seconds With Just $9 Per Month.
This Website Is Created Whit HTML(HyperText Markup Language), And CSS(Cascading Style Sheet) And JavaScript To Build Dynamic Website And Better Experience. I Not Use Wordpress Or Any Type Of Css Framework’s, It’s Full Responsive  And It Look’s Clean And Good On Any Type Of Standard Device. Importantly Is Easy To Use And The Ui Design Is Stand’s For Natural User Interface. At The Top Of The Website We Can See Navigation Bar And Logo, Nav Bar Is Created Whit Flex Box . And After That We Have Hero Section, All The  Section In Website Have Same Layouts, Grid Layout With One Row And 2 Column. I Add All The Components In Separate  Folder For Easy To Use For Everyone. We Have Object Oriented Css And In The Second Rule Of Object Oriented Css We Need To Separate Structure From Skin, That Principle  
Gave Us A Better Access For Each Different Element And Less Code, DRY Or Don’t Repeat Yourself.
Is Mobile First Cloud Hosting Website, This Is Title. We Have A  Animated Section's. For This Animation's I Use Animated Scroll Libery That Came's From JavaScript.
All The Componet's Is Build And Then I Try To Gave Them A Style. To Have Faster Website, I Sprite All Icon's To Spend Less Time When We Waiting To Loading Website.
I Use Inter Font In 500, 600 And 700 weights.
For The Pesron Photo I Use Unsplash.
And Set All The COlor's In The Root Of The Our Css File.
All The Element's Sperated From Structure And Skin.
I Use BEM Convation, In All Of The Elemnt's Of The Website But Mostly Is Use On Card Section.
In JavaScript File We Have Function's And I Use document To Call All The Element's Whit Expanded Class, After That We Call Function Whit This Command, All The Expanded Element, When We Toggle, Need To Collaps.
All The Button's Have Hover Effect, The Button's Separated In Four Group's, Primary Have Blue Color, Secondary With LigthBlue Color, Accent Color It's Combine Of The Red And Orange Color, And Outline Button Have Dark Blue And Border Have Same Color.
This Website Deployed By Netlify. That Mean's The Website Is Online And Every Body Can See. And Every Body Can Use.
I Want To Note That, I Build This Website Throghuot A Course That I Enrolled On 4 Month's Ago, But I Try To Make It Again To Send For Cs50 For Submition.
As front-end developer, a popular request you might get from your clients is to implement stunning animation effects on page scroll. There are many libraries to make this task easier for us. AOS, also called Animate on Scroll, is one such library and it does exactly what its name suggests: it lets you apply different kinds of animations to elements as they scroll into view.
Animations are used to attract people’s attention and add interactivity to your web application rather than just a static page. With animations, users tend to engage more with the features of your application. One of the best animations to add to your webpage is the on-scroll animation. An on-scroll animation is a form of Scrollytelling, which means telling a story or displaying content while scrolling.
On-scroll animation can be complicated to implement on a website without the use of certain scroll animation libraries. These libraries provide a simple interface for creating different interactions on the scroll and improving the user experience. With the Animate on scroll(AOS) library, you can add animations smoothly, and it's easy to configure.
Animate On Scroll Library (AOS) is a library developed by Michał Sajnóg. The library's main goal is to detect the position of elements and then add appropriate classes for animation when they appear in the viewport.
Animate On Scroll Library provides an ease to let you apply different kinds of animations to elements as they scroll into view. The library was built with all types of users in mind to make it easy to configure for accessibility.
AOS is an open-source library with over 16k+ stars on Github
With the use of this AOS attribute, you can control the timing function which specifies the speed curve of the animation, it enables you to control and vary the acceleration of an animation that is it defines where the animation speeds up and slows down over the specified duration. The attribute uses the same values for your CSS animations such as linear, ease, ease-in, ease-out, ease-in-out.
This attribute gives you control over the position in which the animation starts. By default, AOS sets the start position as soon as its top part reaches the bottom part of the window. The possible values to use for this attribute are top-bottom, top-center, top-top, center-bottom, center-center.
Animations in the AOS library by default are always replayed each time it's scrolled into view or out of view. With this attribute, you can set the value to false in other to animate the element only once.
Another alternative is to set your preferred values needed globally for all the elements you want to animate. This can be done by passing them as an object to the init() .
With the updated changes, our landing page’s animations will only start animating when we scroll into the view of the section.
