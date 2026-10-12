# Lab 1 — Part D answers

Write at least 2 full sentences under each "Your answer:" line, in your own
words. Don't delete or change the question lines.

## Q1. What is the difference between `<ol>` and `<ul>`? Give one example of when you would use each.

Your answer:
 <ol> means Ordered List.
  Displays items in a numbered or lettered sequence (1, 2, 3… or A, B, C…).  
  Used when the order of items matters.  

<ul> means Unordered List
  Displays items with bullet points (●, ○, etc.).  
  Used when the order doesn’t matter, just a collection of items.  
 Examples:
- Using <ol> (Ordered List)  
  Example: Steps in a recipe  
  html
  <ol>
    <li>Preheat the oven.</li>
    <li>Mix the ingredients.</li>
    <li>Bake for 30 minutes.</li>
  </ol>
  

Using <ul> Unordered List  
  Example: Grocery shopping list  
  html
  <ul>
    <li>Milk</li>
    <li>Bread</li>
    <li>Eggs</li>
  </ul>


## Q2. Why must every `<img>` have an `alt` attribute? Who uses it?

Your answer:  The alt attribute provides alternative text that describes an image if it fails to load on the screen. It is primarily used by screen readers to assist visually impaired users in understanding the image content, and by search engine crawlers for SEO indexing. Additionally, it helps general users understand what the image was supposed to show when internet connections are slow.

## Q3. Your page links to `hobby.html` and to `https://...`. What is the difference between a relative link and an absolute link?

Your answer: A relative link points to a file or page within the same repository or server using its path relative to the current file, such as hobby.html. Conversely, an absolute link provides the full web address including the protocol, such as https://google.com, to point to a page anywhere on the internet. Relative links are best for linking local files in a website project, while absolute links are necessary for connecting to external domain websites.
