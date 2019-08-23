---
template: post
title: Xử lý bất đồng bộ trong javascript
slug: /posts/Xử lý bất đồng bộ trong javascript/
draft: false
date: 2019-08-04T23:46:37.121Z
description: >-
  Quisque cursus, metus vitae pharetra auctor, sem massa mattis sem, at interdum
  magna augue eget diam. Vestibulum ante ipsum primis in faucibus orci luctus et
  ultrices posuere cubilia Curae; Morbi lacinia molestie dui. Praesent blandit
  dolor. Sed non quam. In vel mi sit amet augue congue elementum.
category: Javascript
tags:
  - Javascript
---
Quisque cursus, metus vitae pharetra auctor, sem massa mattis sem, at interdum magna augue eget diam. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Morbi lacinia molestie dui. Praesent blandit dolor. Sed non quam. In vel mi sit amet augue congue elementum.

![Nulla faucibus vestibulum eros in tempus. Vestibulum tempor imperdiet velit nec dapibus](/media/image-2.jpg)

Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enim in turpis pulvinar facilisis. Ut felis. 

Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna eros eu erat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus.



### 1. JSX là gì?

* JSX( viết tắt của Javascript XML) là một cấu trúc mở rộng của Javascript viết theo kiểm XML thường được sử dụng trong React để mô tả giao diện người dùng. Nó giống như một **template engine** nhưng mang đầy đủ sức mạnh của Javascript giúp người dùng có thể tạo ra các Component UI một cách đơn giản hơn.
* Công thức cơ bản để tạo ra JSX chính là Javascript + XML 

### 2. Cú pháp cơ bản của JSX

* Cú pháp của JSX: 


```
<ReactElement ReactAttributes > Children </ReactElement>
```

* Trong đó **Children** có thể là nội dung của Element hoặc đôi khi cũng có thể là một Element con
* Ví dụ cho cú pháp JSX đơn giản:


```
<h1>Hello, world!</h1> // Children là nội dung của element<div className="App">  <p>Hello, world<p> // Children là một element<div>
```

* Đôi khi có những Element không có **Chidren** bên trong ta có thể viết theo cấu trúc **SelfClosingElement:** 


```
<ReactElement  ReactAttributes />
```

Ví dụ cho  **SelfClosingElement :** 

```
<input type="text" />
```
