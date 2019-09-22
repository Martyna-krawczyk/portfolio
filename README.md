# Martyna Krawczyk Portfolio Website
The portfolio can be found using the below link:
https://martyna-krawczyk.com/

Files can be accessed via Github link below:
https://github.com/Martyna-krawczyk/portfolio

## Purpose
This portfolio website has been created to consolidate access to web and programming projects which I have completed both during the Fast Track course, as well as in the past. It is in itself, also an example of my HTML and CSS skills.  The target audience would likely be future employers in the dev industry.  I wanted the design to look clean, but not sterile and was inspired by many designs on dribble. Please use the below links to access screenshots:
[Dribble Moodboard Screenshot1](https://drive.google.com/file/d/1HgsrkHMqn4SYKd6-AKzreQd11qCIki4g/view?usp=sharing)

[Dribble Moodboard Screenshot2](https://drive.google.com/file/d/1NAawGnmRgT701TPj65fWsm3_p8svdu8s/view?usp=sharing)

[Dribble Moodboad Screenshot3](https://drive.google.com/file/d/1NlpALrxtAtGTtX6HKWD77McHN4B-X6C-/view?usp=sharing)

## Tech Stack
- HTML
- CSS
- Netlify
- Formspree

### Features
Most pages of the website display a header with a background image, with the exception of the Blog.  All pages also include a navigation bar, social links block as well as footer which I will describe in more detail below:

The website is composed of the five below pages:
1. Home
2. About
3. Portfolio
4. Contact
5. Blog

## Sitemap
[sitemap](https://drive.google.com/file/d/1jnuNX-BoirilCbV3VpF_eBpN6T8EpLd4/view?usp=sharing)

In order of appearance, please find some of the pages' functionalities below:

#### Home
The home page includes a summary of what I am up to now, as well as a flexbox containing links to other pages.  The page has media queries to handle the wrapping of the boxes to the narrower page-width and does this seamlessly thanks to the container width adjustment on each card. The cards also have a hover transformation with a slight scale-up.
[Home Wireframe](https://drive.google.com/file/d/1yM5D-6uFWA6ea4YmXEtMdlHAbqxTsY55/view?usp=sharing)

#### About
Under the header section is a short text paragraph about me, followed by a link to download my resume (as a direct download). This page also contains a timeline outlining my past experience.  The timeline took significant work - particularly in making it responsive - I was introduced to new concepts including the pseudocodes :nthchild and :before :after whilst building this element.
[About Wireframe](https://drive.google.com/file/d/148OUjYgVpnijO-P_hJDkqCgtw3wtgGC5/view?usp=sharing)

#### Portfolio
The portfolio section of the website contains five card-style elements (flex-box), each containing images of each respective project as well as links to their sources.
[Portfolio Wireframe](https://drive.google.com/file/d/1gMWbiqaREJQgShVj6D0WPQ_6WrIjfcak/view?usp=sharing)

#### Contact
This page contains a form, styled to the page, and thanks to Formspree (https://formspree.io/), will email me all submitted form field content.
[Contact Wireframe](https://drive.google.com/file/d/1vWchmji_P1ez9OAoe8nWIK4r9uo1QnjD/view?usp=sharing)

#### Blog
The blog doesn't contain the header - instead it contains five [almost] page-width cards which are also responsive. The cards also have a hover transformation with a slight scale-up.
The blog cards contain meta data such as author, date and tags, though these link to the current page, however therre is a Read More>> tag which sends the reader to the original LinkedIn article I have written.
[Blog Wireframe](https://drive.google.com/file/d/1_BioH6oHH0ZejDn4sj-TknrYB80ricc2/view?usp=sharing)

## Navigation
The nav bar at the top of each page was particularly challenging as it was clear that I needed an hamburger menu on the smaller-width media queries.  Once I had the code ready to go, I needed to make changes to the css so that on media query, the hamburger menu would become visible and the top menu links would hide, and vice-versa. The inclusion of the responsive navbar meant that much of my header section content was displaced and this required further rectification.  The navbar now responds to different screen sizes nicely.

### Responsive Navigation Screenshots
[Hamburger Menu](https://drive.google.com/file/d/1kJxc_YcyHjaWVWyusd1hB73MGP10BU9Y/view?usp=sharing)

[Wide-screen menu](https://drive.google.com/file/d/16O02ICHxDVESKw-CUtRE90ChlJzAYvXw/view?usp=sharing)

## Axe - Accessibility
I ran the website through the aXe accessibility extension and was able to follow the recommendations on the home page to satisfy the requirements.  The extension required that I added a title tag to all links which didn't contain any text, therefore I added these as well as adding the <main> tag to the page. AXe also recommended that I consider the h1 and p text being used over a background image to ensure that there was sufficient contrast asd it couldn't 'see' what the background image colours were.  Please see the screenshot using the link below:
![Accessibility](docs/requirements-to-safisfy-axe.png)

## HTML Validation
Because of the hamburge menu, the html validator was not happy that the menu div was within a child, label. It was the only outstanding error, however I decided to leave it as is in order to remain functional to the user.
[HTML Error validation](https://drive.google.com/file/d/1hjxqSxi_8Q-iRlqihrjO4DtAbFsGa-kV/view?usp=sharing)

## Design Variations
There are three variations to the overall design and the three different 'looks' can be accessed via the below links:

[Screenshot of version one](https://drive.google.com/file/d/1l2W9xMKOWPqaHiI62AOR-taiqon_I6jz/view?usp=sharing)

[Screenshot of version two](https://drive.google.com/file/d/1jAV7926U-Jw8_mYLgWgqW2gbCKOgxe5W/view?usp=sharing)

[Screenshot of version three](https://drive.google.com/file/d/1zGLdx6SC1ClUBW8_7xquP_n3GBilzlL1/view?usp=sharing)




