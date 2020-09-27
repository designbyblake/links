# CSS

## Prefers Reduced Motion

```CSS
@media (prefers-reduced-motion: reduce) {
  * {
    animation: none !important;
    transition: none !important;
  }
}
```

## Visually Hidden Content
```CSS
.sr-only {
  border: 0;
  clip: rect(0 0 0 0);
  clip-path: polygon(0px 0px, 0px 0px, 0px 0px);
  -webkit-clip-path: polygon(0px 0px, 0px 0px, 0px 0px);
  height: 1px;
  margin: -1px;
  overflow: hidden;
  padding: 0;
  position: absolute;
  width: 1px;
  white-space: nowrap;
}
```

## Full Width scrollbar fix
```CSS
.element{
	width:100vw;
	max-width:100%;
}
```

## Drop Shadow CSS (works on transparent things)
```CSS
.img{
	filter: drop-shadow(1px 2px 3px black);
}
```