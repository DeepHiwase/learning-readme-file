# A first level heading
## A second level heading
### A third level heading
#### Like h4
##### Like h5
###### Like h6

**This is bold text.**
_This text is italicized._
~~This was mistaken text.~~
**This text is _extremely_ important.**
***All this text is important all bold & italic.***
This is a <sub>subscript</sub> text. a<sub>2</sub>.
This is a <sup>superscript</sup> text. a<sup>2</sup>.

Text that is not a quote
> Text that is a quote.
> All in single quote using ">"

Use `git status` to list all new or modified files that haven't yet been committed. This is inline quoting using backticks.

To format code or text into its own distinct block, use triple backticks. Auto add copy btn and looks like commands or code section.
Some basic Git commands are:
```
git status
git add
git commit
```
### Code section adding
```
function test() {
  console.log("notice the blank line before this function?");
}
```
To preserve your formatting within a list, make sure to indent non-fenced code blocks by eight spaces.

To display triple backticks in a fenced code block, wrap them inside quadruple backticks.

````
```
Look! You can see my backticks.
```
````

### Syntax Highlighting by giving language name
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="json place holder practice / taking out from server">
  <title>LinkedIn Posts -> json place holder</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/axios/1.7.7/axios.min.js"></script>
</head>
<body>
  <h1>LinkedIn</h1>
  <p><b><i><u>Posts: </u></i></b></p>
  <div id="post"></div>
  <button onclick="getRecentPosts()">Fetch Recent Post</button>
  
  <script src="script.js"></script>
</body>
</html>
```

### Supported Color Models
The background color is `#ffffff` for light mode and `#000000` for dark mode.
- HEX `#0969DA`
- RGB  `rgb(9, 105, 218)`
- HSL `hsl(212, 92%, 45%)`
- The visualization of the color is only supported in issues, pull requests, and discussions.

### Links
- You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ).
- This site was built using [GitHub Pages](https://pages.github.com/).


## This'll  be a _Helpful_ Section About the Greek Letter Θ!
A heading containing characters not allowed in fragments, UTF-8 characters, two consecutive spaces between the first and second words, and formatting.

### SECTION Creation or adding anchor tag
Link to the helpful section: [Link Text](#thisll--be-a-helpful-section-about-the-greek-letter-Θ).
- all should be lowercase.
- `-` must be there instead of whitespaces.

### Relative Links -> path/url to file/img/folder present in rootFolder/currentcolder/perviousfolder
- A relative link is a link that is relative to the current file. For example, if you have a README file in root of your repository, and you have another file in docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might look like this:
- [Contribution guidelines for this project](docs/CONTRIBUTING.md)
- GitHub will automatically transform your relative link or image path based on whatever branch you're currently on, so that the link or path always works. The path of the link will be relative to the current file. Links starting with` / `will be relative to the repository root. You can use all relative link operands, such as `./ `and `../`.



- Learning about the styling README file
