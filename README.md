# Code conventions by Kyle Hotchkiss

## SCSS Folder Organization

I use the following folders for my stylesheet organization. I tried to find whomever originally inspired this convention but fell short.

* `components/` - Components are reusable chunks of code not tied to specific pages or templates. For example: header, footer, image with caption, and social button groups would belong here.
* `globals/` - Where to keep your `_variables.scss` and any other config-only SCCSS files.
* `plugins/` - If you load in a jQuery plugin with its own styles, drop them in here.
* `sections/` - Sections are stylesheets that map to a specific page or template. For example: home page, about page, and single post styles would belong here.
* `shared/` - Where to keep HTML element styling. Things like buttons, form fields, and typography styles go here. 
* `index.scss` - Include everything from above in here.
