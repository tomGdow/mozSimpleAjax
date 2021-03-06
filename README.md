
## mozSimpleAjax

A great [simple example](https://developer.mozilla.org/en-US/docs/AJAX/Getting_Started) of Ajax by Mozilla

### Deployment

See [here](http://tomgdow.github.io/mozSimpleAjax/) for working code deployed on [github pages](https://pages.github.com/) 

---
### Structure

<pre>
.
├── index.html
├── README.md
└── test.html

</pre>
### Notes
 From the [Mozilla Site](https://developer.mozilla.org/en-US/docs/AJAX/Getting_Started)

 Step 3 – A Simple Example

Let's put it all together and do a simple HTTP request. Our JavaScript will request an HTML document, test.html, which contains the text "I am a successful Ajax Request." and then we'll alert() the contents of the test.html file.

---

Developed locally using the Python [simple HTTP server](https://docs.python.org/2/library/simplehttpserver.html) 
 
    python -m SimpleHTTPServer

The NodeJS [http-server](https://www.npmjs.com/package/http-server)  may also be used for local development

    http-server
