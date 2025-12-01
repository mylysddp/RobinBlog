# RobinBlog
我的个人Blog内容，在当前blog目录下生成对应Markdown文档，就会在 https://www.plok.sh/ 中生成对应的一篇blog。以下内容是我让Chatgpt帮我根据我提供的 产品落地页的url，生成对应Markdown文档。后续可以复用这个Prompt

# Prompt guide for generating Plok-compatible blog posts

Use this checklist-style prompt when asking the agent to generate new Markdown posts for the blog. It distills the prior requirements so you can swap in a new product name and homepage link.

## Quick prompt template
Copy, paste, and replace bracketed items:

```
Please generate Plok-friendly blog assets in the existing `blog/` folder:
1) Keep the blog header and footer patterns consistent with the existing files.
2) Create a new post with a descriptive filename (no dates), e.g., `what-is-[product].md`.
3) Write the post in **English only**.
4) Follow https://www.plok.sh/guide front matter: include `title`, `published_at` (use today’s date), and any other required keys.
5) Link to the product homepage: [product_homepage_url].
6) Add helpful visuals from Unsplash (or similar) to break up text and beautify the Markdown.
7) Keep content concise, scannable, and aligned with the product’s value.
```

## Detailed checklist
- **Scope**: Work inside `blog/` so content stays organized.
- **Filenames**: Use descriptive words instead of date prefixes (e.g., `why-[product]-matters.md`).
- **Language**: All content should be English.
- **Front matter**:
  - `published_at` should be the current date when the file is generated.
  - Include `title` and any keys required by the Plok guide.
- **Links**: Always include a visible link to the product’s official homepage.
- **Design touches**: Add relevant images from Unsplash (or similar) and mix in bullets, callouts, or short sections so the post isn’t only text.
- **Footer/Header alignment**: Keep tone and calls-to-action aligned with existing `blog.header.md` and `blog.footer.md`.

Use this guide as a starting prompt whenever you spin up a new product post.
