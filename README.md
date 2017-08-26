# 存在bug

当从rectangle工具切换到dots时，再把鼠标移到rectangle上，
之前取消的rectangle会重新显示。可能是因为onmousedown, onmousemove等几个造成的

##需要完善

0. debug
1. 实现使用click来模糊标记，并显示模糊标记。