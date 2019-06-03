# Sass Master Template

This is a basic toolbox of SASS styles, properties, and mixins that is meant to be dropped into any early-stage project. It covers a lot of the odds and ends found in just about any project, without being bogged down by project-specific necessities. This project should help simplify the setup stage of a new project rather replace or supplement existing frameworks of the same nature.

## Installation

Clone or download this project and drop the `/sass` folder in the appropriate directory for your project.

Alternatively, you can opt to use only select partials relevant to the needs of your project.

## Usage

This project is divided into 2 parts: partials and the master stylesheet.

Partials are constituent stylesheets that are divided up by purpose, such as typography or layout. This makes code more organized and easier to maintain.

The master stylesheet is a singular document which contains imports for each of the partials. This is the only file that gets imported into your specific project. `_mixins.scss` is the only partial that does not get imported into the master stylesheet, since mixins do not compile into plain CSS.