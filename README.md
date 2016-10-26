#GistLive
GistLive is a simple viewer for sharing live code examples hosted on GitHub Gist. For example, if your Gist URL is:

[https://gist.github.com/kyshel/53468bff883a0d195622d8c8506c7eb2](https://gist.github.com/kyshel/53468bff883a0d195622d8c8506c7eb2)

Replace “gist.github.com” with “kyshel.github.io/GistLive/?id=” in the URL to view it:

[https://kyshel.github.io/GistLive/?id=53468bff883a0d195622d8c8506c7eb2](https://kyshel.github.io/gistlive/?id=53468bff883a0d195622d8c8506c7eb2)

Your Gist need:

- index.html (essential)
- README.md (optional)
- .json (optional)

The main source for your example is in index.html. You can use absolute links, such as CDN-hosted D3, jQuery or Leaflet.  
To explain your example, add a README.md written in Markdown.  
Customize the appearance of your GistLive by adding a .json file. The following options are supported:



- license - a supported [SPDX](https://spdx.org/licenses/) License Identifier
- height - the iframe height in pixels; defaults to 700





##Credits
GistLive is run by [Kyshel](https://github.com/kyshel).  
GistLive is inspired by [bl.ocks.org](http://bl.ocks.org/)


Code highlighting by [Highlight.js](https://highlightjs.org/).  
Markdown formatting by [Showdown](https://github.com/showdownjs/showdown).

