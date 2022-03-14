ナビ
# \<a>のクリックできる範囲を広くする
## HTML
```html
<nav>
  <div class="container">
    <ul class="navbar">
      <li><a href="#">ホーム</a></li>
      <li><a href="#">お問い合わせ</a></li>
    </ul>
  </div>
</nav>
```

## CSS
```css
.navbar {
  margin: 0;
  padding: 0;
  list-style-type: none;
  background: #565656;
}

.navbar li a {
  display: block;
  padding: 10px 8px;
  color: #fff;
  text-decoration: none;
}
.navbar li a:hover {
  background: #fff;
  color: #565656;
}
```

### ```display: block;```
ブロックにする
