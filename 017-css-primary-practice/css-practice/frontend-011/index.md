<!-- 分析选择器权重 -->
a（0,0,0,1）
.active (0,0,1,0)
#yo (0,1,0,0)
a.active (0,0,1,1)
.box .active (0,0,2,0)
body a.active (0,0,1,2)
.box a.red span (0,0,2,2)
.box a.red .item (0,0,3,1)
#yo .box a.hide (0,1,2,1)
#yo > a.active:hover (0,1,2,1)
html .box:hover (0,0,2,1)
style="..."" (1,0,0,0)