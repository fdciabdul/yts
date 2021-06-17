# Youtube search query without API

## install

`npm install https://github.com/fdciabdul/yts.git`

Test :

```javascript

const yt = require('yts_noapi');
let query = "search term";
yt.search(query)
.then(function(res) {
    console.log(res)

});

```

or with await 


```javascript

const yt = require('yts_noapi');
let query = "search term";
async function search(){
const search = await yt.search(query);
console.log(search);
}
search();

```
