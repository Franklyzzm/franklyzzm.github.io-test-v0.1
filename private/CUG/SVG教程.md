# SVG教程

## 圆形 - <circle>

```svg
<circle cx="100" cy="50" r="40" stroke="black" stroke-width="2" fill="red"/>
```

## 文本 - <text>

```svg
<text x="0" y="15" fill="red" transform="rotate(90 20,30)">I love SVG</text>
```

## 直线 - <line>

繞點x,y 旋轉 角度 `transform="rotate(角度 x,y)"`

```svg
<g style="fill:none; stroke:rgb(255,0,0); stroke-width:5" >
<line x1="20" y1="600" x2="1180" y2="600" />
<line x1="20" y1="600" x2="1180" y2="600" transform="rotate(45 600,600)" />
</g>
```

