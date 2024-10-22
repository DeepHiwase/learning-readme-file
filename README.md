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

- Learning about the styling README file
