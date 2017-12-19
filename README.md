# star-wars-the-last-parallax
We're obsessed with Star Wars: The Last Jedi. A LEGO Darth Vader hangs out between desks; we play the soundtrack over our office speakers; and for our Christmas party, we saw The Last Jedi in theaters. We're also obsessed enough to write a Star Wars-themed post on adding parallax with multiple backgrounds to your website using [jQuery Parallax by Ian Lunn](http://flesler.blogspot.com/2007/10/jqueryscrollto.html). Instead of your run of the mill stock photos, our example is filled with BB-8, X-Wings, ATT Walkers, and Master Luke Skywalker as backgrounds. And don't worry: this tutorial is free of spoilers!

## Tutorial

For detailed instruction's, view Solodev's [Design a Star Wars Background, We Must](https://www.solodev.com/blog/web-design/how-to-make-a-star-wars-parallax-background.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/pjevvaea/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div id="intro">
   <div class="story">
      <div class="float-left">
         <h2>Star Wars: A New Parallax</h2>
         <p><p>In celebration of &quot;Star Wars: The Last Jedi&quot;, the Solodev team decided to write a Star Wars themed post on adding parallax with multiple backgrounds to your website using jQuery. Instead of your run of the mill stock photos, our example is filled with Jedis and the Force as backgrounds. </p> 
      </div>
   </div>
</div>
<div id="second">
   <div class="story">
      <div class="bg"></div>
      <div class="float-right">
         <h2>The Parallax Strikes Back</h2>
         <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean nibh erat, sagittis sit amet congue at, aliquam eu libero. Integer molestie, turpis vel ultrices facilisis, nisi mauris sollicitudin mauris, volutpat elementum enim urna eget odio.</p> 
         <p>Donec egestas aliquet facilisis. Nunc eu nunc eget neque ornare fringilla. Nam vel sodales lectus. Nulla in pellentesque eros. Donec ultricies, enim vitae varius cursus, risus mauris iaculis neque, euismod sollicitudin metus erat vitae sapien. Sed pulvinar.</p>
      </div>
   </div>
</div>
<div id="third">
   <div class="story">
      <div class="float-left">
		<h2>The Return of Parallax</h2>
         <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean nibh erat, sagittis sit amet congue at, aliquam eu libero. Integer molestie, turpis vel ultrices facilisis, nisi mauris sollicitudin mauris, volutpat elementum enim urna eget odio.</p> 
         <p>Donec egestas aliquet facilisis. Nunc eu nunc eget neque ornare fringilla. Nam vel sodales lectus. Nulla in pellentesque eros. Donec ultricies, enim vitae varius cursus, risus mauris iaculis neque, euismod sollicitudin metus erat vitae sapien. Sed pulvinar.</p>
      </div>
   </div>
</div>
```

## CSS

All required CSS is in parallax.css

## JavaScript

All required JS is in parallax.js

## External Resources

This tutorial includes the following third party resources.

```
<link href="parallax.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-parallax/1.1.3/jquery-parallax-min.js"></script>
<script src="parallax.js"></script>
```

