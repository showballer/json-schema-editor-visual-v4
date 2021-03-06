# json-schema-editor-visual

A json-schema editor of high efficient and easy-to-use, base on React&antd4.

![avatar](json-schema-editor-visual.jpg)

## Usage

```
npm install json-schema-editor-visual-v4
```

```js
const option = {};
import "antd/dist/antd.css";
require("json-schema-editor-visual-v4/dist/main.css");
const schemaEditor = require("json-schema-editor-visual-v4/dist/main.js");
const SchemaEditor = schemaEditor(option);

render(<SchemaEditor />, document.getElementById("root"));
```

## Option Object

| name | desc                                 | default |
| ---- | ------------------------------------ | ------- |
| `lg` | language, support `en_US` or `zh_CN` | en_US   |

## SchemaEditor Props

| name         | type     | default | desc               |
| ------------ | -------- | ------- | ------------------ |
| `data`       | string   | null    | the data of editor |
| `onChange`   | function | null    |
| `showEditor` | boolean  | false   |
