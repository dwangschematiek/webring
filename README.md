# dwangschematiek webring

This repo contains the tiny source for this tiny little project :)

Find it at [dwangschematiek.nl/webring/](https://dwangschematiek.nl/webring/).

## Navigation bar

If you are part of the webring, you can design your own navigation.
Here is the one I use.
Use it as is or as a starting point.

```html
<div id="webring">
    <span>&#8636; <a href="#">previous site name</a></span>
    <p>this site is a part of the &#9825; <a href="https://dwangschematiek.nl/webring/" target="_blank">dwangschematiek webring</a> &#9825;</p>
    <span><a href="#">next site name</a> &#8640;</span>
</div>
```

```css
#webring {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: baseline;
}
```

---

Created by ma3ke & friends.

_Be cute do websites._
