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

# FORMS <br>
Form element - is used to create an HTML form for user input <br>
```<form </form>``` <br>

Form Action - specifies where to send form data when submitted <br>
```action="URL"```<br>

Input element - allows you several ways to collect data from a web form, <br>
    these are self closing and do not need closing tags <br>
    ```<input```<br>

Type element - allows different kinds of inputs such as password field, reset button etc <br>
```type="text"``` <br>

Name attribute - is assigned to represent the data being submitted, like a variable <br>
```name="catphotourl"```<br>

Placeholder - is used to give people a hint at what information is being gathered <br>
```placeholder="cat photo URL"```<br>

Required attribute - is used to prevent users from submitting forms without required information <br>
```required``` <br>

Button element - Creates a clickable button <br>
```<button>Click here</button>``` <br>

Add radio buttons to forms <br>
```<input type="radio> TEXT``` <br>

Label elements - are used to help associate text for an input element with the input element itself <br>
```<label><input type="radio"> cat </label>``` <br>

ID attribute - is used to identify specific HTML elements, each ID must be unique for the entire page <br>
```id="indoor"``` <br>

To allow one radio button to be selected automagically and deselect the other you must use the Name attribute with the same value
```name="indoor-outdoor" indoor-outdoor are names of 2 radio buttons```<br>

If you select the Indoor radio button and submit the form, the form data for the button is based on its name and value attributes. Since your radio buttons do not have a value attribute, the form data will include indoor-outdoor=on, which is not useful when you have multiple buttons. <br>
```value="name of ID"``` <br>

The fieldset element is used to group related inputs and labels together in a web form. fieldset elements are block-level elements, meaning that they appear on a new line. <br>
```<fieldset> </fieldset>```

Legend element acts as a caption for the content in the fieldset element. Gives context <br>
```<legend> </legend>```

Checkboxes are created using: <br>
```<input type="checkbox"> Tacos```

There's another way to associate an input element's text with the element itself. You can nest the text within a label element and add a for attribute with the same value as the input element's id attribute. <br>
```<input id="tacos" type="checkbox"> <label for="tacos">Tacos</label>```

Like radio buttons, form data for selected checkboxes are name / value attribute pairs. While the value attribute is optional, it's best practice to include it with any checkboxes or radio buttons on the page. <br>
```<input id="energetic" type="checkbox" value="energetic" name="personality"> <label for="energetic"> Energetic</label>```

In order to make a checkbox checked or radio button selected by default, you need to add the checked attribute to it. There's no need to set a value to the checked attribute. Instead, just add the word checked to the input element, making sure there is space between it and other attributes. <br>
```<label><input id="indoor" type="radio" name="indoor-outdoor" checked value="indoor"> Indoor</label>```

The head element is a container for metadata and is placed between the html and body tag <br>
```<head>``` <br>
```  <title> CatPhotoApp </title>``` <br>
```</head>``` <br>

All pages should begin with ```<!DOCTYPE html>```. This special string is known as a declaration and ensures the browser tries to meet industry-wide specifications. <br>
Add this declaration as the first line of the code. <br>

You can set browser behavior by adding self-closing meta elements in the head. Here's an example: <br>
````<meta attribute="value">`` <br>

