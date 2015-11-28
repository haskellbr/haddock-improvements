# haddock-improvements
Haddock is awesome. It doesn't have the prettiest/best interface in the world
though. Let's make it so.

This package has the haddock for the `aeson` package and very light changes to
the `ocean.css` haddock theme. Very soon it'll be hard to work with just
changing the CSS, without touching the structure.  It's possible to improve a
little though.

- - -

What to expect from now:
- Add `webpack` to build the JavaScript/CSS assets of Haddock
- Improve design and UX
- Collaborate back to the official Haddock resources

If the structure has to be changed, the haddock project will be forked and
this repository will be deprecated.

- - -
## Running a livereload server for development
```
make dependencies
make serve
```
This will install `browser-sync` and start it.
