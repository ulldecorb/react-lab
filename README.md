# Markdown
Markdown style cheatsheet

## Table of content
* [Heading](#heading)
* [Text style](#text-style)
    * [Italic](#italic)
    * [bold](#bold)
    * [Strike Through](#strike-through)
    * [Coded](#coded)
* [Escape Special Characters](#escape)
* [Links](#links)
* [Images](#images)
* [Tools](#tools)
* [Sources](#sources)

## Heading

>\# heading 1   
# heading 1
>\#\# heading 2
## heading 2
>\#\#\# heading 3
### heading 3
>\#\#\#\# heading 4
#### heading 4
>\#\#\#\#\# heading 5
##### heading 5
---
## Text style
<!-- Italics -->
### Italic
>\*this text is italics\*  
*this text is italics*

>\_italic\_  
_italic_

 ### Bold
<!-- Bold -->
>\*\*bold\*\*  
**bold**

### Strike through
<!-- Strike Through-->
>\~\~strike\~\~      
~~strike~~

### Coded

On GitHub md files:

Bash script block
>\```bash  
npm install  
\```
```bash
    npm install
```

JS Block
>\```javascript   
function add(num1, num2){  
}   
\```
```javascript
function add(num1, num2){
}
```

Python block
>\```python  
print("Hello World")  
\```
```python
print("Hello World")
```
<!-- Horizontal Line -->

--- 
___

<!-- Block quote -->
> this is a block

##[Links](#links)
<!--  links -->

>\[This is a link to React]\(https://reactjs.org/docs/getting-started.html)   

[This is a link to React](https://reactjs.org/docs/getting-started.html)

>\[This is the same link with tooltip]\(https://reactjs.org/docs/getting-started.html "Click to go reactjs.org")   

[This is the same link with tooltip](https://reactjs.org/docs/getting-started.html "Click to go reactjs.org")

### Unordered List
<!-- Unordered List -->
* item1
    * item2

<!--Ordered List-->
### Ordered List
1. first item
2. second item
### Inline Code Block
<!-- inline code block-->
`<p></p>`

## Escape Special Characters
Escape specials characters in markdown using backlash \( \ )

## Tools
### Escape specials characters in markdown using backlash \( \ ):
>\&#60;  
&#60;   

>\\\&#60;  
\&#60;   

### Extension to markdown files preview on VSC:
>[Auto-Open Markdown Preview](https://marketplace.visualstudio.com/items?itemName=hnw.vscode-auto-open-markdown-preview)   

### Comments on .md files are like .html files:   
>\<!-- text \-->

### Shortcut comments on VSC \(Windows OS spanish qwerty keyboard):
> Ctrl + ç

## Images
>\!\[H. P. Lovecraft]\(https://upload.wikimedia.org/wikipedia/commons/1/10/H._P._Lovecraft%2C_June_1934.jpg?20171011092735 "H. P. Lovecraft")   
![H. P. Lovecraft](https://upload.wikimedia.org/wikipedia/commons/1/10/H._P._Lovecraft%2C_June_1934.jpg?20171011092735 "H. P. Lovecraft")


<!-- task list -->
* [x] done
* [ ] not done
