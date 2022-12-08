# carousel（轮播图）

1. 图片尺寸：宽 = 600px 、高 = 375px
2. 轮播图显示窗口尺寸：宽 = 600px 、高 = 375px
3. 按钮尺寸：宽 = 30px 、高 = 50px 
4. 指示器尺寸及间距：宽 = 高 = 20px 、左右边距 = 10px
5. 指示器容器尺寸：宽 = 6 * (20 + 20) = 240 px

### 1. HTML结构

```html
<!-- 轮播图显示窗口 -->
<div class="carousel">
    <!-- 图片存放区域 -->
    <ul class="images">
        ...
    </ul>
    
    <!-- 按钮切换区域 -->
    <ul class="handoff">
        <!-- 左切换按钮 -->
        <li class="handoffBtn left"></li>
        
        <!-- 右切换按钮 -->
        <li class="handoffBtn right"></li>
    </ul>
    
    <!-- 指示器存放区域 -->
    <ul class="indicator">
        ...
    </ul>
</div>
```

