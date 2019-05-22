+++
title = "Markdown Syntax"
date = 2019-05-21T06:55:56Z
draft = false
tags = ["markdown", "test"]
categories = ["post"]
+++

# Learn to Write Markdown

***This article is porting from [Markdown Guide](https://www.markdownguide.org/basic-syntax/)***

## Paragraphs

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

## Line Breaks

This is the first line.  
And this is the second line. 

## Bold

I just love **bold text**.

## Italic

Italicized text is the *cat's meow*.

## Bold and Italic

This text is ***really important***.

## Blockquotes

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> <details>
>   <summary>lyrics</summary>
>   Life's a dance, we all have to do
> </details>
>
> *Everything* is going according to **plan**.
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Lists

1. First item
2. Second item
3. Third item
4. Fourth item

## Code Blocks

1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## images
1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the linux mascot](https://d33wubrfki0l68.cloudfront.net/e7ed9fe4bafe46e275c807d63591f85f9ab246ba/e2d28/assets/images/tux.png "Tux, the linux mascot")

3. Close the file.

## Code

At the command prompt, type `nano`.  
``Use `code` in your Markdown file.``

## Horizontal Rules

---

## Links

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

<https://www.markdownguide.org>  
<fake@example.com>

## Tables

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |


## Footnotes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

## Heading IDs {#heading-ids}

Check above heading's ID

Click [Heading IDs](#heading-ids) to go.

## Definition Lists

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

## Strikethrough

~~The world is flat.~~ We now know that the world is round.

## Task Lists

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
