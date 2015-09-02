# Internal talks

We're going to be using [Reveal.js](https://github.com/slara/generator-reveal) to easily setup and deploy our slideshows.

You need to have [Yeoman](http://yeoman.io/) installed.

To install the Reveal.js generator do ```npm install -g generator-reveal```. Then setup your new directory ```mkdir my-new-project && cd $_```. Run ```yo reveal``` and follow the instructions. Finally use ```grunt serve``` to serve your files. 

Then you can add or remove files by adding things to the `slides` directory. Every markdown file you add into the directory just append the name to the ```list.json``` file, and that will determine the order.