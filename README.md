# The 3056 Project
A bespoke Wordpress theme designed and developed especially for The 3056 Project.

http://www.the3056project.com

# About
The 3056 Project is a love-letter to the suburb I lived in for almost ten years, Brunswick, in Victoria, Australia.  My husband analysed data from the Victorian Commission for Gambling and Liquor Regulation and we came up with a definitive list of bars and pubs from within our suburb.  The rules were we were to have at least one drink in every bar, make some notes about the amenities, but also reflect on what it meant to us as Brunswick-ians.

# On the Inside
The 3056 Project uses a fairly traditional blog method of presentation.  Each pub is a blog post, and additional pages are used as required.

Categories are used to list the features of a pub (such as does it take credit cards), and the Advanced Custom Fields plugin is used to show information about how many drinks are on the menu and to store the pictures.  I wanted the back-end to be as easy to use as possible, the idea being that my husband could update this website without my assistance.

The actual website is hosted on a Digital Ocean Ubuntu server, which I set up with Nginx, rather than Apache.  On a previous project, where I hosted a small website on a small server, I found the MySQL server would often crash if it received a moderate amount of traffic.  The combination of Nginx, and the plugin WP Super Cache, has meant my server doesn't quite take the beating it used to.

# On the Outside
The design reflects some of our favourite pubs -- they're a little dingy, perhaps a little cluttered, but overall charming and friendly.  The logo was inspired by vintage beer logos.

We noted during the soft launch period that almost all of our traffic was coming from mobile, and ensured that this design was made with that in mind.

The decision to use SVG icons was also based on our analytics data, as it suggested that our uses were running browsers capable of displaying the graphics.

I think my favourite design decision was to list the bars geographically.  It feels like I'm giving away a secret here, but Brunswick is a fairly long, narrow suburb and the majority of these bars are on Sydney Road.  The bars are listed from north to south.  I attempted to do this using the address alone, but some addresses didn't actually describe where one would consider the bar to actually be, so the longitude was utilised instead.

The 3056 Project also includes the packages Smooth Div Scroll and Masonry.js.
