# Etchv blog

The posts behind [etchv.com/blog](https://etchv.com/blog), written in MDX.

- `posts/<slug>.mdx`: one post per file. The filename is the slug and the address on etchv.com.
- `authors.json`: bylines. Whistler is the pen name of Etchv's founder; Etchv is the company.
- `series.json`: recurring series, such as the weekly Leak Ledger.
- `images/<slug>/`: the images each post uses.
- `link-policy.json`: which outbound hosts a post may link to.

A post's frontmatter takes `title`, `description`, `date`, `author` and `category`, and optionally `updated`, `tags`, `series`, `image`, `cta`, `draft`, `canonical` and `redirect`. `draft: true` keeps the post and its image folder private.

See `LICENSE.md` for how you may reuse the posts.
