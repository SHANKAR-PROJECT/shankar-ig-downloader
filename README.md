# Instalation :
```bash
> npm i priyansh-ig-downloader
```

## Example
```js
const insta = require("priyansh-ig-downloader");

async function test(url) {
  try {
    const result = await insta(url);
    console.log(result);
  } catch (error) {
    console.error("Error fetching data:", error);
  }
}

test("https://www.instagram.com/reel/C9HytkYS4Hc/?utm_source=ig_web_copy_link");
```
## Output Example
```
{
  "video": [
    {
      "video": "https://scontent.cdninstagram.com/o1/v/t16/f2/m69/An9VukWeVHPYEj_QoBTxvf0tfXakKJyWBnztDeTFbQnOgu4XVsGh1Y4xi8ucjLzRFEqnQXom7sn5MSlr01mZbWN3.mp4?efg=eyJxZV9ncm91cHMiOiJbXCJpZ193ZWJfZGVsaXZlcnlfdnRzX290ZlwiXSIsInZlbmNvZGVfdGFnIjoidnRzX3ZvZF91cmxnZW4uY2xpcHMuYzIuMTA4MC5iYXNlbGluZSJ9&_nc_ht=scontent.cdninstagram.com&_nc_cat=111&vs=497431829473320_3124900975&_nc_vs=HBksFQIYOnBhc3N0aHJvdWdoX2V2ZXJzdG9yZS9HQXZCQlJRTXI0ZThmc0FDQUhwU212emZpdTU5YnBSMUFBQUYVAALIAQAVAhg6cGFzc3Rocm91Z2hfZXZlcnN0b3JlL0dBVFAwQnBUU1J0S21NZ0NBSHFCM0hWajJtNEVicV9FQUFBRhUCAsgBACgAGAAbABUAACb%2B7dzD24aXQRUCKAJDMywXQDuQ5WBBiTcYFmRhc2hfYmFzZWxpbmVfMTA4MHBfdjERAHX%2BBwA%3D&_nc_rid=5c862724ed&ccb=9-4&oh=00_AYCg7DV04LknbzJ_Y09ehpcdqt3Jl9gykX2lFieJAjWUJg&oe=668D6CE5&_nc_sid=10d13b",       
      "thumbnail": "https://scontent.cdninstagram.com/v/t51.29350-15/450258777_1528082971118106_3162685055130347958_n.jpg?stp=dst-jpg_e15&_nc_ht=scontent.cdninstagram.com&_nc_cat=1&_nc_ohc=P2DVaf_sZ0IQ7kNvgFSmczi&edm=APs17CUBAAAA&ccb=7-5&oh=00_AYC7b5Dib4CyVhX_h6D1Tb8hZSuKD0fbAfcNcvN78enfaA&oe=66916EA3&_nc_sid=10d13b"
    }
  ]
}
```