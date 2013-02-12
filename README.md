# CurtainsUp

## An aggregator of coolness/amazing tools for your web projects

CurtainsUp is a boilerplate which has the philosophy of providing developers with *a real lot* of cool libraries. All those tools are disabled by default (commented out). Start coding, and unleash a tool every time you need it by uncommenting it. 

<ul>
    <li><a href="http://twitter.github.com/bootstrap/" title="Twitter Bootstrap">Twitter Bootstrap</a></li>
    <li><a href="http://html5boilerplate.com/" title="HTML5 Boilerplate">HTML5 Boilerplate (Utility Classes)</a></li>
    <li><a href="http://jquery.org/" title="jQuery">jQuery</a></li>
    <li><a href="http://underscorejs.org" title="Underscore.js">Underscore.js</a></li>
    <li><a href="http://backbonejs.org" title="Backbone.js">Backbone.js</a></li>
    <li><a href="http://lesscss.org/" title="LESS">LESS</a></li>
    <li><a href="http://git.io/normalize" title="Normalize.css">Normalize.css</a></li>
    <li><a href="http://modernizr.com/" title="Modernizr">Modernizr</a></li>
    <li><a href="http://leaverou.github.com/prefixfree/" title="Prefixfree">Prefixfree</a></li>
    <li><a href="http://imakewebthings.com/jquery-waypoints/" title="jQuery Waypoints">jQuery Waypoints</a></li>
    <li><a href="http://fittextjs.com/" title="FitText.js">FitText.js</a></li>
    <li><a href="http://letteringjs.com/" title="Lettering.js">Lettering.js</a></li>
    <li><a href="http://fgnass.github.com/spin.js/" title="Spin.js">Spin.js</a></li>
    <li><a href="http://benalman.com/projects/jquery-throttle-debounce-plugin/" title="jQuery Throttle Debounce">jQuery Throttle Debounce</a></li>
    <li><a href="http://code.google.com/p/google-code-prettify/" title="Prettify">Prettify</a></li>
    <li><a href="http://inuitcss.com/" title="Inuit.css">Inuit.css</a> <a href="https://github.com/peterwilsoncc/inuit.css" title="Inuit.css LESS port">(LESS port)</a></li>
    <li><a href="http://www.entypo.com/" title="Entypo">Entypo</a></li>
</ul>


## Download

The files you are going to need are located either in "cup" folder. When upgrading to a new version, simply replace the "backstage" folder with the new one (see "How to upgrade" below).

## How To Use

Once you have downloaded CurtainsUp, simply rename the "blueprint.html" file to suit your purpose ("index.html", "article.php" etc.). And that's it.


## Before Going Live

When you're done building your application and ready to open its doors to the masses, make sure you improve your application's performance by reducing http requests: minify the .js tools you have used and store them in one file (that would be "js/min.js"). Then comment out the libraries that have been minified as you don't need to request them anymore. Do the same with CSS libraries (just store them in "css/min.css").

## How to upgrade

With all the libraries included in CurtainsUp, the project will certainly be updated quite often. All the tools aggregated in CurtainsUp are located in a folder named "backstage". You may have noticed that the bits of code including JS and CSS tools in blueprint.html are version-agnostic, so when an upgrade occurs, all you have to do is download the backstage folder and use it in place of the previous one.


## Versioning
CurtainsUp adheres to the semantic versioning system: 

major.minor.patch

The patch version is incremented when a small change is made to CurtainsUp, whether it's a slight modification to the project's markup, or a library which has itself incremented its patch version.

The minor version is incremented when the included libraries have been updated in a more significant way (usually when they have incremented their own minor OR major version).

The major version of CurtainsUp is incremented if/when new libraries are added to the project.

When patch or minor versions are incremented, it is unlikely that you will have to modify or download again the blueprint.html file and the files that derived from them (always check the changelog to make sure of that, though). In such cases, you should probably just update your project by replacing your old backstage folder with the newly downloaded one.

When the major version is incremented, however, you should also update your blueprint.html file and the files that derived from them. You can simply check the changelog to see how to include the new libraries added to the project.

The backstage folder doesn't bear the number of its own version. This makes updating CurtainsUp easier: you don't have to modify all your file inclusions every time you upgrade. The current version of CusrtainsUp can be found in the "version.txt" file located in the backstage folder. The versions of the libraries included in CUp are found in the LICENSE.md file.

## How to help

If you want to monitor specific libraries and handle their updates, please get in touch with [@alexduloz](https://twitter.com/alexduloz). The more people get involved, the more efficient we will be, and the more accurate the versions used in CurtainsUp will be.

## About

### A word from the author

CurtainsUp was born at a time when many people were requesting features for [@thepastrybox](https://twitter.com/thepastrybox). I thought it would be nice if they had the opportunity to pull requests for a project they were enthusiastic about. I thought that, instead of using my own little frameworks, it would be smart to use libraries that are well-documented and that many people use. Since I didn't know exactly which tools would be needed, I decided to go overboard and provide a very rich, broad offer, so that everyone could easily pick the tools they needed.

I've used CurtainsUp on a few projects now besides the Pastry Box template and it takes me seconds to get started, and seconds to go live (I just have to remove/comment out the bits of code/plugins not used). I've used CurtainsUp with both the [Zend Framework](http://framework.zend.com/) and [Slim](http://www.slimframework.com/); in both cases the mutual inclusions worked great.

CurtainsUp is a humble venture. I don't deserve much credit for it. I've done my best to pay tribute to the awesome projects included in CUp. If you have authored some of the code aggregated in "backstage" and feel your work hasn't been given the respect it deserves, please get in touch with me.

## Change Log

### 0.2.0

Added [Harry Roberts](http://csswizardry.com/)' [Inuit.css](http://inuitcss.com/) ([Peter Wilson](https://twitter.com/pwcc)'s [LESS port](https://github.com/peterwilsoncc/inuit.css)) and [Daniel Bruce](http://www.danielbruce.se/)'s [Entypo](http://www.entypo.com/)

### 0.1.0

Initial release