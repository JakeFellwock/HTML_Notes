# OKCoders
Repo for OKCoders Bootcamp

# HTML Notes:

Headers h1 - h6 <br>
```<h1> </h1> ```

Paragraph p-tag  
```<p> </p> ```

Main tag ( use to identify different content areas and improve SEO) <br>
```<main> </main> ```

Img tag (used to add image - self closing tag) <br> 
```<img> ```

HTML attributes inside an opening tag of an element controls the elements behavior such as src for source <br>
```<img src='https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg'>``` 

All img elements should have an alt attribute. This is used for screen readers to improve accessibility and shows text if an image is not able to load. <br>
```<img src='https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg' alt='A cat'> ```

A (anchor) element is used to link to another page <br>
```<a href='https://freecodecamp.org'></a> would link to freecodecamp.org```

Add text to links (text must be placed between opening and closing tags) <br>
```<a href="https://freecatphotoapp.com">link to cat pictures</a> ```

Turn any text into a link such as inside a p element <br>
```<p>See more <a href="https://freecatphotoapp.com">cat photos</a> in our gallery.</p> ```

Open links in a new tab by adding a Target attribute with the value of _blank <br>
```<p>See more <a href="https://freecatphotoapp.com" target="_blank">cat photos</a> in our gallery.</p> ```

Turn other elements into links by wrapping it in anchor tags (turns image into a link) <br>
```<a href="https://freecatphotoapp.com"> <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a> ```

Make use of section element to separate content <br>
```<section> </section>``` 

Create an unordered list (UL) <br>
``` <ul>```<br>
```     <li>Coffee</li>```<br>
```     <li>Tea</li>```<br>
```     <li>Milk</li>```<br>
``` </ul>```<br>

Figure element - defines a caption <br>
The figure tag specifies self-contained content, like illustrations, diagrams, photos, code listings, etc. <br>
```<figure>```<br>
```<img src="pic_trulli.jpg" alt="Trulli" style="width:100%">```<br>
```<figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>```<br>
```</figure>```<br>

Figcaption element is used to add a caption for the figure element <br>
```<figcaption>Cats love lasagna</figcaption>```

EM tag is used to define emphasized text, displayed as italics <br>
```<figcaption>Cats <em>love</em> lasagna </figcaption>``` 

Ordered Lists (OL) list items as numbered when displayed <br>
```<ol>```<br>
```     <li>thunder</li>``` <br>
```     <li>lightning</li>``` <br>
```     <li>catchow</li>``` <br>
```</ol>``` <br>

Strong element is used to indicate that some text is of strong importance or urgent <br>
```<strong>This text is important!</strong>```

FORMS <br>
Form element - is used to create an HTML form for user input ```<form </form>``` <br>
Form Action - specifies where to send form data when submitted ```action="URL"```<br>
Input element - allows you several ways to collect data from a web form, <br>
    these are self closing and do not need closing tags ```<input```<br>
Type element - allows different kinds of inputs such as password field, reset button etc ```type="text"``` <br>
Name attribute - is assigned to represent the data being submitted, like a variable ```name="catphotourl"```<br>
Placeholder - is used to give people a hint at what information is being gathered ```placeholder="cat photo URL"```<br>
Required attribute - is used to prevent users from submitting forms without required information ```required``` <br>
Button element - Creates a clickable button ```<button>Click here</button>``` <br>
Add radio buttons to forms ```<input type="radio> TEXT``` <br>
Label elements - are used to help associate text for an input element with the input element itself <br>
```<label><input type="radio"> cat </label>``` <br>
ID attribute - is used to identify specific HTML elements, each ID must be unique for the entire page ```id="indoor"``` <br>
To allow one radio button to be selected automagically and deselect the other you must use the Name attribute with the same value
```name="indoor-outdoor" indoor-outdoor are names of 2 radio buttons```
If you select the Indoor radio button and submit the form, the form data for the button is based on its name and value attributes. Since your radio buttons do not have a value attribute, the form data will include indoor-outdoor=on, which is not useful when you have multiple buttons. <br>
```value="name of ID"``` <br>
The fieldset element is used to group related inputs and labels together in a web form. fieldset elements are block-level elements, meaning that they appear on a new line. <br>
```<fieldset> </fieldset>```


