# jquery.contenttitle
Setup input fields\elements that have their title as content.
Much like the HTML5 placeholder functionality - but jQuery powered.

- If content empty - reset to title
- If content not empty - leave it untouched
- If content is title, on focus - empty the field

Additional features:
- Setup multiple elements at once
- Adds a class when the title is displayed. For example for displaying the title in a different color.
- Works for <input>, <select>, <textarea> and maybe others
- If the title attribute is used, the browser automatically displays a tooltip for it on hover.

# Dependencies
- jQuery

# Example usage
Html
```html
<input title="search..."/>
<input title="type here..."/>
```

Javascript
```javascript
$("input").contentTitle()
```

# Options
```
$(selector).contentTitle({
  optionName: optionValue, ...
})
```

|optionName|description|default value|
----|----|----
|title_attribute|use this attribute to set the content title|"title"|
|title|use this text as content title|false|
|title_selector|selector to get the content title from html element content|false|
|title_class|class to be used if the content title is displayed|"contentTitle"|

# License
GPL version 3 or later
