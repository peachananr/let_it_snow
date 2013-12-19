#Let it Snow by Pete R.
Create and Control a Festive Snow on Your Website using HTML5 Canvas
Created by [Pete R.](http://www.thepetedesign.com), Founder of [BucketListly](http://www.bucketlistly.com)

Note: This plugin is based on [Jason Brown](https://github.com/loktar00)'s solution [found here](http://stackoverflow.com/questions/13983764/creating-falling-snow-using-html-5-and-js)

[![Let it Snow](http://www.thepetedesign.com/images/let_it_snow_image.png "Let it Snow")](http://www.thepetedesign.com/demos/let_it_snow_demo.html)

## Demo
[View demo](http://www.thepetedesign.com/demos/let_it_snow_demo.html)

## Compatibility
Modern browsers such as Chrome, Firefox, and Safari on both desktop and smartphones have been tested. I have not tested this on IE.

## Basic Usage
Let it Snow is a little plugin that is based off the solution of creating a snow effect with HTNL5 Canvas by Jason Brown. I decided to extend its functionality so that developer will have a full control of how the animation of snow will react.

To add this to your website, simply include the latest jQuery library together with `jquery.let_it_snow.js` into your document's `<head>`, and simply call the function like this:

````javascript
  $("canvas").let_it_snow({
    speed: 0, // How fast the snow falls can be define here. You can choose a number in between 0 - 5. The higher, the faster. The default value is 0.
    interaction: true, // This option allows viewer to interact with the falling snow. Toggle this to false if you don't want the snow to be interactive. The default value is true.
    size: 2, // You can set the size of the snow here. Choose a number between 0 - 10+. The higher, the bigger. The default size is 2.
    count: 200, // This allows you to set the number of snows displayed at a time. The default count is 200.
    opacity: 0, // The opacity variation of the snow. You can choose a number in between 0.00 and 1.00 to set the base opacity and the plugin will randomly generate snows with slightly varied opacity.
    color: "#ffffff", // You can set the color of the snow here. This option only accepts HEX color code in full 6 digits. The default value is "#ffffff"
    windPower: 0 // You can set the wind power here. If you want the wind to blow left, set a positive number in this option., if you want the wind to blow right, set a negative number in this option. The default value is 0.
  });
````

And that's all for this plugin. Stay tuned for more updates.

If you want to see more of my plugins, visit [The Pete Design](http://www.thepetedesign.com/#design), or follow me on [Twitter](http://www.twitter.com/peachananr) and [Github](http://www.github.com/peachananr).

## Other Resources
- [Jason Brown's Repo](https://github.com/loktar00)
- Tutorial (Coming Soon)
