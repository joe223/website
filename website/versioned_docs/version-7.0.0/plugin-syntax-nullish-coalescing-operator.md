---
id: version-7.0.0-babel-plugin-syntax-nullish-coalescing-operator
title: @babel/plugin-syntax-nullish-coalescing-operator
sidebar_label: syntax-nullish-coalescing-operator
original_id: babel-plugin-syntax-nullish-coalescing-operator
---

## Installation

```sh
npm install --save-dev @babel/plugin-syntax-nullish-coalescing-operator
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["@babel/plugin-syntax-nullish-coalescing-operator"]
}
```

### Via CLI

```sh
babel --plugins @babel/plugin-syntax-nullish-coalescing-operator script.js
```

### Via Node API

```javascript
require("@babel/core").transform("code", {
  plugins: ["@babel/plugin-syntax-nullish-coalescing-operator"]
});
```

