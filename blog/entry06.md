# Entry 6
##### 5/5/25

## Content

My MVP is a website that talks about animation technology. A big challenge I faced was getting the mobile navigation menu `burger icon dropdown` to function correctly using the [Bulma CSS framework.](https://bulma.io/documentation/) At first the burger icon would appear on smaller screens as expected, but clicking it didn't toggle the menu visibility. I assumed Bulma would handle it automatically. I only added a click event to the burger icon that toggled the is-active class on the menu. However, I realized I also needed a way to close the menu after navigation. Without it the dropdown would stay open and block the page even after users clicked a link. I added `event listeners` to both the close button and the individual navbar links to solve this. Now the menu closes smoothly whether the user clicks the close icon or selects a page link.

Here is the final code:

```
  <script>
    document.addEventListener('DOMContentLoaded', () => {
      const burger = document.querySelector('.navbar-burger');
      const menu = document.getElementById('mobileMenu');
      const closeBtn = document.getElementById('closeMenu');
      const links = menu.querySelectorAll('.navbar-item');

      burger.addEventListener('click', () => {
        menu.classList.add('is-active');
      });

      closeBtn.addEventListener('click', () => {
        menu.classList.remove('is-active');
      });

      links.forEach(link => {
        link.addEventListener('click', () => {
          menu.classList.remove('is-active');
        });
      });
    });
  </script>
```

## Takeaway
I learned how to manually add JavaScript behavior for components that Bulma styles but doesn’t handle. And the value of testing across devices early, mobile issues are easier to fix when caught early in the process.

## EDP

In the engineering design process I am at the improve as need step because I have finished everything required for the MVP now I just need to fix any issues and add beyond MVP.

## Skills

While working on my MVP I've been developing skills that will help me outside of this project too. One of those is problem decomposition. When something feels overwhelming I’ve learned to break the task into smaller parts to complete. Another skill I’ve been getting better at is debugging. I read errors carefully, then tinker, and watch the result. It has helped me get more comfortable with things not working the first time. I’ve learned to stay patient.

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
