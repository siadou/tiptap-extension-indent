# tiptap extension indent

## Introduction

This is an extension for [tiptap](https://github.com/ueberdosis/tiptap), Insprired by [Indent Extension For Tiptap 2 (just want to share)](https://github.com/ueberdosis/tiptap/issues/1036)

## 


## Settings

js
```
Indent.configure({
    maxLevel: 8,
    minLevel: 0,
    defaultLevel: 0,
    HTMLAttributes: {}
})
```

scss:

```
@for $i from $MIN_LEVEL through $MAX_LEVEL {
  [data-indent='#{$i}'] {
    $val: $i * 2rem;
    padding-left: $val;
  }
}
```
