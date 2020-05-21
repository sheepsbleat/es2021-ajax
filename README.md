# es2021-ajax
suggestions for es2021 ajax features
## fetch in one step
```javascript
async function getJson() {
return fetch("url").json;
}
var x = getJson();
// json code {foo : "bar"}
```
## xhr deprecated off standards (or change syntax to something like this) 
```javascript
var xhttp = new XMLHTTPREQUEST;
xhttp.onrequestready(response => (
response.json();
))
```
