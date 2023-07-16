- Document Object Model(DOM) provides web apis for a programmer to change style, properties or structure of a web document by using a scripting or programming language.
- To this end, DOM provides many interfaces which contain events, properties and methods. Window and Document are two of the most important interfaces.
### Window:
- Window is the root object of DOM hierarchy. It represents the browser window where the HTML document is being shown.
- Also, each tab will get its own global window object which can be accessed by javascript. But some properties like `innerHeight` and methods like `resizeTo()` still are present in global window which contains all tabs.
- Any property or method of window object can be accessed directly without using dot notation. `window.innerHeight` can directly be accessed as `innerHeight`.
- Main properties:
  - `history`: references history of pages visited in current window.
  - `innerHeight` and `innerWidth`: height and width of window.
  - `document`: the HTML document currently loaded in window.
  - `location`: URL of the current document in window.
- Main methods:
  - `open()` and `close()`: opens and closed the window
  - `prompt()`: prompts user for input and returns the text
  - `alert()`: alerts user with a dialog
  - `scroll()`: scrolls to particular position in window
### Document:
- Document object refers to content that is actually rendered or visible inside the browser window. It contains references to HTML, CSS, JS etc. that are needed to render the document.
- It can be accessed in javascript using `window.document` or `document`.
- Main properties:
  - `body` and `head`: returns `body` and `head` tag contents of current document.
  - `scripts`: returns collection of all `scipt` tag content.
  - `children`: returns collection of all child elements in current document.
- Main methods:
  - `append`: adds a new node element after the last child of document object.
  - `createElement`: creates new element with provided propertes.
  -  `getElementById`: gets an element of document with the given id.
 
