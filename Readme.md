# Build Chrome Extension

You can build your own chrome extension, it is almost similer to a website, you can build it using HTML, CSS and JS. but here one more specific file is required name ```manifest.json``` and the inner structure of this file given bellow

```
{
  "name": "Extension Name",
  "version": "Extension Version eg. 1.0",
  "description": "Extension Name",
  "chrome_url_overrides": {
    "newtab": "Your main file. eg. index.html"
  }
}

```