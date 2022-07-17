# Frontend Mentor - Product preview card component

<h5 align="center">Assalam U Alaikum, well I don't like writing descriptions but Readme is fine</h5>
<hr>

## The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

## Snapshots

![](img/screenshot-desktop.png)
![](img/screenshot-mobile.png)

## What I learned?

I already knew about how to do <strike><del>this</del></strike> but forgot about it so by researching I got to know about the <strong>strike</strong> tag it's a fallback as <strong>del</strong> isn't visible in every browser

```html
<p class="old-price">
  <strike>
    <del>$169.99</del>
  </strike>
</p>
```

but after reading my report I think it's much better to use css

```css
  .old-price {
    text-decoration: line-through;
  }
```

This was the code that finally like damn finally worked and the mobile version was good and happy by just adding auto to center the box (already knew this too but forgot to use it) :]

```css
.box {
  margin: 1em auto;
}
```

I'm damn glad to learn how to add code snippets!!! (from the template read me file)

````html
```html
<p>Your Code</p>
```
````

## Useful resources

[How to take a screenshot?](https://www.makeuseof.com/how-to-full-page-screenshot-chrome-firefox/) - I didn't knew how to take a webpage snapshot so yeah

[Slash through the text?](https://www.w3schools.com/cssref/pr_text_text-decoration.asp) - I also forgot how to slash (line-through) the text

## Thoughts

It was easy but still there were some places where I got stuck (centering & responsiveness) so this helped me narrow down some of my weak points and also forced me to try different ways to style things. Making mobile friendly websites are kinda difficult but I'll be glad to continue doing it

## Author

- Twitter - [@MaskeyDude](https://www.twitter.com/MaskeyDude)
- Frontend Mentor - [@MaskeyDude](https://www.frontendmentor.io/profile/MaskeyDude)

<hr>
<div align="center">
<a href="https://maskeydude.github.io/product-preview-card-component/" target="_blank">Preview</a>
</div>