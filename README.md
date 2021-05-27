TOTP
# Generate time-based one time passwords in the browser
[Demo](https://git-collab.github.io/totp/)

## Providing parameters in the URL

### Private key

You can provide the key in the URL using the URI fragment or a query parameter, for example: `https://totp.danhersam.com/#/KEY` or `https://totp.danhersam.com?key=KEY`
<br><br>
```
https://git-collab.github.io/totp/#/KEY
```
```
https://git-collab.github.io/totp/?key=KEY
```
<br><br>
### Digits and period
You can also provide the digits and token period using a query string in the URL, for example: `https://totp.danhersam.com/?period=60&digits=6&key=KEY`
<br><br>
```
https://git-collab.github.io/totp/?period=60&digits=6&key=KEY
```
