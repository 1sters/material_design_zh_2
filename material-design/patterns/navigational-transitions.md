# 导航过渡   

导航过渡是一个应用中状态之间的切换，例如从一个高层级的页面切换到一个具体的页面。最主要，但不是全部，过渡在本质上是层级。

这些转变应该合适地展示用户浏览一个应用的每个状态。

> 父元素到子元素

> 兄弟元素到兄弟元素

## 父元素到子元素   

查看一个应用的更深的层级或者页面，是从父页面开始的。在父页面上会有很多的子页面可供用户浏览，这些都是父页面的子页面。

在 material design 中，高度变化意味着从父元素到子元素的聚焦变化。

### 高度和宽度   

用户触摸的表面应该提升并且扩展到它原生的地方。这种扩张和运动将父元素到子元素的移动高亮，使用 material 运动曲线进行的自然运动。

<video crossorigin="anonymous"  loop  controls width="760" height="350">
<source src="http://materialdesign.qiniudn.com/videos/patterns_navigational-transitions_parent-to-child_list-02_xhdpi_019.mp4">
</video>

父元素到子元素的过渡动画

<video crossorigin="anonymous"  loop  controls width="760" height="350">
<source src="http://materialdesign.qiniudn.com/videos/patterns_navigational-transitions_parent-to-child_calendar_tablet_xhdpi_004.mp4">
</video>

父元素到子元素的过渡动画效果

## 兄弟元素到兄弟元素
兄弟元素之间的过渡是发生于同层级元素之间的过渡。

### 静态高度   

当一个用户通过标签进行导航，将不会有高度变化。每个标签的内容和表面保持同样的高度。兄弟元素向左移出屏幕时，新的内容从右边滑进来。

<video crossorigin="anonymous"  loop  controls width="760" height="350">
<source src="http://materialdesign.qiniudn.com/videos/patterns_navigational-transitions_sibling-to-sibling_tabs-01_xhdpi_013.mp4">
</video>

兄弟元素过渡

<video crossorigin="anonymous"  loop  controls width="760" height="350">
<source src="http://materialdesign.qiniudn.com/videos/patterns_navigational-transitions_sibling-to-sibling_tabs-02_xhdpi_003.mp4">
</video>

兄弟元素到兄弟元素的过渡动画