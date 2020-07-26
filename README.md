## Welcome to 3rd Ringwood's Website

You can use the [editor on GitHub](https://github.com/3rdRingwood/3rdringwood.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you "commit" to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
# Header 1

## Header 2

### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Images

All images are stored in [assets/img/](assets/img/), to link them into a page use their file path with a slash at the beginning in this special syntax: `![](/assets/img/hall/hall1.png)`.

If images come out too big (by default they'll try and fill the whole width), more syntax is needed; a width of `300px` is normally about right, e.g.

```
![](/assets/img/scouts/Beaver_RGB_multi.png){:width="300px"}
```

### Pages

To edit the page `http://ringwoodscouts.co.uk/explorers/`, you would open [explorers/index.md](explorers/index.md), click on the pencil icon on the right just above the content, make and then save your changes.

Each page starts with "frontmatter" (the part surrounded by `---`s) and then is followed by Markdown (see above). The frontmatter has the following settings:

- `title` - this is what's used in the browser title bar, as a title at the top of the page, and in the Google (or other search engine) results for that page
- `short_title` - this is the name of the page to be shown in the link list at the top; it lets you choose a shorter name if you want. If not specified, we'll use 'title' instead
- `group: navigation` - always use this
- `order` - this value sets the order the links will appear in the list at the top; a lower number moves the link to the left. We've numbered them in tens to allow you to add new pages in the middle of existing links (e.g. to create a page between Beavers (order: 20) and Cubs (order: 30) you'd give the new page order 25).

### Documentation

Check out the [GitHub Pages documentation](https://help.github.com/categories/github-pages-basics/).
