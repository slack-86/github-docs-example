 # Writing good :cloud: documentation [^1]

## Step 1 - Using Codeblocks [^2]

A *good* **cloud engineer** uses codeblocks whenever possible because it allows others to copy and paste their code to replicate or research issues. 

Codeblocks are created with three backticks **`** (not single quotation) 

```
print("Hello, World!")
```
Highlight syntax by adding the language behind the back ticks
```python
print("Hello, World!")
```
>This is an example of python syntax highlighting

<img width=300px src="https://github.com/slack-86/github-docs-example/blob/0bd9c47f190101aca20cd8f2623971010423a2b2/assets/Image.jpeg">

Good cloud engineers use code blocks for both code and errors that appear in the console, for example:
```bash
NameError: name 'x' is not defined
```
> This is an example of an eror that appears in bash

## Step 3 - Use GitHub flavored markdown task lists

Github extends markdown to have a check list :thumbsup:[^3]
- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Step 4 - Emojis

| Name | Shortcode | Emoji |
| --- | --- | --- | 
| Computer | `:cloud:` | :cloud: |
| Cloud | `:computer:` | :computer: |

## Step 5 - Creating a markdown table [^4]
Here's the markdown for the preceding emoji table:
```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Computer | `:cloud:` | :cloud: |
| Cloud | `:computer:` | :computer: |
```
Github also extends markdown tables with addition alignment and cell formatting options.

## Bonus
[Secret Windows in Hidden Gardens](secret-window/hidden-garden.md)

## External References
[^1]: [Github Flavor Markdown Specificaitons](https://github.github.com/gfm/)
[^2]: [GFM Basic Writing and Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
[^3]: [GFM Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) 
[^4]: [GFM Tables (With Extension)](https://github.github.com/gfm/#tables-extension-)


