
#USAGE:

await fetchAsync('https://raw.githubusercontent.com/zackmark29/hmacsha1/main/hmacsha1.js');

var key = '';
var query = '';

var hmacsha1 = hmacSha1(key, query);
console.log(hmacsha1);  //result: 37dba14338dc6569f66aab9757462fc2a402e2ee

function hmacSha1(key, query) {
    return hmacSha1(key, query);
}

async function fetchAsync(url) {
    const promise = await fetch(url, {
        method: 'GET',
    });
    const data = await promise.text();
    return data;
}

credit: https://stackoverflow.com/a/43965010/14311474
