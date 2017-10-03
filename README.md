# 存在bug

当从rectangle工具切换到dots时，再把鼠标移到rectangle上，
之前取消的rectangle会重新显示。可能是因为onmousedown, onmousemove等几个造成的


完三个点后，不移动鼠标，不会显示三条边，移动一下鼠标，就会显示三条边，这个是由onmousemove造成的。
##需要完善

0. debug
1. 实现使用click来模糊标记，并显示模糊标记。
2. 框一片区域，批量改label的功能，为以后进一步修改数据细分label准备。
3. moveout the ugly whencheck(), use hide attribute, first make every thing to be object, then choose to hide or display.