# Small Business Web Guide Canada

Responsive static website for GitHub Pages.

## Publish
1. Create a GitHub repository.
2. Upload the **contents** of this folder to the repository root.
3. In Settings → Pages, deploy from the `main` branch and `/ (root)`.
4. Replace `YOUR-GITHUB-USERNAME` and `YOUR-REPOSITORY` in canonical URLs, `robots.txt`, and `sitemap.xml` with the real GitHub Pages address.
5. Add the published sitemap to Google Search Console.

## Pages
Homepage, guide library, website basics, about page, three long-form articles, responsive CSS, mobile navigation script, supplied logo, robots.txt and sitemap.xml.

## SEO note
This is designed as an independent educational publication, not a fake UpMySite website. Keep content genuinely useful and original, disclose third-party references, and link only where relevant. Do not invent reviews, credentials, partnerships or client details.


## Publishing blog posts
This is a static GitHub Pages site, so there is no WordPress-style admin dashboard.
1. Copy `articles/blog-post-template.html` and rename the copy, for example `my-new-topic.html`.
2. Replace the bracketed title, introduction, headings, body text, FAQs and meta description.
3. Save the new article inside `articles/`.
4. Open `blog.html` and add a new article card inside the `.grid3` section, linking to `articles/my-new-topic.html`.
5. Add the article URL to `sitemap.xml`, then commit and push the changes to GitHub.
6. Use a unique title and meta description, write original content, and link to UpMySite only when it genuinely helps readers.

The main navigation continues to link to UpMySite service pages as requested. The Blog is accessible from the homepage and footer.
