## Dans HTML/CSS Framework Used @ http://www.emerge.co.uk

This framework is designed to be used as a quick tool to start the development of a web project. 
Folders and base files are included for speed.
The folder structure is as :

* root 
	* css
	* js
		* vendor


Contains a folder GRIDS, this shows the entire grid for example.


#### CSS

The framework is built using the SCSS compiler, Run the sass --watch command on styles.css. 
You'll see that the SCSS files are seperated into different files. These allow us to seperate styles by their functions.

Define color variables in the _global_colours.scss 

Download Scout app if you're unfamiliar with SCSS http://mhs.github.io/scout-app/


#### Images

Use sprites where possible, We've already got _sprite_icons.scss set up for doing this.
Use JPEGs where possible.


#### HTML

Please use tab indentation, set to 4 spaces.


#### GRID

The site is based on a 12 column grid, main definitions are :

##### container 
defines sections of content, think of header, main, footer.

##### row
defines a central column of 960px's width;

##### col-xxx 
defines the grid columns in a row, they must add up to twelve. Last column in a row must add "last" class.


###### Example HTML Markup

``` 
    <div class="container">
        <div class="row">
            <div class="col-twelve">
                <h1>Emerge CSS Boilerplate</h1>
            </div><!-- twelve --> 
        </div><!-- row -->
    </div>

```




