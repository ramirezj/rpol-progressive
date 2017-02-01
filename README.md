# RPoL-Progressive

Reimagining the [RPoL.net](http://rpol.net) play-by-post roleplaying forum as a modern progressive web app.

## Background

RPoL.net has ~5,000 active campaigns, with ~9 million posts, by a broad and engaged user community. Some have be running campaigns here for > 10 years. It was built and continues to be maintained by a sole developer, `jase`, with support from a small core of moderators. Between them they have nutured a long-lived and welcoming community, that I belong to.

Reimaging the front-end of the site is an exercise in the possible, for me. 

It is not supported or endorsed by the RPoL.net team in any way (though I have informed them of this project and would welcome the opportunity to give back to the community).

## Design Constraints

For initial iterations over the site, I have imposed constraints that match those of the site, as I understand them. These have been gleaned by the existing community forums, especially those of a technical nature:

* Users come from a broad range of backgrounds, abilities and familiarity with computers
* Some users will have slow and low-bandwidth connection to the internet
* Some users will have obsolete or underpowered devices and browsers
* Users cannot necessarily change these things, nor should they be required to
* Users create much of the content, much of which is freeform text or semi-structured content
* Users consume the content, seeking narrative immersion unhindered by the technology
* Users are loyal, familiar with how the site works right now, and for those part comfortable with that

## Principles

* Any changes to the existing experience must be made objectively and with care
* Everything must be built as a progressive enhancement on top of the content
* Everything must be built so as to be reusable as standalone components
* All surface components should be fully responsive and readable on any device
* All surface components should be responsive to content, i.e. 0, 1 or N
* Everything should be accessible and have the scope to be internationalisable
* Everything should be as fast as possible 

## Challenges

* Data on existing usage and journeys is unavailable to me
* Data on the breakdown of devices, browsers, screen resolution and other technical context for the users is unavailable to me
* Bias may be brought in from my own experience as a user, or from the non-representative sampling I will speak to, i.e. self-selected subset of users who read the forums and have expressed an interest in improvement or change
* Only the final presentation outputted by the site is available for my review
* Only a subset of the screens is available

## Solutions

At this stage I intend to tackle this screen-by-screen, beginning with the front page for a logged on user. I have begun simply with a static mock, written from scratch in HTML5 and CSS3 with no or minimal Javascript, that recreates surface elements of the existing theme, layout and features. 

For the first pass there are elements that do not fully satisfy all the principles, such as the use of SVG for images and fallbacks for some modern HTML and CSS elements. These will be addressed.

For the second and subsequent passes I will be introducing a dynamic build with templates, probably Metalsmith with Handlerbars, and a component guide to examine sub-elements.

## Contributing

Feedback and bug reports welcome; this is a personal portfolio project so I'm not expecting to take pull requests.

## License

[CC BY-NC 2.0 UK](https://creativecommons.org/licenses/by-nc/2.0/uk/)
