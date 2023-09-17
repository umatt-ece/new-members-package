# Intro to Markdown
Just need a quick refresher? Check out this [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/).

## What is Markdown?
> "_Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents_"

Basically, markdown is kinda like a coding language that allows you to add formatting (ie. _italics_, **boldface**, etc...) to a document. It also allows you to add other elements such as headings, links, code snippets, tables, and more to what otherwise would be just plain old text. Don't believe me? Take a look at the source code for this document, and you'll see that all the formatting is done with just regular characters such as #, *, _, and >.

## Why should I care?
1. Markdown is simple and easy to learn (if you don't agree you can fight me).
2. Markdown is "portable", in that it doesn't require any fancy software or proprietary file formats. Plus, even not rendered Markdown is designed to look good and be readable just a plain-text (just try reading an un-rendered HTML file, and you'll see what I mean). 
3. Markdown rendering is supported by most browsers, code editors, even some command line tools. Software like Discord, Obsidian, or Jira all support the use of Markdown out of the box.
4. As a software developer, Markdown makes it extremely easy to integrate sections of code into a document (if you've every tried added code into a Word document, you understand the struggle).

That aside, the biggest reason I recommend you be at least familiar with Markdown is because: GitHub. GitHub provides extensive support of Markdown in its project management features. Knowing a bit of basic syntax will help you look more professional and save you time.

To get yourself a bit more familiar with Markdown, head over to [markdownguide.org](https://www.markdownguide.org/) and take a quick look through the [Get Started](https://www.markdownguide.org/getting-started/) article.

> Now you be thinking to yourself, _"Kameron, if I'm not going to be coding, then why should I learn Markdown?"_ Now, I could say that it's a "useful life skill" or some bullshit like that. But you know what, I like it, and I'm the one writing these tutorials. So until someone wants to come along and convert this all into LaTeX or a .docx, ya'll can suck it.

## How do I write in Markdown?
Bellow I provide a few simple examples to get you started. But you should really read through the [Basic Syntax](https://www.markdownguide.org/basic-syntax/) article to get a good overview of formatting in Markdown.

### Headings
Probably the most basic element in Markdown is its headings. You can create a heading using the `#` character. The humber of `#`'s that you use determines the level of heading:

```markdown
# Title

## Heading 1

### Heading 2

#### Heading 3
```

> **Tip:** Titles and Headings size 1 will often be underlined by renderers by default, but you can manually add full page line using `---`. I find this helps a lot when trying to add a bit of a break between sections or add emphasis.

### Lists
Probably the second most used future of Markdown is lists. There are 3 different types of lists: ordered, unordered, or checkboxes. Most renderers will also let you indent lists using tabs or 4 spaces.

```markdown
1. Ordered List

- Unordered List

- [ ] Unchecked checkbox
- [x] Checked checkbox
```

### Test Styling
You can make text _italic_ by surrounding the text with `_`'s or **bold** by surrounding it with `**`'s. You can make text both ***bold &

## Time to wrap it all up

Still curious? Check out the [Extended Syntax](https://www.markdownguide.org/extended-syntax/) guide.

Otherwise, with the skills now at your disposal, go forth and write beautifully formatted documents in markdown!
