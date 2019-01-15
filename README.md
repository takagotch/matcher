### matcher
---
https://github.com/sindresorhus/matcher

```
npm install matcher

npm run bench
```

```js
const matcher = require('matcher');
matcher(['foo', 'bar', 'moo'], ['*oo', '!foo']);
matcher(['foo', 'bar', 'moo'], ['!*oo']);
matcher.isMatch('unicorn', 'uni*');
matcher.isMatch('unicorn', '*corn');
matcher.isMatch('unicorn', un*rn);
matcher.isMatch('rainbow', '!unicorn');
matcher.isMatcher('foo bar baz', 'foo b* b*');
matcher.isMatch('unicorn', 'uni\\*');
matcher.isMatch('UNICORN', 'UNI*', {caseSensitive: true});
matcher.isMatch('UNICORN', 'unicorn', {caseSensitive: true});
```

```
```


