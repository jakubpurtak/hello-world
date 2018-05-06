# Nagłowek1
This is also an H2
------------------

*Introducing my quote:*

> Neque porro quisquam est qui
> dolorem ipsum quia dolor sit amet, 
> consectetur, adipisci velit...



```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```
