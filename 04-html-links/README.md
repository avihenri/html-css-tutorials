# Lesson 4: HTML Links

## What Are HTML Links?

HTML links allow you to connect your webpage to other pages, websites, or resources. They are created using the `<a>` tag, also known as the anchor tag. Links are an essential part of the web, making it easy for users to navigate between pages and access additional information.

With HTML links, you can:
- Link to external websites.
- Navigate to other pages within your site.
- Direct users to specific sections on a page.

---

### Syntax:

```html
<a href="url">link text</a>
```

The anchor tag has a few attributes:

1. **href**: Required attribute, determining the link's destination
   - Example: `<a href="http://example.com">example.com</a>
2. **target**: Optional attribute, determines where to open the link. By default, links are open in current window/tab `_self`
   - Example: `<a href="http://example.com" target="_blank">example.com</a>
      - opens in a new window/tab
   - Example: `<a href="http://example.com" target="_parent">example.com</a>
      - opens in a the parent frame
   - Example: `<a href="http://example.com" target="_top">example.com</a>
      - opens in a the full body window
3. **title**: Optional attribute, provides extra information for tooltips

We can also link to an email address to open the user's default mail app:
```html
<a href="mailto:someone@example.com">Send email</a>
```

Links can take a relative path or an absolute path:
1. **relative path**: Is a local link to your application
   - Example: <a href="/04-html-links/example.html">HTML Links Example</a> <!-- / is the root of your application -->
   - Example: <a href="../03-html-text/example.html">HTML Text Example</a> <!-- ../ goes back a directory to reach a level up from where this tag is declared -->
2. **absolute**: Is a link to a full website with http:// or https://
   - Example: <a href="https://www.example.com/">Example website</a>

<!-- [Next Lesson: HTML ](../05-html-/README.md) -->