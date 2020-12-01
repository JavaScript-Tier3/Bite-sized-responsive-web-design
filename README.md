# Bite-sized-responsive-web-design

## Overview of HTML and CSS
- HTML, which stands for Hypertext Markup Language, is used to establish the raw page structure for web pages. This is what will make up the headings, tables, images, paragraphs, and so on. Essentially everything that appears on the page will need to be contained in an HTML element. 

- CSS, which stands for Cascading Style Sheets, is used to apply formatting and design to the raw HTML. This will be font, colors, layout positioning, animations, and so on. CSS is what will make the web page look more appealing, and can be how you add in accessibility features to the web page. 

## HTML Elements
- block-level elements will always need to be on their own line in the HTML code.

- inline elements will be on the same line as other block-level and inline elements.

## CSS Features
- Rules:
    selector { property: value; }

- Internal style sheet: the CSS rules can be stored within a specific HTML page

- External style sheet: This is a file that is stored in the site's root folder with a ".css" file extension.  This style sheet will contain all the CSS rules for the site. They can control and format an unlimited number of HTML pages, so they are quite beneficial for working with large sites. 

## Responsive Web Design with Media Queries
One of the difficulties with web design is that your web page will be visited by people using a wide variety of devices, from desktops to netbooks to various kinds of smartphones. All these devices can have different sizes and shapes. As a developer, you cannot possibly know what kinds of devices people will use to view your site. However, to provide the best possible experience, you need to make sure that the website responds to the user's device and changes the layout accordingly. This is what responsive web design is all about. 

There are a variety of methods to achieve the desired responsiveness, but the best solution is to use what are called CSS media queries, or simply media queries. Media queries work by applying a specific group of CSS rules to your web layout, but only if the device viewing the web page matches a specified width. 

For example, you can create a set of CSS rules that format your web layout and apply a media query to it. This media query will make it so that those CSS rules will only be applied if the device being used has a screen width that is less than 320 pixels in width. Then you can create a second set of CSS rules, but this one will only be applied if the device has a screen width greater than 1200px (pixels) in width. 