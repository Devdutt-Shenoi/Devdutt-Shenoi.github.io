# Devdutt.ga
### My Home Base on the inter webs.
_____
I don't use it much but this is my intergalactic garage, I sometimes update it with what important is happening in life and how I am doing the things tha I am.


## Links
* CSS file is saved as  [http://devdutt.ga/site.css](http://devdutt.ga/site.css).
* Images are also saved as such, in the [image](http://devdutt.ga/imgaes) folder.

## Header
The code used in the header is basically an image styled to be shaped 'D' within the linked CSS as:

```css
.header .logo img{
  border-radius: 1000px;
  border-radius: 0 200px 200px 0;
  -webkit-border-radius: 0 200px 200px 0;
}
```
Then there is the texts:
1. The name with a subscript to the blog.
2. Tag-line that points to another website.

**The code used in the header is :**

```html
<header class=header>
    <div class=row>
        <div class="columns small-12">
            <a href="http://devdutt.ga" class="logo" >
            <img alt="logo image" src="http://devdutt.ga/images/photo.jpg"> 
            <span>devdutt Shenoi</span> 
            </a>
            <a href="http://devdutt.ga/blog" class="radius super-script"> Blog </a>
            <p class=tagline>Co-founder & Developer @<a href="http://vimag.vv.si"> V!</a>
        </div>
    </div>
</header>
```
