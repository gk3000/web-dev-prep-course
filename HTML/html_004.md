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

How browser will show this ↓↓↓

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

## Semantic meaning 

When we are talking about HTML and some elements we mention a phrase *semantic meaning*. What is it? 

Most of the elements in HTML have a meaning to the browser in a way that browser (and search engines parsing your pages) will know what type of content you have by reading the HTML elements. 

If a browser sees `<p>` tag it will know that it is a paragraph. If it will see `<h1>` tag it will know it is a heading of the first level. And so on. 

With containers we also have some which do have a semantic meaning:

`<section>`, `<article>` group together content focused on the same topic

`<footer>` sits in the end of a page and contains all the secondary footer content like information about the author of the section, copyright data or links to related documents

`<header>` represents introductory content, typically a group of introductory or navigational aids. It may contain some heading elements but also a logo, a search form, an author name, and other elements

`<aside>` HTML element represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes

`<main>` represents the dominant content of the body of a document, the main content of your page or a section of it

`<nav>` represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents


> `<div>` element doesn't have any semantic meaning, it tells browser nothing about what kind of content it has. So while we can layout the whole page with divs only, it would hurt our SEO. Let's try to use elements with semantic meaning where appropriate and use div just for the sake of CSS or to group elements for other purposes without changing the semantic structure of our pages.

## span

`<span>` element is a generic inline container for text content and it doesn't represent anything, we usually use it for the CSS to target part of text or if we want to add some attributes to part of our text. 

For example:

```html
<p>Paragraphs to wrap text paragraph inside but <span>part of it should be special and we can use span to do so</span> without affecting whole paragraph.</p>
```

How browser will show this ↓↓↓

<p>Paragraphs to wrap text paragraph inside but <span>part of it should be special and we can use span to do so</span> without affecting whole paragraph.</p>

So while we can not see any difference at the moment we now have a way to only select "part of it should be special and we can use span to do so" fragment within our paragraph without changing the semantic structure of it. 