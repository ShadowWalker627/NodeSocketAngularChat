# NodeSocketAngularChat
NodeJS + Socket.IO + AngularJS 聊天应用
#0811
添加 Enter 键发送消息：
<input ng-keyup="$event.keyCode == 13 && myFunc()" ...>(来自 StackOverflow) 在 myFunc 中要添加 event.preventDefault()
