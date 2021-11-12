# Markdown-Cheat-Sheet
Some marks are listed here, others like header are in different files

## Simple MarkDown

Name | Code | How to use | Result
---|---|---|---
Italic | `*` or `_` | `*Test*` or `_Test_` | *Test*
Bold | `**` or `__` | `**Test**` or `__Test__` | **Test**
Strike | `~~` | `~~Test~~` | ~~Test~~

You can mix these marks like this:

Strucure: `_**Test**_`

Result: _**Test**_

## Lists
### Numeric List
Example:
```
0. Test 1
0. Test 2
0. Test 3
0. Test 4
0. Test 5
```

Result:

0. Test 1
0. Test 2
0. Test 3
0. Test 4
0. Test 5

### Marks List
Example:
```
* Test 1
* Test 2
* Test 3
   * Test 4
* Test 5
```

Result:

* Test 1
* Test 2
* Test 3
   * Test 4
* Test 5

### Tasks List
Example:
```
- [ ] Test 1
- [ ] Test 2
- [ ] Test 3
- [x] Test 4
- [ ] Test 5
```

Result:

- [ ] Test 1
- [ ] Test 2
- [ ] Test 3
- [x] Test 4
- [ ] Test 5

## Images
Images can be added to your MD file like this:
Example: `![Github Logo](https://i.imgur.com/5cUA6pt.png)`

Result:

![Github Logo](https://i.imgur.com/5cUA6pt.png)

## Links
Links can be added to your MD file like this:

Example: `[Github](https://github.com)`

Result: [Github](https://github.com)

## Code

### Isolated code
You can add code to your md file if you want by doing this:

Example: \`console.log("Test");\`

Result: `console.log("Test");`

### Slice of code
What if you want to use multiple lines?

Example: \`\`\`

if(text === "hi") {

  console.log("hello");
  
} else {

  console.log("hi");
  
}

\`\`\`

Result: 
```
if(text === "hi") {
  console.log("hello");
} else {
  console.log("hi");
}
```

## Quotes
We can quete text like others people comments.

Example: `> Test`

Result: 
> Test

## Tables

Example: 
```
Centralized | Left alignment | Right alignment | Default alignment
:---:|:---|---:|---
Test | Test | Test | Test
```

Result: 

Centralized | Left alignment | Right alignment | Default alignment
:---:|:---|---:|---
Test | Test | Test | Test
