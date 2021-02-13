# Class 01

## Responsive Web Design


*In this page I will summarize what I have learned in this read.*





![HTML](https://th.bing.com/th/id/OIP.FV3cr6w1twbhfIHghAJicwHaEo?pid=ImgDet&rs=1)

### Responsive Overview:

The responsive web design term itself was coined, and largely developed, by **Ethan Marcotte.** 

## Responsive vs. Adaptive vs. Mobile:

![HTML](http://www.swiftelearningservices.com/wp-content/uploads/2017/01/Responsive-Vs-Adaptive.png)

![HTML](https://traininginstituteinchandigarhsector34a.files.wordpress.com/2019/01/d3e96fc8-2781-443d-9700-218795ae3b39.png)

1. Responsive generally means to react quickly and positively to any change.
2. adaptive means to be easily modified for a new purpose or situation, such as change

***Currently the most popular technique lies within responsive web design, favoring design that dynamically adapts to different browser and device viewports***






### Responsive web design is broken down into

- flexible layouts

-media queries

-flexible media

### flexible layouts

*do not advocate the use of fixed measurement units, such as pixels or inches.*

    target ÷ context = result
    
   - The result is the relative width of the target element.
   
   



1. Flexible Grid

2. Fixed Grid

### media queries:

1.  @media rule inside of an existing style sheet

2. importing a new style sheet using the @import rule

3.linking to a separate style sheet from within the HTML document


**Logical Operators in Media Queries**

help build powerful expressions.

- and 

-not

-only

     @media all and (min-width: 800px) and (max-width: 1024px) {...}
    @media not screen and (color) {...}
    
        @media only screen and (orientation: portrait) {...}





## What is “Float”?

The float property specifies how an element should float.

*none* 

The element does not float, (will be displayed just where it occurs in the text). This is default	


*left*

The element floats to the left of its container	


*right*

The element floats the right of its container	

*initial*

Sets this property to its default value. Read about initial	

*inhert*

Inherits this property from its parent element. Read about inherit	

**Floats are also helpful for layout in smaller instances. **


![HTML](https://th.bing.com/th/id/R1b4b2e9b237e8cf9723499fcdd2ea9f2?rik=mr87ONKWqWDMbQ&riu=http%3a%2f%2fwww.dotnet-stuff.com%2fexamples%2fcss-floating-property.jpg&ehk=blqk%2bVni2GYp3afINCQiQMmOE%2bFve%2b%2b2SGG6qoxmdnQ%3d&risl=&pid=ImgRaw)


### Clearing the Float

An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float. Again an illustration probably does more good than words do.


![HTML](https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/unclearedfooter.png?resize=540%2C195)






