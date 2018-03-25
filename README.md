# Css Manual

## Table of Contents

* [Introduction](#introduction)
* [Syntax](#syntax)
* [Using Css](#using-css)
* [Selectors](#selectors)
* [Specifity](#specifity)
* [Inheritance](#inheritance)
* [Combinators](#combinators)
  * [Adjacent Sibling](#adjacent-sibling)
  * [General Sibling](#general-sibling)
  * [Child](#child)
  * [Descendant](#descendant)
* Reference
  * [Css Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
* Credit
  * https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass

## Introduction

CSS ย่อมาจาก Cascading Style Sheet ใช้กำหนดรูปแบบการแสดงผลของภาษา HTML เช่น รูปแบบตัวอักษร สี กำหนดการแสดงผลให้รองรับกับขนาดหน้าจอของอุปกรณ์ต่างๆ และ อื่นๆอีกมากมาย

## Syntax

<img src="https://github.com/yuttasakcom/css-manual/blob/master/img/syntax.png">

## Using Css

การเรียกใช้งาน Css

1.  External

```html
<link rel="stylesheet" type="text/css" href="/style.css" />
```

2.  Internal

```html
<style>
  selector {
    property: value;
  }
</style>
```

3.  Inline HTML

```html
<div style="property:value;"></div>
```

## Selectors

<img src="https://github.com/yuttasakcom/css-manual/blob/master/img/selectors.png">

<img src="https://github.com/yuttasakcom/css-manual/blob/master/img/selectors2.png">

## Specifity

<img src="https://github.com/yuttasakcom/css-manual/blob/master/img/specifity.png">

## Inheritance

<img src="https://github.com/yuttasakcom/css-manual/blob/master/img/inheritance.png">

## Combinators

### Adjacent Sibling

  <img src="https://github.com/yuttasakcom/css-manual/blob/master/img/adjacent-sibling.png">

### General Sibling

  <img src="https://github.com/yuttasakcom/css-manual/blob/master/img/general-sibling.png">

### Child

  <img src="https://github.com/yuttasakcom/css-manual/blob/master/img/child.png">
  
### Descendant
  <img src="https://github.com/yuttasakcom/css-manual/blob/master/img/descendant.png">
