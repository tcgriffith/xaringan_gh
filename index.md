
## Hello github page

### Link

Note the relative link starting with a slash before the html file.

The index.md is used to customize the github page's home page, 
The following link directs to the slide.

Code: `[slide link](/xaringan_example.html)`

Result:

[slide link](/xaringan_example.html)


### Embed

Or you could embed the xaringan slide into a webpage using iframe:

Code:

```
## CSS styles
<style>
.resp-container {
    position: relative;
    overflow: hidden;
    padding-top: 56.25%;
}

.testiframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}
</style>


## html iframe to embed the slide.

<div class="resp-container">
    <iframe class="testiframe" src="https://tcgriffith.github.io/xaringan_theme_example/use_master.html">
      Fallback text here for unsupporting browsers, of which there are scant few.
    </iframe>
</div>

```

Result:

<style>
.resp-container {
    position: relative;
    overflow: hidden;
    padding-top: 56.25%;
}

.testiframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}
</style>

<div class="resp-container">
    <iframe class="testiframe" src="https://tcgriffith.github.io/xaringan_gh/xaringan_example.html">
      Fallback text here for unsupporting browsers, of which there are scant few.
    </iframe>
</div>