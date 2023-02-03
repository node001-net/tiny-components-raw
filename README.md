# Tiny Components - Raw

Component for not escaping Html. Thanks to (@GianlucaGuarini)[https://github.com/GianlucaGuarini]

## Installation

Setup this registry in your project .npmrc file:

```
@tiny-components:registry=https://gitea.node001.net/api/pa()ckages/tiny-components/npm/
```

Install with npm or yarn

```
npm i --save @tiny-components/raw
yarn add @tiny-components/raw
```

## Using

Thats all, html in String will not escaped.
```
<tiny-raw html={ htmlString }></tiny-raw>
```
