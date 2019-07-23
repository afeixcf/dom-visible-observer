# dom-visible-observer
在scroll过程中判断某个DOM是否已经进入指定容器的可视区域

```
npm install dom-visible-observer 

import visibleObserver from 'dom-visible-observer'

visibleObserver({
    container,
    el,
    threshold,
    show,
    hide
})
```

## container
表示监听滚动的容器 默认是document

## el
监听的DOM元素

## threshold
差值 number 默认0

## show
滚动容器时，当DOM进入容器可视区域时的回调

## hide
滚动容器时，当DOM未进入或已离开容器可视区域时的回调