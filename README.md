
# Level 1 header

Lorem ipsum dolor sit amet, consectetur adipisicing elit,
sed do eiusmod tempor incididunt ut labore et dolore magna
aliqua. Ut enim ad minim veniam, quis nostrud exercitation
ullamco laboris nisi ut aliquip ex ea commodo consequat.

## Level 2 header

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Level 3 header

Sed ut perspiciatis unde omnis iste natus error sit voluptatem
accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab
illo inventore veritatis et quasi architecto beatae vitae dicta sunt
explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut
odit aut fugit, sed quia consequuntur magni dolores eos qui ratione
voluptatem sequi nesciunt.

## Other blocks

Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet,
consectetur, adipisci velit, sed quia non numquam eius modi tempora
incidunt ut labore et dolore magnam aliquam quaerat voluptatem.

    int i = 0;
    for ( ; i < 10; i++) {
        printf("Name: %s\n", names[i]);
    }

Ut enim ad minima veniam:

> Quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut
> aliquid ex ea commodi consequatur?

> Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse
> quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo
> voluptas nulla pariatur?

Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet,
consectetur, adipisci velit, sed quia non numquam eius modi tempora
incidunt ut labore et dolore magnam aliquam quaerat voluptatem.

~~~ Swift
for (var i = 0; i < 10; i++) {
    println("Name: \(names[i])")
}
~~~

---

 *  Quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut
    aliquid ex ea commodi consequatur?

 *  Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse
    quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo
    voluptas nulla pariatur?

***

 1. Quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut
    aliquid ex ea commodi consequatur?

 2. Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse
    quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo
    voluptas nulla pariatur?

___

## Spans

This [text is linked to "/url"](/url "url title"), and this text is
*emphasized*. There is also some `inlined code`.

## Which Redcarpet extensions are enabled?

#### NO INTRA EMPHASIS

If enabled, the word "word" is not emphasized in:

 * This is intra_word_emphasis with some __real__awesome underscores
 * This is intra*word*emphasis with some **real**awesome asterisks

#### TABLES

A little table:

| header 1 | header 2 |
| -------- | -------- |
| cell 1   | cell 2   |
| cell 3   | cell 4   |

#### FENCED CODE

```
Backtick-fence for code block
```

~~~
Tilde-fence for code block
~~~

#### AUTOLINK

Links without enclosing web pages like http://google.com or just
www.google.com or emails like someone@google.com without having to
enclose them in angle brackets.

#### STRIKETHROUGH

Here is some ~~struck out text~~ for you.

#### UNDERLINE

If enabled, the following is rendered underlined (else, it's treated as
normal emphasis):

_Text enclosed in single underscores_

#### SPACE HEADERS

If enabled, the following is NOT considered to be a h5 header:

#####Not a good header

#### SUPERSCRIPT

x^2 implies "x-squared" and 2^(nd) time implies "second time"

#### LAX SPACING

If enabled, HTML blocks do not require to be surrounded by an empty line
<div>
    This is inside a div
</div>
And this is outside the div.

If enabled, fenced code blocks do not require to be preceded by an empty line
~~~
This is inside a fence
~~~
And this is outside the fence.

If enabled, lists do not require to be preceded by an empty line:

This is an unordered list:
 * One
 * Two
 * Three

And this is an ordered list:
 1. One
 2. Two
 3. Three

End of list

#### DISABLE INDENTED CODE

If enabled, 4-space indented text, like below, is not considered to be a code-block

    int i = 0;
    for ( ; i < 10; i++) {
        printf("Name: %s\n", names[i]);
    }

#### HIGHLIGHT

Here is some ==highlighted text== for you.

#### FOOTNOTES

Super cali[^1] fragilistic

[^1]: expiali docious

#### QUOTE

Processes "quotes" in text to HTML `q` tags.

