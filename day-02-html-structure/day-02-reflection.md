
Day 02 Reflection

* Issue

My profile image was not loading on the webpage.

* Cause
I used the `<image>` tag instead of the correct HTML `<img>` tag and used an incorrect image path.

* Fix
I changed `<image>` to `<img>` and used the correct relative path: `images/image.png`.

# Day 02 Reflection

 1. What is the difference between an HTML tag, an element, and an attribute?

An HTML tag is written inside angle brackets, like `<p>`. An element includes the opening tag, content, and closing tag. An attribute provides extra information, like `href` in a link.

 2. When should you use an ordered list instead of an unordered list?

We use an ordered list (`<ol>`) when items need to follow a specific order or sequence. We use an unordered list (`<ul>`) when the order does not matter.

 3. Why does an informative image need alt text?

Alt text describes the image. It helps screen readers explain the image to visually impaired users and provides information if the image cannot load.

 4. What did you observe when you broke and then fixed an internal link?

When I used an incorrect link target, clicking the link did not take me to the correct section. After fixing the `href` and matching it with the section's `id`, the link worked correctly.
