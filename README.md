# Snappy Scroll

### Core CSS Code
Use any one of these codes below as parent, they have different behaviour. Try yourself.
``` CSS
.snappyContainer-mandatory {
  scroll-snap-type: y mandatory;
  overflow-y: scroll;
  height: 100vh;
}
```
or
``` css
.snappyContainer-proximity {
  scroll-snap-type: y proximity;
  overflow-y: scroll;
  height: 100vh;
}
```
and use *windows* class as child for snappy effect
``` css
.windows {
  scroll-snap-align: start;
  width: 100%;
  height: 100vh;
}
```

### HTML Implementation
**Note :** *bg-blues, bg-purple, bg-berry* are background colors for different *windows.*

``` HTML
<div class="snappyContainer-mandatory">
  <div class="windows bg-blues"> Your code here </div>
  <div class="windows bg-purple"> Your code here </div>
  <div class="windows bg-berry"> Your code here </div>
</div>
```
or
``` HTML
<div class="snappyContainer-proximity">
  <div class="windows bg-blues"> Your code here </div>
  <div class="windows bg-purple"> Your code here </div>
  <div class="windows bg-berry"> Your code here </div>
</div>
```
