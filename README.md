# es2021-ajax
suggestions for es2021 ajax features
## fetch in one step
`
async function getJson() {
return fetch("url").json;
}
var x = getJson();
// json code {foo : "bar"}
`
