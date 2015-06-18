#html-minifier
https://github.com/kangax/html-minifier

##fix bug that `<!-- htmlmin:ignore -->` doesn't work .
The same issues.

https://github.com/kangax/html-minifier/issues/293

https://github.com/kangax/html-minifier/issues/353

https://github.com/kangax/html-minifier/issues/366


##Ignoring chunks of markup.
If you have chunks of markup you would like preserved, you can wrap them `<!-- htmlmin:ignore -->`.
example
```
<!-- htmlmin:ignore-->
<div data-key=<%value%>></div>
<input type="radio" <%@if($setting.type$=RCVD_ALL)%>checked="checked"<%@endif%> />
<!-- htmlmin:ignore-->
```
##How to use
I had modify the `htmlminifier.js` like that.

Detail: https://github.com/kangax/html-minifier/issues/376

