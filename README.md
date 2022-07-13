<p align="center">
</p>

<h1>
    <h3>基于Vue.js的高质量UI工具包（在iView组件库基础上修改了部分适用于企业规范的默认样式）.</h3>
</h1>

[![](https://img.shields.io/travis/iview/iview.svg?style=flat-square)](https://travis-ci.org/iview/iview)
[![iView](https://img.shields.io/npm/v/iview.svg?style=flat-square)](https://www.npmjs.org/package/iview)
[![NPM downloads](http://img.shields.io/npm/dm/iview.svg?style=flat-square)](https://npmjs.org/package/iview)
[![NPM downloads](https://img.shields.io/npm/dt/iview.svg?style=flat-square)](https://npmjs.org/package/iview)
![JS gzip size](http://img.badgesize.io/https://unpkg.com/iview/dist/iview.min.js?compression=gzip&label=gzip%20size:%20JS&style=flat-square)
![CSS gzip size](http://img.badgesize.io/https://unpkg.com/iview/dist/styles/iview.css?compression=gzip&label=gzip%20size:%20CSS&style=flat-square)
[![Join the chat at https://gitter.im/iview/iview](https://img.shields.io/badge/chat-on_gitter-30b392.svg?style=flat-square)](https://gitter.im/iview/iview?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Backers on Open Collective](https://opencollective.com/iview/tiers/backer/badge.svg?label=backer&color=brightgreen)](#backers)
[![Sponers on Open Collective](https://opencollective.com/iview/tiers/sponsor/badge.svg?label=sponsor&color=brightgreen)](#sponers)


## Docs

**[3.x](http://iview.talkingdata.com/)** | [2.x](http://v2.iviewui.com) | [1.x](http://v1.iviewui.com)

## Features
高质量、功能丰富
友好的 API ，自由灵活地使用空间
细致、漂亮的 UI
可自定义主题

### Install postViewui

Using npm:
```
npm install post-viewui --save
```

Using a script tag for global use:

```html
<script type="text/javascript" src="iview.min.js"></script>
<link rel="stylesheet" href="dist/styles/iview.css">
```

You can find more info [on the website](https://www.iviewui.com/docs/guide/install-en).

## Usage

```vue
<template>
    <Slider v-model="value" range />
</template>
<script>
    export default {
        data () {
            return {
                value: [20, 50]
            }
        }
    }
</script>
```

Using css via `import`:

```js
import 'iview/dist/styles/iview.css';
```

## License
[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2016-present, TalkingData
