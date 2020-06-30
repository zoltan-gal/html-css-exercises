# Best practices

Read these [best practicies](https://blog.tbhcreative.com/2015/08/10-best-practices-in-html.html) that you should follow and apply onto your code.

## Indentation

Ensure that your HTML, JavaScript, and CSS is __indented neatly__:
 - Indentation describes how groups of related lines of code a horizontally-aligned.
 - This improved readability and helps other developers to contribute to your code.

## 
https://blog.tbhcreative.com/2015/08/10-best-practices-in-html.html

# Validate your HTML content

Ensure that your markup is valid HTML5:
 - You should precede the `<html>` tag with `<!DOCTYPE html>`, which tells the browser that this is a HTML5 document.
 - You can paste your markup into the [W3 Validator](https://validator.w3.org/) to check your HTML.

Utilise semantic elements where possible
E.g. use the <nav> element  for your navigation bar, the <article> element  for any reusable article text etc.

This will benefit screen reader users, as well as allowing search engine crawlers to understand your content more easily (this is known as Search Engine Optimisation, or SEO)

# Accessibility

Accessibility describes the usability of your application for able-bodied users with limited hardware or infrastructure (e.g. restricted mobile bandwidth),
or for users with physical or cognitive impairments, such as the visually-impaired. Developing accessible software allows many people to use your project,
and in many countries, it’s a legal necessity.

Recommendations:
 1. Ensure that colours have enough __contrast__. This will allow those who are colour blind to easily read the content of your application.
    E.g. don’t use green font on a dark green background.
 2. Use alt attributes for images, so that screen readers can describe them to the visually-impaired.
 3. Write semantic HTML (covered below) to ensure high compatibility with existing and emerging screen readers.

Links:
 - https://alistapart.com/article/wiwa/
 - https://youtu.be/o4xHfi4t9S0
