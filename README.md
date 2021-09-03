# introduction-to-html
### Styling Text
The em tag emphasizes text, while the strong tag highlights important text.
- The em tag will generally render as italic emphasis.
- The strong will generally render as bold emphasis.  
```html
  <p><strong>The Nile River</strong> is the <em>longest</em> river in the world, 
  measuring over 6,850 kilometers long (approximately 4,260 miles).</p>
```
### Line Breaks
```html
<p>The Nile River is the longest river <br> in the world, measuring over 6,850 <br> 
kilometers long (approximately 4,260 <br> miles).</p>
```
The Nile River is the longest river<br>in the world, measuring over 6,850<br>kilometers long (approximately 4,260<br>miles).
### Unordered Lists
```html
<ul>
  <li>Limes</li>
  <li>Tortillas</li>
  <li>Chicken</li>
</ul>
```
In the example above, the list was created using the ul tag and all individual list items were added using li tags.<br>
The output will look like this:
- Limes
- Tortillas
- Chicken
### Ordered Lists
```html
<ol>
  <li>Preheat the oven to 350 degrees.</li>
  <li>Mix whole wheat flour, baking soda, and salt.</li>
  <li>Cream the butter, sugar in separate bowl.</li>
  <li>Add eggs and vanilla extract to bowl.</li>
</ol>
```
The output will look like this:

1. Preheat the oven to 350 degrees.
2. Mix whole wheat flour, baking soda, and salt.
3. Cream the butter, sugar in separate bowl.
4. Add eggs and vanilla extract to bowl.
### Images
```html
<img src="image-location.jpg" />
```
The img tag has a required attribute called src. The src attribute must be set to the image’s source, or the location of the image.
### Image Alts
The value of alt should be a description of the image.
```html
<img src="#" alt="A field of yellow sunflowers" />
```
### Videos
Unlike the img tag however, the video element requires an opening and a closing tag.
```html
<video src="myVideo.mp4" width="320" height="240" controls>
  Video not supported
</video>
```
