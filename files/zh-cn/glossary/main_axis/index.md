---
title: 主轴
slug: Glossary/Main_Axis
translation_of: Glossary/Main_Axis
original_slug: Glossary/主轴
---
<p>主轴是由弹性容器 {{glossary("flexbox")}} 中弹性方向 {{cssxref("flex-direction")}} 属性所定义的的。弹性方向 <code>flex-direction </code> 有 4 个可能的值，分别是：</p>

<ul>
 <li><code>row</code></li>
 <li><code>row-reverse</code></li>
 <li><code>column</code></li>
 <li><code>column-reverse</code></li>
</ul>

<p>选择行 <code>row</code> 或者 <code>row-reverse</code> 反向行，那么主轴方向就会沿着行的走向。</p>

<p><img alt="In this image the flex-direction is row which forms the main axis" src="basics1.png"></p>

<p>选择列 <code>column</code> 或者反向列 <code>column-reverse</code> ，那么主轴就会从上至下沿着块的走向。</p>

<p><img src="basics2.png"></p>

<p>在主轴上，你可以用 <code>flex</code> 属性来增加可用空间，从而控制弹性元素的尺寸，你还可以用 <code>justify-content</code> 属性来控制元素周围的空间、间距。</p>

<h2 id="学习更多">学习更多</h2>

<h3 id="属性参考">属性参考</h3>

<ul>
 <li>{{cssxref("flex-basis")}}</li>
 <li>{{cssxref("flex-direction")}}</li>
 <li>{{cssxref("flex-grow")}}</li>
 <li>{{cssxref("flex-shrink")}}</li>
 <li>{{cssxref("justify-content")}}</li>
 <li>{{cssxref("flex")}}</li>
</ul>

<h3 id="拓展阅读">拓展阅读</h3>

<ul>
 <li>CSS 弹性容器指南： <em><a href="/zh-CN/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox">Basic Concepts of Flexbox</a></em></li>
 <li>CSS 弹性容器指南： <em><a href="/zh-CN/docs/Web/CSS/CSS_Flexible_Box_Layout/Aligning_Items_in_a_Flex_Container">Aligning items in a flex container</a></em></li>
 <li>CSS 弹性容器指南： <em><a href="/zh-CN/docs/Web/CSS/CSS_Flexible_Box_Layout/Controlling_Ratios_of_Flex_Items_Along_the_Main_Ax">Controlling Ratios of flex items along the main axis</a></em></li>
</ul>