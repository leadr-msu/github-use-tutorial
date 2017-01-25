Because LEADR projects often require captions on images in order to allow for proper citation, adding images to html files requires a little more than simple <img> tags. Furthermore, the `src` value for an image used on a LEADR project should point to a locally-saved image, rather than a URL of the image on a website. This means you should be saving images from the internet into your repo, often into the "images" folder that is a sub-folder to the one that contains your html file. For example, if your html file is saved in a folder named "sites," it is easiest to save the image you use into the folder named "images" _inside_ of the one named "sites."

To add captions to images, it is important to use the <figure> container. Figure containers allow a <figcaption> container within, which makes captioning painless. Furthermore, any changes to the image's size, alignment, or other attributes should be made to the <figure> tag instead. Define the `<img>` tag with `width="100%"` in order to ensure the image's width expands and contracts as you change the size of the <figure> container.

Finally, to create a popover that displays the citation information about your image, use an <a> tag with the `href` attribute set to `"#"`, the `rel` attribute set to `"citation"`, the `data-toggle` attribute set to `"popover"`, and the `data-content` defined as the text of your citation.

Here is some example code for an image with a caption:

    <figure style="float: right; width: 40%; padding-right: 20px; padding-bottom: 5px;">
    
    <img src="images/duck.jpg" width="100%" />
    
    <figcaption><a href="#" rel="citation" data-toggle="popover" data-content="Cro0016.
    2009. Mallard2.jpg, Wikimedia Commons, accessed 13 April 2016.">Image 1</a> - A 
    duck</figcaption>
    
    </figure>

To see this code in action, go to this [example code page](https://msu-anthropology.github.io/daea-fs16/wiki/figure-code.html).