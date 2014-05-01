**Syntax:** `addButtonToContainer( text, func [, ID] );`

<br/>

**Arguments:**
* **text** [string]: The text for the button.
* **func** [function]: The function to be called when the button is clicked upon.
* **ID** _(optional)_ [string]: The ID to be used for the button element.

<br/>

**Example:**
`addButtonToContainer('A Test Button', function () { alert('Test.'); }, 'test-button');`