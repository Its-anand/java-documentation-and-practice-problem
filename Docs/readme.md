# Markdown Notes

### Headings in markdown

Just like in html we have 6 heading tags for different-different size, in markdown we have # different-different size starting from # to ###### which is same as h1 to h6 

```dtd
# h1
## h2
.
.
###### h6
```

### Line break Tag

In Html br tag wa used to change line. In markdown two enter are used when pressed enter twice then line will change.

like this.

### Horizontal line 

Two draw horizontal line just like hr tag, we use three dash --- this will draw a horizontal
like this.

---

### Unordered List

- To create list in the documentation use one dash - or + sign.
  - Two create sub list press space then press dash.

```dtd
like this
- This will create a list.
 - This will create a sublist.
```

### Ordered List

1. To create an ordered list in the documentation, use 1. space and text.
like this
```dtd
1. This is an ordered list.
```

### Hyperlink or link

Two insert Hyperlink or links in the document then we use square bracket followed by simple bracket. 
In square bracket, we put the description and url is placed inside simple bracket.

```dtd
[This is where we put description](Url)
```

### Highlight the text

To highlight text use backtick `Highlighted text` 

```dtd
`Highlighted text`
```
### Code

We can put code of any programming language just put three backtick ``` put code then three more backticks to close.
We can specify which programming language code is that. 

To do so put name of the language for example I will put java code in it, so I will put three backtick followed by the
name java ```java 

then put code in between then close by putting three more backtick at the end```

fore example.

```dtd

` ` `html
this is
` ` `

` ` `java
this is
` ` `

```
### Image

Inserting image is same as inserting hyperlink just with one small difference exclamation mark ! then one square bracket 
one simple bracket in square bracket put alt text and in simple bracket put url

```dtd
![alt image](https://picsum.photos/200/200)
```

![image](https://picsum.photos/200/200)

### Blockquote text

> This is Blockquote text to create Blockquote text use angular bracket >


### Italic

To make text Italic use one bold * hello * = *hello*

### Bold

To make text bold use two ** hello ** = **hello**

### Strike through

Strike through means ~~cut through~~ to insert it use two tilt characters  ~~

### Table of content (Section link)

We can create a Section link using hyperlink just at the place of url put # and name of the section, 
for example, [Introduction] (#introduction) Note: there should be only one # and everything should in lower case and if 
there are more than two words use dash - in between. 

for example, [introduction] (#introduction-to-computer)

## Github Special

### Table
Table is not officially supported in markdown but few websites like GitHub allow you to create table
the format of it is like this make sure to put this line |---|---|---| after table head otherwise it will not work
minimum three dash is necessary after each Vertical bar | like this  |---|

```dtd
| Head    | Head     | Head    |
|---------|----------|---------|
| Content | Content  | Content |
| Content | Content  | Content |
| Content | Content  | Content |
```

| Head    | Head     | Head    |
|---------|----------|---------|
| Content | Content  | Content |
| Content | Content  | Content |
| Content | Content  | Content |


### Alerts
This might not work everywhere except GitHub.
Alerts are a Markdown extension based on the blockquote syntax that you can use to emphasize critical information. 
On GitHub, they are displayed with distinctive colors and icons to indicate the significance of the content.

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

![image](https://docs.github.com/assets/cb-50447/mw-1440/images/help/writing/alerts-rendered.webp)

### Hiding content with comments

You can tell GitHub to hide content from the rendered Markdown by placing the content in an HTML comment.
```dtd
<!-- This content will not appear in the rendered Markdown -->
```
### Task lists

To create a task list, preface list items with a hyphen and space followed by [ ]. To mark a task as complete, use [x].
```dtd
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```
![Task lists image](https://docs.github.com/assets/cb-64626/mw-1440/images/help/writing/task-list-rendered-simple.webp)

### Mentioning people and teams

You can mention a person or team on GitHub by typing @ plus their username or team name. 
This will trigger a notification and bring their attention to the conversation.
People will also receive a notification if you edit a comment to mention their username or team name.

>Note: 
> A person will only be notified about a mention if the person has read access to the repository and, if the repository is owned by an organization, the person is a member of the organization.

@github/support What do you think about these updates?
![tag image](https://docs.github.com/assets/cb-6949/mw-1440/images/help/writing/mention-rendered.webp)

