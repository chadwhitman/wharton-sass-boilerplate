## Wharton Sass Boilerplate
#### A simple way to organize your SASS files using a 3-1 architecture pattern.

#### Overview
The scss directory consists of three folders to organize a projects main style areas:
- base
  - the base directory is the place to keep all global related styles, including helpers and mixins.
- components
  - the components directory is the place to create styles for each part of an application. This can include layout related items (e.g., footer, header, main), to things like buttons or cards or navigation. Note: I prefer to consider layout items like any other component and not breaking them out into their own folder (as there is often overlap anyway and it avoids confusion in the long run).
- library
  - the library directory is the place to put any and all third-party stylesheets (e.g., Bootstrap, Normalize).

#### Authors

- Chad Whitman

#### Inspired by

- SASS Boilerplate by Hugo Giraudel
- Tom Rose, @slurve
