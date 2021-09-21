Write a function that transform array data to valid `html` *string*

EXPECTED OUTPUT

```"<div>some div value<div/><div><span><span>last span value<span/></span></div><p>some p value<p/>"```

```javascript
const dataForHTML = [
    {
      type: 'div',
      value: 'some div value',
    },
    {
      type: 'div',
      value: {
        type: 'span',
        value: {
          type: 'span',
          value: 'last span value',
        }
      }
    },
    {
      type: 'p',
      value: 'some p value',
    }
]
```
