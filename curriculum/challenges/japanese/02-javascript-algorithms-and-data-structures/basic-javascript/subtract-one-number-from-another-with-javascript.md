---
id: cf1111c1c11feddfaeb4bdef
title: JavaScript で、ある数値から別の数値を引き算する
challengeType: 1
videoUrl: 'https://scrimba.com/c/cP3yQtk'
forumTopicId: 18314
dashedName: subtract-one-number-from-another-with-javascript
---

# --description--

ある数値から別の数値を引き算することもできます。

JavaScript では減算記号として `-` を使用します。

**例**

```js
const myVar = 12 - 6;
```

`myVar` の値は `6` になります。
# --instructions--

差が `12` になるように `0` を変更してください。

# --hints--

The variable `difference` should be equal to `12`.

```js
assert(difference === 12);
```

You should only subtract one number from `45`.

```js
assert(/difference=45-33;?/.test(__helpers.removeWhiteSpace(code)));
```

# --seed--

## --after-user-code--

```js
(function(z){return 'difference = '+z;})(difference);
```

## --seed-contents--

```js
const difference = 45 - 0;
```

# --solutions--

```js
const difference = 45 - 33;
```
