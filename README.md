# The Monkees Website

### Who is this website for?

The monkees are a 1960’s rock band who have recently begun celebrating their 50 year anniversary. 
They are world renowned performers who have vast experience of performing at live events throughout 
the globe and have built up huge legions of fans throughout their time at the top.

### What needs does it fulfill?

This website has been created to help publicise the band further and to help showcase their music. 
Its primary target is current and potential fans of “The Monkees” and is a place where they can 
hear and see all of their greatest memories. 

Some of its key features include:

*	Users can listen to the bands current greatest hits and new material will be made available when it is released.
*	Music videos can be viewed.
*	Links are available to purchase past albums.
*	All the bands latest news is available.
*	Photos of the band throughout their 50 years.
*	Information on all band members.
*	Details of all up-coming events and links to purchase tickets.
*	Users can sign up to The Monkees newsletter.
*	Fast access to official Facebook, Twitter and YouTube pages are easily accessible.
*	The Monkees can be contacted about booking for future events via the Event Booking page.
*	The website is responsive and can be easily accessed and viewed on any device i.e. mobile, tablet or desktop.

### Where can the website be viewed?

This website is hosted by GitHub pages and can be viewed at: 
[https://shanecoen.github.io/the-monkees-project/index.html](https://shanecoen.github.io/the-monkees-project/index.html)

## The Website:

![responsive website image](assets/images/readme-the-monkees-responsive.png)


### Responsively Designed:

This website has been designed Mobile first as priority and huge importance has put into this area to ensure that
it functions responsivelly on all devices be it mobile, tablet and desktop screen sizes.

It was designed using the 5 principles of UX Design (strategy, scope, structure, skeleton and surface) in order to develop
a website that fully met the users needs.

The bootstrap framework was used extensivelly to give the website a highly responsive layout.

The website was tested at every single stage to ensure that it responded correctly to every device type. Media Queries
were used where required to ensure that every aspect responded as desired with regard to image size, layout, positioning etc.

### UX Design

It was designed using the 5 principles of UX Design (strategy, scope, structure, skeleton and surface) in order to develop
a website that fully met the users needs.

### Technologies Used:

* Bootstrap 4.0 (note: all features of the Bootstrap framework that were utilisied throughtout this project were modified with my
own styles in order to meet my requirements).
* HTML5
* CSS3

### Functionality:

#### Common To All Pages:

* Navbar

Boostrap was used to create the Navbar that is used and is common to all pages in this website. It responds to all 
screen sizes and produces a collapsible navbar menu on smaller mobile and tablet screen sizes. The image below 
show the navbar in tablet screen size with the menu collapsed and the collpased menu open.

![responsive navbar image](assets/images/readme-navbar.png)

* Jumbotron

Each page makes use of the Bootstrap Jumbotron feature with each containing a background image and logo.

* Footer

The footer is also common to all pages. It gives quick access to The Monkees social media pages i.e. Facebook, Twitter and YouTube. It also
allows users to sign up to the newsletter which gives unique access to all The Monkees latest news and info.

#### Homepage (index.html):

* Picture Slider

The homepage displays a picture slider feature. Its makes use of the Bootstrap Caraosel and is placed behind a picture frame image which is used
to help display famous memories of The Monkees. The images slide automitically and no navigation controls are present. 

![homepage picture frame slider](assets/images/readme-picture-frame.png)

* News Reel

The Bootstrap Carousel was again used for this feature but it was edited and was transformed into a news reel showing all the latest
news. These news reel items feature Headings, images and text and a video and audio file. The user can naviagte between each item using the
next and previous icons, they also change automitically after 10 seconds or will pause when the user hovers over them.

![homepage news reel slider](assets/images/readme-news-reel.png)

* Up-Coming Events

For this section the Bootstrap "Card" feature was utilised. Each up-coming event features an image along with date and a venue. Each date
also comes with a link to purchase individual event tickets.

![up-coming events section image](assets/images/readme-upcoming-events.png)

#### The Band (band.html):

* Video files

There are two video files displayed in this page (music video and The Monkees TV episode). Each is embedded from YouTube using Bootstrap's
responsive <iframe> feature. Bootstrap comes with customisbale aspect ratios to ensure the embedded video file is responsive
to the device type being used.

* Image Slider

This page again makes use of Bootstrap carousel feature to allows the user to naviagte through a number of images of the band. Navigation is 
allowed via the use of the next and previous icons (images will also change automitically).

* Meet The Monkees

This feature uses the Boostrap card component and the collapsible accordian (modified using my own styles).  Each collapsible card is used to feature one individual
member of the band (includes four in total) and features the members name and an image. Once the card is clicked it opens to reveal information
and another image of the band member. When one card is opened it automitically closes any previoud card that had been opened (image below shows
card unopened (left) and opened (right).

![meet the monkees section image](assets/images/readme-meet-the-monkees-two.png)

#### The Music (music.html):

* Audio And Video Files

This page allows the user to listen to some of The Monkees greatest hits via Audio Files. The files are laid out using Bootstraps list group and
each file comes wth controls to play, pause, download (depending on browser) and adjust sound. A link is included to purchase the album that
these audio files come from.

The three music video files included are similar to the band.html and use Bootstraps responsive <iframe> embedded videos.

![music audio files image](assets/images/readme-music-audio.png)

* Albums

This section uses the Bootstrap "Card" feature. A list of The Monkees past albums featuring an image, album title and a link to purchase is
included. These albums covers are responsive and react to individual device sizes.

![album purchase section image](assets/images/readme-albums.png)

#### Event Booking (contact.html):

* Event Booking Form

This page allows the user to contact The Monkees with regard to making a future booking for events such as birthdays anniversaries and larger 
events such music venues and festivals. It makes use of Bootstraps form-group and uses labels and inputs (including select fields and radio
buttons). The image below show the event booking form in both mobile (left) and desktop view (right).

![event booking form image](assets/images/readme-booking.png)

### Testing:

This website was tested at every single stage to ensure that it responded correctly to every device type. Media Queries
were used where required to ensure that every aspect responded as desired with regard to image size, layout, positioning etc.

It was tested using various browsers i.e. Google Chrome, Microsoft Edge and Mozilla Firefox utilising available tools such as 
Chromes dev tools and Firefox's Responsive design mode. The site could then be inspected as it was being worked on and any changes being made to the site were constantly
being monitored to see how the different browsers and screen sizes would be affected. Using all these available tools I was able to
ensure my website functioned correctly and is responsive as possible on all device sizes. The image below shows how this responsive design
mode tool was utilised to show the website on various device types and brands.

![mozilla firefox responsive design mode image](assets/images/readme-responsive-design-mode.png)

### Author:

Shane Coen (This project is part of Code Institute's Online mentored Software Developemnt course and was completed in March 2018).


















