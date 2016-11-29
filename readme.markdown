# minimist-browser
A fork of the excellent [minimist](https://github.com/substack/minimist) for the browser. Adds `parseCli` to window. See minimist for all options.

# usage
```javascript
// arg: string
var str = 'query -f -n 10 -u username',
    res = parseCli(str);
```

# license
MIT