# Refined Theme

This is a fork from [Kwan Theme](https://github.com/icoloma/jsonresume-theme-kwan) by Nacho Coloma. 

It's been refined - just a little bit!

 * Month names are in long form, e.g. "July" instead of "Jul".
 * The small clock icon and the duration have been removed.
 * If no references are specified, then the phrase "Available on request." is displayed.

[Theme Preview](http://themes.jsonresume.org/refined)


### To develop your resume

To develop iteratively (either to modify the template, CSS or resume contents) to the following

```
$ git clone https://github.com/kenguest/jsonresume-theme-refined.git
$ cd jsonresume-theme-refined
$ npm install
$ grunt watch // watches for less file changes
$ ./serve.js [optional_resume_filename] // Do this in a separate terminal to run the server with the provided resume or a default one
```

Visit [http://localhost:8888](http://localhost:8888) to see the theme in action.

