## iframe里阻止嵌套请求
在response-headers里
X-Frame-Option：sameoption

## a元素与iframe结合使用
当iframe中嵌套一个a标签
a元素的target：_self，在iframe内部中打开
a元素的target：_parent，在iframe外层父窗口中打开
a元素的target：_top，多层嵌套，在iframe顶层窗口中打开
a元素的target：_blank，在新窗口中打开