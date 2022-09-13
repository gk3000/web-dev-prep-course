# Making your first page 

What? Already? 

Well... yes! We can already make our first page with HTML. 

> Remember, HTML is only the structure of the page, it doesn't and shouldn't control the visual design, we are going to make it with CSS! 

Go to codepen.com, sign up if you want to save your work, and create new pen: https://codepen.io/pen/

In the left panel you can write your HTML which you will see in the render part of the screen. 

Let's create a personal webpage describing a person, duh, with several parts of content: 

Name 
Image
Couple of paragraphs about a person 
Hobbies of this person 

Looks simple, isn't it? 

```html
<main>
  
  <h1>Ash Riley</h1>
  <img src="https://thispersondoesnotexist.com/image" alt="Ash's portrait"/>
  
  <h2>About me</h2>
  <p>Hi, I'm Ash. I am only starting learning HTML and this is my first ever webpage.</p>
  <p>For now it only contains HTML without any styling but that's ok, I will learn CSS pretty soon.</p>
  
  <section>
    <h1>Things I like to do:</h1>
   <ul>
    <li>Reading books</li>
     <li>Riding my motorbike</li>
     <li>Eating breakfast</li>
     <li>Observing life around me</li>
  </ul>   
  </section>

</main>
```

How browser will show this ↓↓↓

<main>
  
  <h1>Ash Riley</h1>
  <img src="https://thispersondoesnotexist.com/image" alt="Ash's portrait"/>
  
  <h2>About me</h2>
  <p>Hi, I'm Ash. I am only starting learning HTML and this is my first ever webpage.</p>
  <p>For now it only contains HTML without any styling but that's ok, I will learn CSS pretty soon.</p>
  
  <section>
    <h1>Things I like to do:</h1>
   <ul>
    <li>Reading books</li>
     <li>Riding my motorbike</li>
     <li>Eating breakfast</li>
     <li>Observing life around me</li>
  </ul>   
  </section>

</main>

[CodePen with the code](https://codepen.io/GK3000/pen/xxjEBQX)