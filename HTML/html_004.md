# HTML containers

Same as in real life sometimes we want to group several elements together based either on the fact that they are focused on the same topic or simply to create structure (later it will be used by CSS...). 

For that we have several container tags in HTML. Let's see how they work. 


## div 

It is the most universal container without any semantic meaning, it allows us to group elements into one single unit. Anything which goes between opening and closing "div" tags would be children to this element. 

> Yes, in HTML we use terms like *parent*, *child*, *sibling* because the structure of HTML reminds us of a family tree...


```html
<div>
	<h1>About bananas</h1>
	<p>Not only do bananas provide a slew of health benefits, but they are one of the world's most popular fruits. Global banana exports reached about 24.5 million tons (22.2 million metric tons) in 2020 according to a preliminary report by the United Nations.</p>
	<img src="https://raw.githubusercontent.com/gk3000/artsy_bananas/main/artsy_bananas_00.png" alt="Artsy banana" />
	<ul>
		<li>Bananas may have been the world's first cultivated fruit. Archaeologists have found evidence of banana cultivation in New Guinea as far back as 8000 B.C. </li>
		<li>Though the name doesn't imply as much, bananas are considered berries. (Meanwhile, the strawberry, raspberry and blackberry are not true berries in the botanical sense, because they don't have the three required fleshy layers of a berry, Live Science previously reported.) </li>
		<li>The banana plant is classified as an arborescent (tree-like) perennial herb.</li>
		<li>A bunch of bananas is called a hand; a single banana is a finger.</li>
		<li> There are almost 1,000 varieties of bananas</li>
	</ul>
</div>
```

How browser will show this:

<div>
	<h1>About bananas</h1>
	<p>Not only do bananas provide a slew of health benefits, but they are one of the world's most popular fruits. Global banana exports reached about 24.5 million tons (22.2 million metric tons) in 2020 according to a preliminary report by the United Nations.</p>
	<img src="https://raw.githubusercontent.com/gk3000/artsy_bananas/main/artsy_bananas_00.png" alt="Artsy banana" />
	<ul>
		<li>Bananas may have been the world's first cultivated fruit. Archaeologists have found evidence of banana cultivation in New Guinea as far back as 8000 B.C. </li>
		<li>Though the name doesn't imply as much, bananas are considered berries. (Meanwhile, the strawberry, raspberry and blackberry are not true berries in the botanical sense, because they don't have the three required fleshy layers of a berry, Live Science previously reported.) </li>
		<li>The banana plant is classified as an arborescent (tree-like) perennial herb.</li>
		<li>A bunch of bananas is called a hand; a single banana is a finger.</li>
		<li> There are almost 1,000 varieties of bananas</li>
	</ul>
</div>

---


```html
<p>Paragraphs to wrap text paragraph inside.</p>
```

How browser will show this:

<p>Paragraphs to wrap text paragraph inside.</p>

---

```html
<ul>
<li>unordered list with the list items inside</li>
<li>will be rendered with the bullets by default</li>
<li>used to render content which is a list of items</li>
</ul>
```

How browser will show this:

<ul>
	<li>unordered list with the list items inside</li>
	<li>will be rendered with the bullets by default</li>
	<li>used to render content which is a list of items</li>
</ul>

---

```html
<ol>
<li>this is an ordered list</li>
<li>every element in it will have it's own number</li>
<li>it could be a list of steps to follow or any other numbered items</li>
</ol>
```
How browser will show this:

<ol>
	<li>this is an ordered list</li>
	<li>every element in it will have it's own number</li>
	<li>it could be a list of steps to follow or any other numbered items</li>
</ol>

---


## Images

To render an image with HTML we need to use "img" tag:

```html
<img src="https://raw.githubusercontent.com/gk3000/artsy_bananas/main/artsy_bananas_00.png" alt="Artsy banana" />
```

How browser will show this:

<img src="https://raw.githubusercontent.com/gk3000/artsy_bananas/main/artsy_bananas_00.png" alt="Artsy banana" />

First thing you will notice about "img" element is that it is *self-closing*, there are no opening and closing tags but one tag which we open with `<` and close with `/>`.

Another thing we see here is that element has 2 *attributes* inside: `src` and `alt`. 

`src` attribute points to the URL or address of image we want to render and `alt` attribute contains the description of the image which is used if image file is not available or for the screen readers. For the reasons of accessibility it is obligatory to add `alt` attribute to the images we render. 

---

## Buttons 

To add a button we will use a "button" element like so:

```html
<button>Click me</button>
``` 

This snippet will render a button with the label "Click me"

How browser will show this:

<button>Click me</button>

---

> Take a look at [this CodePen](https://codepen.io/GK3000/pen/rNvMoWY) to see how those elements are rendering content.