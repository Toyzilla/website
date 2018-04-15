# website

Toyzilla website: [http://toyzillabox.com](http://toyzillabox.com).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

No prerequisites other than a code editor and a few web browsers for testing.

I use:

 * Atom (code editor)
 * *Google Chrome*, Safari and Firefox on 🖥 (web browsers)
 * *Google Chrome* and Safari on 📱 (web browsers)

(Optional)

 * Python (run a simple HTTP server locally)
 * Preview.app (simple image edits; crop, resize)


### Installing (Running)

 * Open this project in a code editor in order to start editing documents.
 * Open any of index.html files in a browser.

(Optional)

To run a simple HTTP server, you may use:

```
$ cd path/to/this/project
$ python -m SimpleHTTPServer 8000
```

Then you may open `http://localhost:8000/` to view the website.


## Tests

The website *should ideally* (see note below) be tested...

Using different platforms:

 * Mac OS X
 * Windows

Using different devices:

 * Desktop (mouse, touch)
 * Tablet
 * Phablet
 * Mobile

Using different resolutions and aspect ratios:

 * 4:3 (1024x768, 2048x1536)
 * 16:10 (1280x800)
 * 16:9 (1136x640, 1280x720, 1334x750, 1334x750, 1920x1080, 2560x1440)

Using different pixel densities:

 * 1 dpi
 * 1.5
 * 2
 * 3
 * 4


**Note on testing**

I generally only test on Google Chrome using the developer console to
simulate different screen sizes and densities. The Windows Surface proved to
be a special resolution not in the default settings.

## Coding Style

I try to respect the 80-column line while this is just a preference, and there
may be a few exceptions.

When there are many properties for HTML tags, I put them on different lines.

Example:

```
<img
  src="./images/bag-01.jpg"
  class="figure-img img-fluid rounded"
  alt="One of our bag of toys">
```

## Deployment

 * Rename any images or stylesheets that were modified by incrementing their
   numbers. (This is to avoid any caching surprises on Amazon S3.)
 * Login to Amazon. 🔐
 * Update assets in the appropriate S3 buckets.
 * Live tests.

## Built With

 * [Google Fonts](https://fonts.google.com/) - The fonts we used
 * [Bootstrap 4](http://getbootstrap.com/) - Styles and pop-up (modal)
 * [Font-awesome](https://fontawesome.com/) - Small icons
 * [The Noun Project](https://thenounproject.com/) - Other icons
 * [jQuery 3](http://jquery.com/) - Cross-browser JavaScript

## Contributing

To do...

 * Code of conduct
 * Process for submitting pull requests

## Versioning

To do...

 * Use [SemVer](http://semver.org/) for versioning.

For the versions available, see the [tags on this repository](https://github.com/Toyzilla/website).

## Authors

 * **Patrick Desmarais** - *Initial work* -
   [desmarais-patrick](https://github.com/desmarais-patrick)

See also the list of
[contributors](https://github.com/Toyzilla/website/contributors) who
participated in this project.

## License ⚖

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

 * README [template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
   by [PurpleBooth](https://gist.github.com/PurpleBooth). Thanks! 😉
 * Design feedback from other Toyzilla team members: Audrey, Stephanie and
   Rowena. 🇨🇦
 * Design feedback from Lloyd. 🇨🇦
 * Design inspirations: [Papirmass](https://www.papirmass.com/). Nice design! 😎
