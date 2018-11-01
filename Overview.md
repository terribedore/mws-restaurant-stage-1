[Intro Video](https://www.youtube.com/watch?v=N-Tf905Oerk)

# Project Overview
For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also begin converting this to a Progressive Web Application by caching some assets for offline use.

## Specification
You will be provided code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

## Requirements
**Make the provided site fully responsive**. All of the page elements should be usable and visible in any viewport, including desktop, tablet, and mobile displays. Images shouldn't overlap, and page elements should wrap when the viewport is too small to display them side by side.

You will convert a site that looks like this:
(https://d17h27t6h515a5.cloudfront.net/topher/2017/August/598b4108_starter-mobile-page-1/starter-mobile-page-1.png)
Not ready for mobile.

(https://d17h27t6h515a5.cloudfront.net/topher/2017/August/598b4152_starter-mobile-page-2/starter-mobile-page-2.png)
Not ready for mobile, either.

...into a site that looks like this:

(https://d17h27t6h515a5.cloudfront.net/topher/2017/August/598b41ee_finished-mobile-page-1/finished-mobile-page-1.png)
Responsive and mobile-ready.

(https://d17h27t6h515a5.cloudfront.net/topher/2017/August/598b423a_finished-mobile-page-2/finished-mobile-page-2.png)
Also responsive and mobile-ready.

**Make the site accessible**. Using what you've learned about web accessibility, ensure that `alt` attributes are present and descriptive for images. Add screen-reader-only attributes when appropriate to add useful supplementary text. Use semantic markup where possible, and aria attributes when semantic markup is not feasible.

**Cache the static site for offline use**. Using Cache API and a ServiceWorker, cache the data for the website so that any page (including images) that has been visited is accessible offline.
