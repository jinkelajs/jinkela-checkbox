# Jinkela-Checkbox

## Install

```bash
npm install jinkela-checkbox
```

## Usage

### new Checkbox([args])

* `args` **Object** Set of configurable options to set. Can have the following fields:
  * `text` **String** The default text.
  * `readonly` **Boolean** The readonly flag.

## Demo [Live](https://jinkelajs.github.io/jinkela-checkbox/example/)

```html
<meta charset="utf-8" />
<script src="https://unpkg.com/jinkela@1.2.19/umd.js"></script>
<script src="https://unpkg.com/jinkela-checkbox@1.0.0/index.js"></script>
<script>
addEventListener('load', () => {

  let hehe = new Checkbox({ text: 'hehe' }).to(document.body);

  console.log(hehe.checked);

});
</script>
```
