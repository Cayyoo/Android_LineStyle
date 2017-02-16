# LineStyle线条的各种样式

样式：
 * corners ----------圆角
 * gradient ----------渐变
 * padding ----------内容离边界距离
 * size　------------大小　
 * solid 　----------填充颜色
 * stroke ----------描边
 * 说明：corners的属性bottomLeftRadius为右下角、bottomRightRadius为左下角

-----

 注意：
 * 1.、如果在<stroke>标签中设置了android:width，则在<View>标签中android:layout_height的值必须大于android:width的值，否则虚线不会显示。<br/>
       如果不设置，默认android:width为0。
 * 2.、关于4.0以上设备虚线会变实线的问题：
      代码中：line.setLayerType(View.LAYER_TYPE_SOFTWARE, null);<br/>
      或者<br/>
      XML中：android:layerType="software"

<br/>
      
 ![screenshot](https://github.com/ykmeory/LineStyle/blob/master/screenshot.jpg "截图")
