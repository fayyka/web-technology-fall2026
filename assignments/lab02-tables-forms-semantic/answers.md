# Lab 2 — Part D answers

Write at least 2 full sentences under each "Your answer:" line, in your own
words. Don't delete or change the question lines.

## Q1. In your form, why must a `<label>`'s `for` match its `<input>`'s `id`? What goes wrong if they don't match?

Your answer: they must match because the `for` in `<label>` links the label to the specific `<input>` with the same `id`. This makes clicking the label focus or activate the input, and improves accessibility for screen readers.  

if they don't match the label won’t be connected to the input. Clicking the label won’t focus the field, and assistive technologies won’t know which input the label describes.  


## Q2. You used both `<section>` and `<article>`. What is the difference? Why did the hackathon story become an `<article>`?

Your answer: - **Difference:**  
  - <section> groups related content under a theme or topic.  
  - <article> is for self‑contained content that could stand alone (like a story, blog post, or news item).  

- **Hackathon story as `<article>`:**  
  Because it’s a complete, independent piece of content that makes sense on its own, not just a subsection of a larger topic.

## Q3. What is the difference between `<th>` and `<td>`? Why should a table never be used to lay out a whole page?

Your answer: - **Difference:**  
  - <th> = **Table Header cell** → defines a heading for a column or row, usually bold and centered.  
  - <td> = **Table Data cell** → holds the actual content (numbers, text, etc.) inside the table.  

- **Why not use tables for whole page layout:**  
  - Tables are meant for **tabular data**, not design.  
  - Using them for layout makes pages harder to maintain, less accessible, and not responsive on modern devices.  

