# The Monkees website
🔸 Milestone Project #1: User-Centric Frontend Development - Code Institute

## Overview
This project is a website for the rock band "The Monkees", which is targeting the current and potential fans. The primary goal is to showcase their best work (such as video clips, music and pictures) and create a social presence connecting to their fans (through online booking and social medias). It is designed from a mobile-first approach

## Deployment

The live project url is https://clarabausson.github.io/milestone_project_1/. 
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://github.com/ClaraBausson/milestone_project_1.git into your terminal.

## UX
The main goal for this project was to make it as easy as possible for current fans to keep updated on their favourite's band activity aand have a place to get in touch with them, and for potential fans to learn more about the band. 
The color scheme is black and white with orange highlights, to keep the website minimalistic and simple while still matching the band's style.


## Technologies
1. HTML5
2. CSS3
3. Bootstrap (4.3.1)


## Features

### Existing Features
* Responsiveness on both mobile and desktop
* Static navbar to allow the user a quick access to all areas
* Collapsed navbar on smaller screen sizes
* Spotify iframes to showcase the music
* Tour section informs the user on the next touring dates and allow them to buy tickets online (generic website) and visit the event's website (if it's a festival)
* Booking form allowing users to contact and book the band for private events

### Features Left to Implement
* ScrollSpy feature 
* Smooth scrolling effect


## Testing
The current and potential fan user story achieved the intended outcome of providing them with information and work shwocase of the band. They are able to see the showcased content (pictures and music) via the "Gallery" and "Music" sections.
They are also able to view the band's social media profiles via clicking on the icons in the header (or footer in large screen devices).

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to all fields, so if those fields are not filled in, the form will not submit.

All links will open in a new tab using 'target="_blank"' and have been manually tested to ensure that they are pointing to the correct destination.

This site was tested across multiple browsers (Chrome, Safari) and on multiple mobile devices (iPhone 5, 7, 8, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. 

During the testing phase, I realized that an overflow was displayed on the right side of the website, which I fixed by setting the overflow-x to none for html in my CSS file.

### Remaining bugs
* Gallery - Upon opening an image in full-screen mode, the user is sent back to the landing section; as this code is from Fancybox and relies on Javascript, I have been unable to fix it on time.

## Credits

### Authors

* **Clara Bausson** - *Initial work* - [ClaraBausson](https://github.com/ClaraBausson)

### Content
All content in the "About Us" in this website were based on [Wikipedia](https://en.wikipedia.org/wiki/The_Monkees). All content in the "Home" in this website were based on the [official website](https://www.monkees.com/news). All other content were written by me.

### Media
All background images were taken from [Pexels](https://www.pexels.com/), a stock image library, with the exception of the photos of the band, which were downloaded from the [official website](https://www.monkees.com/). Some pictures were modified with filters, to better fit the overall theme.

The pictures are hosted on [Cloudinary](https://cloudinary.com/).

### Acknowledgements
The media viewer from the gallery section is from [Fancybox](https://fancyapps.com/fancybox/3/).

The icon set for the social links was taken from [FontAwesome](https://www.bootstrapcdn.com/fontawesome/).

The fonts used are from [GoogleFont](https://fonts.google.com/).

The Spotify embed was generated with [Spotify for Developers](https://developer.spotify.com/documentation/widgets/generate/play-button/) and modified to improve the sizing and alignement of the embed.

The photo effects were taken from [codepen.io](https://codepen.io/nxworld/pen/ZYNOBZ).

I have received inspiration from various artists' websites, notably [MARINA](http://www.marinaofficial.co.uk/), [Eminem](https://www.eminem.com/) and [Metallica](https://www.metallica.com/).

**This is for educational use.** 