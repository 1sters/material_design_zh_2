
# 响应式交互

响应式交互能让用户信任，并且吸引他们。 当用户操作一个美观且符合常理的应用时，他们会感到满意甚至很高兴。那是一种经过深思熟虑、有目的、非随机的而且可以带有轻微异想天开但不会让人分心的交互。

在 material design 中，应用是响应式的并且渴望用户操作的：

  * 触摸，语音，键盘及鼠标作为首要考虑的输入方式。
  * 虽然 UI 元素是有形的，但是他们被限制在屏幕里面（电脑或者移动设备的屏幕），视觉元素和动效能减少这种割裂，让用户能够立即感知自己的操作。

响应式交互把一个应用从简单展现用户所请求的信息，提升至能与用户产生更强烈、更具体化交互的工具。

表层响应


<video src="http://materialdesign.eoemobile.com/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.mp4" controls="controls" width="740" loop height="350"></video>      

元素响应

<video src="http://materialdesign.eoemobile.com/animation-responsive-interation-radialReact-example_large_xhdpi.mp4" controls="controls" width="740" loop height="350"></video>       

径向响应

## 表层响应

接收到输入事件，如点击屏幕，系统会立即在交互的触点上绘制出一个可视化的图形让用户感知到：如在点击屏幕时、使用麦克风时，或者键盘输入时，会出现类似于墨水扩散那样的视觉效果形状。

触控涟漪是这种触摸效果的核心视觉机制。在进行触摸事件时，设备能清晰而及时地让用户感知触摸按钮和语音输入时的变化。


### 最佳范例

在输入事件对应的位置上，例如：在手指的点击位置或者讲话的时候，屏幕上麦克风的图标位置会出现一个扩散的视觉元素。


<video crossorigin="anonymous"  loop  controls width="740" height="350">
<source src="http://materialdesign.eoemobile.com/animation-responsiveinteraction-surfacereaction-030202_TouchRipple_PressRelease_xhdpi_002.mp4">
</video>      

触控涟漪-点击/释放

<video crossorigin="anonymous"  loop  controls width="740" height="350">
<source src="http://materialdesign.eoemobile.com/animation-responsiveinteraction-surfacereaction-030202_TouchRipple_DragRelease_xhdpi_002.mp4">
</video>       

触控涟漪-拖进/拖出


## 元素响应

和表层响应的触控涟漪一样，每个元素本身也能做出交互响应，物体可以在触控或点击的时候浮起来，以表示该元素正处于激活状态。用户可以通过点击、拖动来生成、改变元素或者直接对元素进行处理。


## 最佳范例


### 以触控点为原点展开新元素的动画

当用户操作生成一个新元素时，元素的动画应该基于触控点展开。

<video crossorigin="anonymous"  loop  controls width="740" height="350">
<source src="http://materialdesign.eoemobile.com/animation-responsiveinteraction-materialresponse-PointOfOrigin_DO_003.mp4">
</video>   

<p> <font color="green">(上图)可取</font></p>
元素从触控点展开时，通过视觉效果将元素与触控点联系起来。

<video crossorigin="anonymous"  loop  controls width="740" height="350">
<source src="http://materialdesign.eoemobile.com/animation-responsiveinteraction-materialresponse-PointOfOrigin_DONT_003.mp4">
</video>    

<p> <font color="red">(上图)不可取</font></p>
卡片元素从屏幕正中央出现，用户无法把触控点与卡片元素联系起来。


### 点击浮动

当卡片元素或可分离元素被激活时，应该浮起以表明正处于激活状态。

<video crossorigin="anonymous"  loop  controls width="740" height="350">
<source src="http://materialdesign.eoemobile.com/animation-responsiveinteraction-materialresponce_liftontouch_xhdpi_002.mp4">
</video>     

点击浮动

## 径向响应

所有的用户交互行为中都会有一个中心点，他们想通过该中心点来达到自己的目的。

作为用户关注的中心点，应该绘制一个明显的视觉效果来让用户清晰地感知自己的输入（触摸屏幕、语音输入等）。在用户的操作中心点应该形成一个像涟漪一样逐渐发散开的径向动效响应。

所有输入都有中心点，涟漪效果应从触控点、语音时屏幕上的语音图标、键盘输入时具体的按键点击位置上展开。

这些输入动作产生时都应该在中心点形成一个视觉上的关联，从中心点展开一连串动作产生的涟漪效果。

> 原文：[Responsive Interaction](http://www.google.com/design/spec/animation/responsive-interaction.html) 翻译：[7heaven](https://github.com/7heaven) 校对：[KongZhen](https://github.com/KongZhen)
I
