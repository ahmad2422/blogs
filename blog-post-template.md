---
title: "Blog Post Template"
menu_order: 3
post_status: draft
post_excerpt: "Excerpt"
post_date: "2025-08-08"
comment_status: open
featured_image: _images/devops.png

# Categories and tags are assigned via the taxonomy block using slugs
taxonomy:
  category:
    - tutorials
    - wordpress
  post_tag:
    - markdown
    - workflow

# Any extra key value pairs go in custom_fields
custom_fields:
  reading_time: "7 min"
  canonical_url: "https://example.com/blog-post"
---

# H1 Heading
Intro paragraph. This post shows all common content types that render correctly in WordPress when published via Git it Write.

## H2 Heading
Inline code like `npm run build` and a link to a **relative post** such as `./faq.md` will be converted to the correct site URL on publish. See also an **absolute repo link** like `/guide/doc1.md`.  

### H3 Heading
Bulleted list:
- Markdown files must end with `.md`
- Use standard file names for clean slugs
- Keep images inside the `_images` folder

Numbered list:
1. Write content locally
2. Commit to GitHub
3. Trigger publish from the plugin or wait for the webhook

#### H4 Heading
Blockquote:
> Git it Write lets you keep content in Git while publishing to WordPress.

##### H5 Heading
An image embedded between content. Place the file under `_images` and reference it with a leading slash so the plugin uploads and rewrites it.

![Architecture overview](/_images/devops.png "High level flow")

###### H6 Heading
JavaScript code block:

###### H6: HTML allowed

<section id="example">
  <h2>Sample Section</h2>
  <p>This HTML is included in the Markdown and will render in the post.</p>
  <button type="button" onclick="alert('Hello!')">Click me</button>
</section>


```js
// Minimal client side example embedded in markdown
function greet(name) {
  const msg = `Hello, ${name}!`;
  console.log(msg);
  return msg;
}
greet("my name");
