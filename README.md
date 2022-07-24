<h1><img src="https://img.fortawesome.com/349cfdf6/logo-fa-pro.svg" alt="Font Awesome 6.1.1 Pro" width="50%"></h1>

# Now, by using [jsdelivr.net](https://www.jsdelivr.com/).

## Steps:
1. Find your link on GitHub, and click to the "Raw" version.
2. Copy the URL.
3. Change ```raw.githubusercontent.com``` to ```cdn.jsdelivr.net```
4. Insert ```/gh/``` before your username.
5. Remove the ```branch``` name.
6. (Optional) Insert the version you want to link to, as ```@version``` (if you do not do this, you will get the <i>latest</i> - which may cause long-term caching)

## Examples:

```
https://raw.githubusercontent.com/<username>/<repo>/<branch>/path/to/file.js

DEMO: https://raw.githubusercontent.com/ignaciocorball/FA6PRO/master/css/all.css
```
Use this URL to get the latest version:
```
http://cdn.jsdelivr.net/gh/<username>/<repo>/path/to/file.js

DEMO: https://cdn.jsdelivr.net/gh/ignaciocorball/FA6PRO/css/all.css
```
Use this URL to get a specific version or commit hash:
```
http://cdn.jsdelivr.net/gh/<username>/<repo>@<version or hash>/path/to/file.js

DEMO: https://cdn.jsdelivr.net/gh/ignaciocorball/FA6PRO@5.15.3/css/all.css
```
<b>For production environments</b>, consider targeting a specific tag or commit-hash rather than the branch. Using the latest link may result in long-term caching of the file, causing your link to not be updated as you push new versions. Linking to a file by commit-hash or tag makes the link unique to version.
