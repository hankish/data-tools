# Data Tools #

This is a parking lot for some random data manipulation tools.

These tools are just single html files. The UI is built using [LitElement](https://lit-element.polymer-project.org/) along with some components from Google's [Material Web Components collection](https://github.com/material-components/material-components-web-components).

## Tools ##

You can either use the Github-hosted copy or download the html file and open it in a web browser. Note: If you get any unpkg.com errors, just keep refreshing the page and they'll eventually go away.

- [Domain Extractor](https://hankish.github.io/data-tools/domain-extractor.html): Extracts web domains from URLs
- [Top Google Result Searcher](https://hankish.github.io/data-tools/top-google-result.html): Runs a list of Google searches and returns the titles and urls of the top searches. Useful for getting company websites in bulk. Note: For now this is built to work only with the [serpstack API](https://serpstack.com/documentation). But you could pretty easily update the source code to work with another SERP API provider. But you need to make sure that you use a SERP API that adds CORS headers to their responses otherwise your browser will throw a CORS error.