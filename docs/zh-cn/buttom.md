
## Button 按钮

####  基础按钮
不同颜色来适应不同的应用场景 
<div class="marginT10">
  <button class="pure-btn pure-btn--default" >
    <span class="pure-btn__text">default</span>
  </button>
  <button class="pure-btn pure-btn--primary "  >
    <span class="pure-btn__text">primary</span>
  </button>
  <button class="pure-btn pure-btn--success" >
    <span class="pure-btn__text">success</span>
  </button>
  <button class="pure-btn pure-btn--error" >
    <span class="pure-btn__text">error</span>
  </button>
  <button class="pure-btn pure-btn--warning" >
    <span class="pure-btn__text">warning</span>
  </button>
  <button class="pure-btn pure-btn--info" >
    <span class="pure-btn__text">info</span>
  </button>
</div> 

 ```html
  <!-- default  primary success error  warning info -->
   <button class="pure-btn pure-btn--default" >
      <span class="pure-btn__text">default</span>
   </button>
 ```

####  幽灵按钮
通过添加 `.pure-btn--对应状态--hollow` 类来实现描边效果
  <div class="marginT10">
    <button class="pure-btn pure-btn--default" >
      <span class="pure-btn__text">default</span>
    </button>
    <button class="pure-btn pure-btn--primary  pure-btn--primary--hollow"  >
      <span class="pure-btn__text">primary</span>
    </button>
    <button class="pure-btn pure-btn--success  pure-btn--success--hollow" >
      <span class="pure-btn__text">success</span>
    </button>
    <button class="pure-btn pure-btn--error  pure-btn--error--hollow" >
      <span class="pure-btn__text">error</span>
    </button>
    <button class="pure-btn pure-btn--warning  pure-btn--warning--hollow" >
      <span class="pure-btn__text">warning</span>
    </button>
    <button class="pure-btn pure-btn--info  pure-btn--info--hollow" >
      <span class="pure-btn__text">info</span>
    </button>
 </div>

```html
    <button class="pure-btn pure-btn--primary  pure-btn--primary--hollow"  >
      <span class="pure-btn__text">primary</span>
    </button>
 ```

####  按钮尺寸
  通过添加 `.pure-btn--large`, `.pure-btn--small`, `.pure-btn--smaller`   控制按钮大小
  <div class="marginT10">
    <button class="pure-btn pure-btn--primary pure-btn--large" >
      <span class="pure-btn__text">large</span>
    </button>
   <button class="pure-btn pure-btn--primary " >
      <span class="pure-btn__text">normal</span>
    </button>
    <button class="pure-btn pure-btn--primary  pure-btn--small"  >
      <span class="pure-btn__text">small</span>
    </button>
    <button class="pure-btn pure-btn--primary  pure-btn--smaller"  >
      <span class="pure-btn__text">smaller</span>
    </button>
 </div>

```html
    <button class="pure-btn pure-btn--primary pure-btn--large" >
      <span class="pure-btn__text">large</span>
    </button>
    <button class="pure-btn pure-btn--primary " >
      <span class="pure-btn__text">normal</span>
    </button>
    <button class="pure-btn pure-btn--primary  pure-btn--small"  >
      <span class="pure-btn__text">small</span>
    </button>
    <button class="pure-btn pure-btn--primary  pure-btn--smaller"  >
      <span class="pure-btn__text">smaller</span>
    </button>
 ```
####  按钮组
 

   元素外层添加 `.pure-btn-group`  实现按钮组
<div class="marginT10">
  <div class="pure-btn-group">
      <button class="pure-btn " >
        <span class="pure-btn__text">large</span>
      </button>
      <button class="pure-btn" >
        <span class="pure-btn__text">normal</span>
      </button>
      <button class="pure-btn "  >
        <span class="pure-btn__text">small</span>
      </button>
    </div>
  </div>

```html
  <div class="pure-btn-group">
      <button class="pure-btn " >
        <span class="pure-btn__text">large</span>
      </button>
      <button class="pure-btn " >
        <span class="pure-btn__text">normal</span>
      </button>
      <button class="pure-btn  "  >
        <span class="pure-btn__text">small</span>
      </button>
      <button class="pure-btn "  >
        <span class="pure-btn__text">smaller</span>
      </button>
    </div>
 ```