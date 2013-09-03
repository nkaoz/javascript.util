javascript.util
===============

functions:


###muy util para textarea que no cuentan con la propiedad text Area
<pre>
~~~~
function MaxLengthText(element, len) {
    if (element.value.length > len) {
        txt = element.value.substring(0, len);
        element.set("value", txt);
    }
}
~~~~
</pre>