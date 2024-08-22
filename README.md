# fiveno
JavaScript library for 5ne.co/
# main
```js
async function main(){
    const {fiveno} = require('./fiveno');
    const url= new fiveno();
    let req=await url.short_url("url")
    console.log(req)
}
main()
```
