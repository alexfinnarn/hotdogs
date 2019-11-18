# Dirty Dogs Work Sample

Hello! This is my solution to a work sample test listed at: https://github.com/Dynamit/front-end-code-day/tree/master/hotdog

I assumed the prompt to be ambiguous for the purpose of making the job candidate make decisions and show you how they think. In the rest of the readme, I'll go through my thought process in creating this website from the provided PSD and mock image. I'm about 90% happy with the current site, and I'll list the remaining issues at the end. I believe you shouldn't spend too much time finessing everything without some dialog back and forth to the designers, stakeholders, and other developers or else you might be wasting time where compromises or changes would have saved time and money...plus this is an unpaid test :)

Hosted site: https://alexfinnarn.github.io/hotdogs

## Main Assumptions

Before I began, I assumed that I only needed to code up the homepage and not the Contact, About Us, etc pages. I also used HTML and CSS for modern browsers without any vendor prefixes since no browser requirements were listed.

## Mobile-first Approach

My first thought was how to present the site in a mobile-first manner. While the mock image only showed what appeared to be desktop-like dimensions, more than half of web traffic these days comes from mobile devices which can be of all kinds of different screen dimensions. 

In a mobile-first approach, content is key. This is why I removed what I called the "hotdog leader" image in the header and replaced it with a mobile menu bar. The menu bar consists of an off-canvas menu, the business name, and two ways to further interact with the business via phone or Instagram. On really tiny screens, I left off the phone number since it wasn't in the header of the mock image anyway and screen realestate was scarce.

I wanted to use the least amount of JavaScript (JS) possible on the site since I still believe in a web that allows people to surf with JS disabled. I sometimes surf the web that way in order to not be tracked and save data...and it's just fun to see who's still paying attention these days. In the spirit of saving time and standing on the shoulder of giants, I don't want deny that I took a solution from the web and modified it for this site: https://medium.com/@heyoka/responsive-pure-css-off-canvas-hamburger-menu-aebc8d11d793

The rest of the site functions mostly the same as the desktop version except the flex direction and order of the hotdog types and footer information. Flexbox easily allows for changing direction in containers from rows to columns and reordering content. 

One decision I made was to place the hotdog descriptions after the images on the mobile version based on [the idea to "support information consumption flow"](https://ux.stackexchange.com/questions/50430/should-the-description-of-a-picture-be-above-it-or-below). When I scroll through a page, I first see an image and then my mind wants to connect that to a description, and I think a lot of people's minds work the same way.

## Desktop Version

For the desktop version, I altered the "hotdog leader" image to allow the business tag line and call-to-action (CTA) button to appear above-the-fold, at least on my work machine. The "More Dogs 'n Make Em Hot" button is the main conversion on the homepage so I thought it was important to make sure the user saw this without having to scroll on both desktop and mobile versions.

## Animations and Colorful Hotdog

I also made sure that the tagline and CTA button were above-the-fold so I could add some simple animations to draw the user's attention from a tasty hotdog, to what the business does, and finally to a button they could place an order by clicking. Animations can be confusing to users and a performance cost, but I thought this tactic would be a good way to drive conversions by leaving the user's eyes on the CTA button.

The mock image has a monochromatic version of a hotdog, but there is plenty of research on [how adding color can increase conversions in website content](https://getuplift.co/emotional-targeting-leverage-the-power-of-emotion-to-grow-conversions/). No one ever eats a monochromatic hotdog, but everyone is familiar with the colors of the bun, hotdog, and mustard I used to make up the hotdog. I took the liberty of coloring the hotdog to trigger the webiste visitor's memory of hotdogs and hopefully start a rumble in their tummies!

## Shortcomings/Improvements

Like I said, there are several areas that I would like to improve upon with input from teammates.

- **Flash of Unstructred Content with icons** - I used [Iconicons](https://ionicons.com/usage) for the Instagram, phone, and hamburger menu icons. They reccomend to use web components for the icons, and this causes the icons t
- **Hotdog leader image loading** - I don't like how the image appears at first in a choppy manner


