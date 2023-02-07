# VSCode All In One

[https://vscode.xgqfrms.xyz/](https://vscode.xgqfrms.xyz/)

[https://github.com/xgqfrms/vscode](https://github.com/xgqfrms/vscode)

## VSCode (shortcuts)

Shift + Alt + A === Block Commnets

Ctrl + / === line Commnets

## VSCode Code Snippets

> tst with dynamic testcases

```json
{
  "TypeScript Template": {
    "prefix": "tst",
    "body": [
      "\"use strict\";",
      "",
      "/**",
      " * ",
      " * @author xgqfrms",
      " * @license MIT",
      " * @copyright xgqfrms",
      " * @created 2023-02-0$1",
      " * @modified ",
      " * ",
      " * @description ",
      " * @description ",
      " * @difficulty Easy Medium Hard",
      " * @ime_complexity O(n)",
      " * @space_complexity O(n)",
      " * @augments ",
      " * @example ",
      " * @link https://leetcode.com/problems/$2/",
      " * @link https://leetcode.cn/problems/$2/",
      " * @solutions ",
      " * ",
      " * @best_solutions ",
      " * ",
      " */",
      "",
      "export {};",
      "",
      "const log = console.log;",
      "",
      "// Generator",
      "const $3 = ($5datas = [], debug = false) => {",
      "  let result = ``;",
      "  // do something...",
      "  return $7result;",
      "};",
      "",
      "",
      "export default $3;",
      "export {",
      "  $3,",
      "};",
      "",
      "/*",
      "",
      "",
      "// 测试用例 test cases",
      "const testCases = [",
      "  {",
      "    inputs: [],",
      "    input: '4193 with words  ',",
      "    result: 4193,",
      "    desc: 'value equal to 4193',",
      "  },",
      "];",
      "",
      "for (const [i, testCase] of testCases.entries()) {",
      "  const [first, second] = testCase.inputs;",
      "  const result = $3(first, second);",
      "  log(`test case \\${i} result: `, JSON.stringify(result) === JSON.stringify(testCase.result) ? `✅ passed` : `❌ failed`, result);",
      "  const result = $3(testCase.input);",
      "  log(`test case \\${i} result: `, result === testCase.result ? `✅ passed` : `❌ failed`, result);",
      "  // log(`test case ${i} =`, testCase);",
      "}",
      "",
      "// $ npx ts-node ./100\\ same-tree.ts",
      "",
      "*/",
      "",
    ],
    "description": "TypeScript Template & code snippets!"
  }
}
```

> js6r with dynamic test cases

```json
{
  "JavaScript ES6 React Template": {
    "prefix": "js6r",
    "body": [
      "\"use strict\";",
      "",
      "/**",
      " * ",
      " * @author xgqfrms",
      " * @license MIT",
      " * @copyright xgqfrms",
      " * @created 2022-03-0$1",
      " * @modified ",
      " * ",
      " * @description ",
      " * @description ",
      " * @difficulty Easy Medium Hard",
      " * @complexity O(n)",
      " * @time O(n)",
      " * @augments ",
      " * @example ",
      " * @link https://leetcode.com/problems/$2/",
      " * @link https://leetcode-cn.com/problems/$2/",
      " * @solutions ",
      " * ",
      " * @best_solutions ",
      " * ",
      " */",
      "",
      "const log = console.log;",
      "",
      "// Generator",
      "const $3 = ($5datas = [], debug = false) => {",
      "  let result = ``;",
      "  // do something...",
      "  return $7result;",
      "};",
      "",
      "",
      "export default $3;",
      "export {",
      "  $3,",
      "};",
      "",
      "/*",
      "",
      "",
      "// 测试用例 test cases",
      "const testCases = [",
      "  {",
      "    input: '4193 with words  ',",
      "    result: 4193,",
      "    desc: 'value equal to 4193',",
      "  },",
      "];",
      "for (const [i, testCase] of testCases.entries()) {",
      "  const result = $3(testCase.input);",
      "  log(`test case ${i} result: `, result === testCase.result ? `✅ passed` : `❌ failed`, result);",
      "  // log(`test case ${i} result:\n\t\t`, result === testCase.result ? `passed ✅` : `failed ❌`, result);",
      "  // log(`test case ${i} =`, testCase);",
      "}",
      "",
      "",
      "*/",
      "",
    ],
    "description": "JavaScript ES6 React Template & code snippets!"
  }
}
```

> js6r (with test cases)

```json
{
  "JavaScript ES6 React Template": {
    "prefix": "js6r",
    "body": [
      "\"use strict\";",
      "",
      "/**",
      " * ",
      " * @author xgqfrms",
      " * @license MIT",
      " * @copyright xgqfrms",
      " * @created 2022-03-0$1",
      " * @modified ",
      " * ",
      " * @description $2",
      " * @description $2",
      " * @difficulty Easy Medium Hard",
      " * @complexity O(n)",
      " * @time O(n)",
      " * @augments ",
      " * @example ",
      " * @link https://leetcode.com/problems/???/",
      " * @link https://leetcode-cn.com/problems/???/",
      " * @solutions ",
      " * ",
      " * @best_solutions ",
      " * ",
      " */",
      "",
      "const log = console.log;",
      "",
      "// Generator",
      "const $3 = ($5datas = [], debug = false) => {",
      "  let result = ``;",
      "  // do something...",
      "  return $7result;",
      "};",
      "",
      "",
      "export default $3;",
      "export {",
      "  $3,",
      "};",
      "",
      "/*",
      "",
      "",
      "// 测试用例",
      "// test cases",
      "const tests  = [",
      "  '4193 with words  ',",
      "  '   -42',",
      "  '12345657890 bigint',",
      "];",
      "for (const [i, test] of tests.entries()) {",
      "  const result = $3(test);",
      "  if(typeof result === 'boolean') {",
      "    log(`test${i} =`, result ? `✅` : `❌`);",
      "  } else {",
      "    log(`test${i} =`, result);",
      "  }",
      "}",
      "",
      "",
      "*/",
      "",
    ],
    "description": "JavaScript ES6 React Template & code snippets!"
  }
}

```

> test

```json
{
  "JavaScript ES6 React Template": {
    "prefix": "js6r",
    "body": [
      "\"use strict\";",
      "",
      "/**",
      " * ",
      " * @author xgqfrms",
      " * @license MIT",
      " * @copyright xgqfrms",
      " * @created 2022-03-0$1",
      " * @modified ",
      " * ",
      " * @description $2",
      " * @description $2",
      " * @difficulty Easy Medium Hard",
      " * @complexity O(n)",
      " * @time O(n)",
      " * @augments ",
      " * @example ",
      " * @link https://leetcode.com/problems/???/",
      " * @link https://leetcode-cn.com/problems/???/",
      " * @solutions ",
      " * ",
      " * @best_solutions ",
      " * ",
      " */",
      "",
      "const log = console.log;",
      "",
      "// Generator",
      "const $3 = ($5datas = [], debug = false) => {",
      "  let result = ``;",
      "  // do something...",
      "  return $7result;",
      "};",
      "",
      "",
      "export default $3;",
      "export {",
      "  $3,",
      "};",
      "",
      "/*",
      "",
      "// error",
      "const test1 = isValid(`((}}`);",
      "// ok",
      "const test2 = isValid(`()[]{}`);",
      "",
      "log(`❌test =`, test1 ? `✅` : `❌`);",
      "log(`✅test ok =`, test2 ? `✅` : `❌`);",
      "",
      "// test cases",
      "// 测试用例",
      "const tests  = [",
      "  '4193 with words  ',",
      "  '   -42',",
      "  '12345657890 bigint',",
      "];",
      "for (const [i, test] of tests.entries()) {",
      "  const result = $3(test);",
      "  log(`test${i} =`, result, result ? `✅` : `❌`);",
      "}",
      "",
      "",
      "*/",
      "",
    ],
    "description": "JavaScript ES6 React Template & code snippets!"
  }
}
```

> js6r

```json
{
    "JavaScript ES6 React Template": {
        "prefix": "js6r",
        "body": [
            "\"use strict\";",
            "",
            "/**",
            " * ",
            " * @author xgqfrms",
            " * @license MIT",
            " * @copyright xgqfrms",
            " * @created 2019-08-$1",
            " * ",
            " * @description $2",
            " * @augments $3",
            " * @example $4",
            " * @link $5",
            " * ",
            " */",
            "",
            "const log = console.log;",
            "",
            "const $2Generator = ($5datas = [], debug = false) => {",
            "    let result = ``;",
            "    // do something...",
            "    return $7result;",
            "};",
            "",
            "",
            "",
            "export default $2;",
            "",
            "export {",
            "    $2,",
            "};",
            "",
        ],
        "description": "JavaScript ES6 React Template & code snippets!"
    }
}

```

> js6r

```json
{
  "JavaScript ES6 React Template": {
    "prefix": "js6r",
    "body": [
      "\"use strict\";",
      "",
      "/**",
      " * ",
      " * @author xgqfrms",
      " * @license MIT",
      " * @copyright xgqfrms",
      " * @created 2020-01-0$1",
      " * ",
      " * @description $2",
      " * @augments $3",
      " * @example $4",
      " * @link $5",
      " * ",
      " */",
      "",
      "const log = console.log;",
      "",
      "const $2Generator = ($5datas = [], debug = false) => {",
      "    let result = ``;",
      "    // do something...",
      "    return $7result;",
      "};",
      "",
      "",
      "",
      "export default $2;",
      "",
      "export {",
      "    $2,",
      "};",
      ""
    ],
    "description": "JavaScript ES6 React Template & code snippets!"
  }
}


```

> ts6r

```json

{
    "TypeScript ES6 React Template": {
        "prefix": "ts6r",
        "body": [
            "\"use strict\";",
            "",
            "/**",
            " * ",
            " * @author xgqfrms",
            " * @license MIT",
            " * @copyright xgqfrms",
            " * @created 2019.0$1.0$2",
            " * ",
            " * @description $3",
            " * @augments ",
            " * @example ",
            " * @link $4",
            " * ",
            " */",
            "",
            "const $3Generator = ($5datas = [], debug = false) => {",
            "    let result = ``;",
            "    // do something...",
            "    return $6result;",
            "};",
            "",
            "",
            "",
            "export default $3;",
            "",
            "export {",
            "    $3,",
            "};",
            ""
        ],
        "description": "TypeScript ES6 React Template & code snippets!"
    }
}


```

> p3y

```json
{
  "Python3 Template": {
    "prefix": "py3",
    "body": [
      "# coding: utf8",
      "",
      "__author__ = 'xgqfrms'",
      "",
      "\"\"\"",
      "",
      "/**",
      " * ",
      " * @author xgqfrms",
      " * @license MIT",
      " * @copyright xgqfrms",
      " * @created 2020-01-0$1",
      " * ",
      " * @description $2",
      " * @augments $3",
      " * @example $4",
      " * @link $5",
      " * ",
      " */",
      "",
      "\"\"\""
    ],
    "description": "Python3 Template & code snippets!"
  }
}

```

> js6r （new version）

```json

{
  "JavaScript ES6 React Template": {
    "prefix": "js6r",
    "body": [
      "\"use strict\";",
      "",
      "/**",
      " * ",
      " * @author xgqfrms",
      " * @license MIT",
      " * @copyright xgqfrms",
      " * @created 2020-08-0$1",
      " * @modified ",
      " * ",
      " * @description $2",
      " * @difficulty Easy Medium Hard",
      " * @complexity O(n)",
      " * @augments ",
      " * @example ",
      " * @link ",
      " * @solutions ",
      " * ",
      " */",
      "",
      "const log = console.log;",
      "",
      "// Generator",
      "const $3 = ($5datas = [], debug = false) => {",
      "  let result = ``;",
      "  // do something...",
      "  return $7result;",
      "};",
      "",
      "",
      "",
      "export default $3;",
      "",
      "export {",
      "  $3,",
      "};",
      "",
    ],
    "description": "JavaScript ES6 React Template & code snippets!"
  }
}
```

> got

```json
{
  "Go Template": {
    "prefix": "got",
    "body": [
      "/**",
      " * ",
      " * @author xgqfrms",
      " * @license MIT",
      " * @copyright xgqfrms",
      " * @created 2020-01-0$1",
      " * ",
      " * @description $2",
      " * @augments $3",
      " * @example $4",
      " * @link $5",
      " * ",
      " */",
      "",
      "package main",
      "",
      "// import \"fmt\"",
      "// import (\"fmt\")",
      "import (",
      "  \"fmt\"",
      "  \"strings\"",
      "  \"time\"",
      "  \"math/rand\"",
      "  \"testing\"",
      "  \"bytes\"",
      "  \"encoding/base64\"",
      "  \"image\"",
      "  \"image/png\"",
      ")",
      "",
      "func main() {",
      "  fmt.Println(\"Hello, Go\")",
      "}",
      "",
      ""
    ],
    "description": "Go Template & code snippets!"
  }
}

```

<!-- [want more](https://github.com/xgqfrms/vscode/tree/master/code-snippets) -->

<!-- [want more](./code-snippets/readme.md) -->

[want more](./code-snippets#readme)

<!-- https://github.com/xgqfrms/vscode/issues -->


## VSCode useful Extensions All In One 


[VSCode useful Extensions All In One ](./plugins-extensions/readme.md)

<!--

[VSCode useful Extensions All In One ](./plugins-extensions/readme.md)

[VSCode useful Extensions All In One ](./plugins-extensions#readme)

[VSCode useful Extensions All In One ](./plugins-extensions)


https://github.com/xgqfrms/vscode/blob/master/
-->

## refs

> vscode & code snippets

https://www.cnblogs.com/xgqfrms/p/9226993.html













