# jquery.contenttitle
Setup input fields\elements that have their title as content.

- Empty field on click
- If content null - reset to title
- If content not null - leave new content untouched

Additional features:
- Adds class if title is displayed (for example for displaying the title in different color)
- Works for input, select, textarea and possibly others
- Setup multiple elements at once
- The content title is displayed on hover if the ``title`` is used

# Example usage
Html
```html
<input title="search..."/>
```

Javascript
```javascript
$("input").contentTitle();
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
