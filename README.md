# Essentia

Business template for Hugo. This template has been built for editing and building with [Bookshop](https://github.com/CloudCannon/bookshop) and [CloudCannon](https://cloudcannon.com/). Built by [Insight Creative](https://insightcreative.com/).

**Disclaimer** - This template has been heavily integrated with [CloudCannon](https://cloudcannon.com/), and therefore many features are specific to the CloudCannon platform and may not work with other hosting providers.

**Disclaimer** - Essentia is a template for kick starting our Hugo projects. It's not a Hugo theme. Check the theme docs for more information.

## Features

* Pre-built pages
* Pre-styled components
* [Bookshop](https://github.com/CloudCannon/bookshop) component library for website building
* Fully configurable Website
* Blog with pagination and category pages
* Configurable navigation and footer
* Multiple hero blocks
* Multiple call to action blocks
* Multiple testimonial blocks - single and slider
* Contact forms
* Optimised for editing in [CloudCannon](https://cloudcannon.com/)
* SEO ready with preconfigured meta tags and schema data templates

## Technologies You Should Familiarize Yourself With

[Hugo](https://gohugo.io/) + [CloudCannon](https://cloudcannon.com/) + [Cloudinary](https://cloudinary.com/)

### Hugo 
Hugo is one of the most popular open-source static site generators. With its amazing speed and flexibility, Hugo makes building websites fun again. We choose to build with Hugo because of it’s amazing speed and great community. Try it out, you will be impressed.

### CloudCannon 
The CMS marketers *and* developers love to use.

### Cloudinary
For better image/video transformations and optimizations [integrate](https://cloudcannon.com/documentation/articles/integrating-your-dam-with-cloudcannon/) a third-party DAM like [Cloudinary](https://cloudinary.com/) or use [imgix](https://imgix.com/).

### PostCSS | [PurgeCSS](https://purgecss.com/) (removes unused CSS)

## Development Guide

## Installation
Install Hugo.

[Read the HUGO quickstart guide](https://gohugo.io/getting-started/quick-start/)

## Getting Started

To get started clone the repository then sync your files to [CloudCannon](https://cloudcannon.com/).

To run locally:

```
npm install
hugo server

```

That’s it! 

When Hugo is done building, you should see a success message like:

```
Web Server is available at //localhost:1313/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```

You may then view your local site in the browser at http://localhost:1313/.

Local development is powered by:

* A local development server at http://localhost:1313/.
* Automatic CSS & JS updates without reloading the page
* Automatic page reloads when content is changed

You now have a local environment up and running, start developing!

Need more information about Hugo? Visit the [Hugo docs](https://gohugo.io/documentation/) or get a jump start with the great [Jamstack tutorials](https://cloudcannon.com/community/learn/) from CloudCannon.

## Accessibility Tests
We do our best to follow the WCAG2AA standard, and one of the ways we check that we're following the right rules is through automated tools, like [pa11y](https://github.com/pa11y/pa11y/). For more info on the rules being tested checkout the [pa11y wiki](https://github.com/pa11y/pa11y/wiki/HTML-CodeSniffer-Rules).

### Running Tests
To run a web accessibility test do the following:

* Install and run the site locally following the Install and Run instructions above. Site must be running locally to perform the scan.
* If this is your first time running pa11y, then you'll need to run npm install -g pa11y-ci to make sure pa11y is installed.
* In a separate terminal window, run pa11y-ci to initiate the accessibility checker.

## Images
Images can be found in static/uploads.

## Site Settings

Essentia is set up for editing general site settings like logo, business name, phone, address and social media. Find site settings within Data > site_settings.yml