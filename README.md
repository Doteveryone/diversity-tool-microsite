# Our Diversity microsite

The microsite for the OurDiversity project.

Uses [Jekyll](https://jekyllrb.com) to generate static pages. Any local changes are pushed to GitHub, which takes care of rendering flat HTML files from templates.

## Visualiser component

Parts of this site are straightforward flat HTML files, but the visualiser is a separate, small React app. You can find out more about the [visualiser on its own GitHub page](https://github.com/Doteveryone/diversity-tool-visualiser).

The visualiser is compiled into production mode and copied over into the `visualise-the-data` directory of this repository every time an update is made.

## Development

Run `jekyll serve` from the root of the project to preview the project locally.

To build the production version run `jekyll build`.
