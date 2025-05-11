# Entry 6
##### 5/5/25

## Content

My MVP is a website that talks about animation technology. A big challenge I faced was getting the mobile navigation menu `burger icon dropdown` to function correctly using the [Bulma CSS framework.](https://bulma.io/documentation/) At first the burger icon would appear on smaller screens as expected, but clicking it didn't toggle the menu visibility. I assumed Bulma would handle it automatically. I only added a click event to the burger icon that toggled the is-active class on the menu. However, I realized I also needed a way to close the menu after navigation. Without it the dropdown would stay open and block the page even after users clicked a link. I added `event listeners` to both the close button and the individual navbar links to solve this. Now the menu closes smoothly whether the user clicks the close icon or selects a page link.

Here is the final code:


[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
