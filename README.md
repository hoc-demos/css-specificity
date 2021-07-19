# CSS Specificity

![](https://raw.githubusercontent.com/hoc-demos/images/main/css-specificity.png)

```html
 <ul>
      <li><a style="color:dodgerblue" href="">style="color:dodgerblue"</a></li>
      <li><a id="id-link" href="">id="id-link"</a></li>
      <li><a class="class-links" href="">class="class-links"</a></li>
      <li><a href="">Nothing on element</a></li>
    </ul>
```

<br/>

### Specificity from Highest to Lowest

#### Style
```html
<li><a style="color:dodgerblue" href="">style="color:dodgerblue"</a></li>
```

#### ID
```css
#id-link {
    color:green;
}
```

#### Class
```css
.class-links {
    color:hotpink;
}
```

#### Type
```css

a {
    color:black;
    font-weight:800;
    font-size:40px;
}
```
