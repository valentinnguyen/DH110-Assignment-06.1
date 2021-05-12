# DH110 Assignment 06.1 — Interface Design
##### Valentin Nguyen | Spring 2021 | Dr. Sookie Cho

## Overview Description
GenMeet is a website that is meant to "bridge the gap" by providing an opportunity to bring people from different generations together to have a conversation. The follow UI designs is of the homescreen, or the very first screen the user sees when opening the website. 

### Process
This prototype allows a user to create their own profile on the GenMeet website. It is developed based on one of my personas, Maya Edwards, who is a librarian born in 1970 (making her Gen X). The user has to put in their basic information through input fields. If the user doesn't input any information in the fields, a message and icon in a bright red color will prompt hte user that they need to input info into the fields. Then, the user has to indicate which generation they're from, then select which generation they would like to meet more people from through a series of buttons. Once the user reaches near the end of the process, they will have to input their phone number and verify themselves with a code sent to their phone number. This is to verify the user as a legitamate person if they provide their real information.

### Purpose
The purpose of this website is to create a visual prototype draft of one of the many tasks a user will have to perform when using the website. It is meant to cater towards users who have just found the website and navigates them through the process of making their own profile within the site.

## UI Screen Designs with Variations

Below are variations of the homepage interface design:
- Top left: Light Mode, which is also the default home screen for all interfaces.
- Bottom left: Dark mode, for users that prefer dark mode.
- Top right: Black and White Light Mode, for users that prefer black and white mode.
- Bottom right: Black and White Dark Mode, for users that prefer black and white mode and dark mode.

<img width="1128" alt="Screen Shot 2021-05-11 at 4 41 29 PM" src="https://user-images.githubusercontent.com/81778205/117897498-cface900-b277-11eb-8a33-882c9dff0f4d.png">

### UI Design Description

The user interface design is meant to be simple but also include all of the essential information the user would need to know when stumbling upon the homepage. On the upper left-hand corner is the logo of the app, GenMeet, which is big enough for the user to also recognize it as a button to bring them back to the homepage if they were on any other page in the app. The app's motto, "BRIDGE THE GAP", is displayed in a large and bold font to emphasize the main purpose of the app. Below the motto is a description of why the app exists and how it benefits the user, with a few highlights to emphasize the important parts of the description. Right below is a bold yellow button labelled "GET STARTED", which hopefully prompts the user to begin making their profile in the app. Finally, on the far left is an illustration of a staircase between two pathways. The staircase "bridges the gap" between the two paths, bringing back the motif of the motto.

While I was designing the rest of the screens, I kept in mind to keep the overall prototype as visually consistent as possible so that the user can quickly familiarize themselves with the branding of the website. Additionally, there are small details that follow the 10 usability heuristics such as visibility of system status (blinking cursor in input fields), user control and freedom (chevron arrows that users can press to go to the previous screen), error prevention (red messages and icons to inform users they have to fill in the fields), and more.

## Impression Test

View the impression test [here.](https://drive.google.com/file/d/1kSNs6GzS37rvJVx_VE3qPw9ipFsWQ6sF/view?usp=sharing)

## Accessibility Check

Below is a graphic indicating the accessibility check for the various color schemes I have on the interface designs:
<img width="968" alt="contrast checker" src="https://user-images.githubusercontent.com/81778205/117901181-aabc7400-b27f-11eb-8003-52f5543c6bf3.png">

## Design System

##### Typefaces

For the typeface, I wanted to select a san serif font that was bold and simple but simply rounded. Rubik has slightly rounded corners and was provided in both Roman and Italic styles. The GenMeet logo is in the Italic Rubik typeface, and the rest of the prototype uses only the Rubik typeface.

![cda34068bf385a6a143dd1e2a261ceb6](https://user-images.githubusercontent.com/81778205/117904609-84e69d80-b286-11eb-8949-c246b47cbe29.png)

##### Color Scheme

My initial instinct was to make everything black and white because I can confidently say that that color scheme passes the accessbility check, and it's fairly simple. However, I thought it was too simple, so I decided to throw in a few contrasting and vibrant colors to make the overall design more interesting and pleasant to look at. I decided to go with a more warm color scheme to make the overall mood of the website more positive. 

For the default color scheme, the background of the website is white and the foreground elements include a green progress bar, black text, and yellow buttons with black text on top that prompt the user to press when they want to move on to the next screen. I also used a bit of red to consider error prevention, which is whenever a user forgets to put in information in an input field (a message saying "Your ______ is required" along with an icon of an exclamation mark in a circle.

<img width="1141" alt="color palette" src="https://user-images.githubusercontent.com/81778205/117901171-a5f7c000-b27f-11eb-8bd6-3dce59def603.png">

##### Layout grid + spacing

For the layout grid, I had decided to put in 1 row and 7 columns through each screen, with 20px gutters around the perimeter of the screen as well as between the colomns. My reasoning for choosing 7 columns is that it provides a good guideline for two elements on each screen: the progress bar and the chevron arrow. The progress screen fits nicely between the third and last columns, and the chevron arrow aligns nicely along the third column as well. 

<img width="792" alt="Screen Shot 2021-05-11 at 6 33 44 PM" src="https://user-images.githubusercontent.com/81778205/117905124-8369a500-b287-11eb-902e-d0f209d53def.png">


