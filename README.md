## muse-js-tinybuild

`npm i muse-js-tinybuild`

Browser: `<script src="https://cdn.jsdelivr.net/npm/muse-js-tinybuild@1.0.0/dist/muse.min.js"></script>` then MuseClient will be in the window

Just a repackaging of MuseClient to try to minify the library as much as possible using [`tinybuild`](https://github.com/brainsatplay/tinybuild).

The bundle has MuseClient available as a global so it can be included right in your html files and used in script tags. Run the index.html on a local server or use the `tinybuild` command for a quick test.

We got it down to 187kb minified, which is... a lot... but I blame the use of rxjs. This bundle includes types.


To run this repo, open the root in terminal and type:

`npm i` 

then

`npm start`

or

`npm i -g tinybuild & tinybuild` which will also handle missing dependencies



Might rewrite this down the line to be clean of fluff.
