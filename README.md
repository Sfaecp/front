# front
//解除切屏限制
window.onmouseleave = window.onblur = window.onmouseout = document.onmouseleave = document.onblur = document.onmouseout = document.body.onmouseleave = document.body.onblur = document.body.onmouseout = onmouseleave = onblur = onmouseout = null;
 
//解除选中文本限制（这里html看具体考试页面绑定的限制事件dom而定）
window.onselectstart = document.onselectstart = document.body.onselectstart = onselectstart = document.querySelector("html").onselectstart = null;
 
//解除复制粘贴限制
window.oncopy = window.onpaste = document.oncopy = document.onpaste = document.body.oncopy = document.body.onpaste = oncopy = onpaste = null;
 
//解除右键菜单限制（这里html看具体考试页面绑定的限制事件dom而定）
window.oncontextmenu = document.oncontextmenu = document.body.oncontextmenu = oncontextmenu = document.querySelector("html").oncontextmenu = null;
 
//解除快捷键操作屏蔽
window.onkeyup = window.onkeydown = window.onKeyPress = document.onkeyup = document.onkeydown = document.onKeyPress = document.body.onkeyup = document.body.onkeydown = document.body.onKeyPress = onkeyup = onkeydown = onKeyPress = null;
