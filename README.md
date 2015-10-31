# jQuery lazy load

This is a jQuery plugin for image lazy loading images. 

This plugin is modified for some plugins whitch do not work in some latest browsers.

##How to use?

For your HTML markup, please use data-src attribute instead of src:

    <img class="scrollLoading" data-url="/YOUR PICTURE PATH" />

In your Javascipt:

    $("img.scrollLoading").scrollLoading();