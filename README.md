# Css Manual

## Table of Contents

* [Introduction](#introduction)
* [Using Css](#using-css)

## Introduction

CSS ย่อมาจาก Cascading Style Sheet ใช้สำหรับกำหนดรูปแแบหน้าตาของไฟล์ HTML นั่นเอง โดยสมบัติของ CSS จะมีสมบัติ Cascading คือ คำสั่งที่อยู่บนสุดจะมีลำดับสำคัญสูงกว่าคำสั่งด้านล่างเสมอ CSS สามารถใช้กำหนดรูปแบบ Font สี ฉากหลังและอื่นๆที่แสดงบนหน้าเว็บไชต์ทั้งหมด

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
