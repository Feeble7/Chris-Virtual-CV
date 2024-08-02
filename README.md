# Chris-Virtual-CV

Virtual CV

For this project on the HTML side I have made use of a bootstrap stylesheet to improve the layout of my cv - structuring the CV in rows and columns IE --> 
<div class="Row">
    <div class="col">
    
    </div>
</div>
Bootstrap divides one container into a total of 12 columns across, when lookings at the code above, see index.html code to see how it was implemented it.

Along with that I have also added code for a side navigation bar that stays fixed as one scrolls through the CV. 

The website is fully compatible with major devices and web browsers and resizes nicely whilst still keeping the navbar on the left side of the page.

To help with navigating the website(Especially for mobile users) I have added a Content section that has links that jump to parts of the Virtual CV if one clicks on it.
I.E on the side navigation bar, Link :  About Me --> on click. jumps to the About me section in the main class / right side of the CV. This works with every section in my page

For the Javascript side, I have added a onhover function that changes my photo, to that of another photo. If cursor hovers over the photo it will change to another photo.
For mobile users, the onhover works differently, if one touches the image then it will change to a different image. To change back to original image tap anywhere outside of the image border --> tap anywhere inside the page - don't tap the image itself again, then it will remain on the changed image.

For the CSS I have added a lot of code to help better structure the Page, aswell as hover functions for links in the navbar in which the link will change color if one hovers over it.
That and I have included styles for the navbar and have changed the fonts to Times New Roman to give the main class page a better look.

In the navbar i have also put in links to revelant pages, such as my LinkedIn, a pdf of my Resume/CV, my github repository as well as a mailto feature :
    <span><i class="fa fa-envelope" aria-hidden="true"></i></span>
    <span><b><a href="mailto:kellerman.chri@gmail.com">Gmail</a><b></span>


In the Code above is also an example of how the Font Awesome stylsheet was implemented to give icons to each of the neccesary links/elements in my navigation bar.
