# DEMO2

基于 [demo1](https://github.com/hekatech/achrom-css/tree/main/demo1) 修改，添加更多可配置选项的弹幕样式

## 使用方法

在 OBS 浏览器的自定义 CSS 样式框中输入：

```
@import url("https://css.4o.cx/demo2/blive-chat.css");
```

## 可配置项

在上述代码的**下方**添加如下内容：

```
:root {
	--color1: #fff;
	--color2: rgba(0,0,0,.7);
	--color-s: rgba(0,0,0,.5);
	--mark-n: '◇ ';
	--mark-s: '◆ ';
	--cstm-fontsize: 20px;
	--direction: unset;
}
```

`color1` = 普通弹幕背景颜色，如需要半透明效果请使用 rgba()

`color2` = 礼物 / SC 背景颜色，如需要半透明效果请使用 rgba()

`color-s` = 弹幕框下阴影颜色

`mark-n` = 普通弹幕发送者 ID 前缀字符，请不要删除空格

`mark-s` = 主播 / 房管 / 大航海用户 ID 前缀字符，请不要删除空格

`cstm-fontsize` = 弹幕正文字体大小，其它字符和图标尺寸会等比例缩放

`direction` = 弹幕流对齐的位置，`unset` 是靠下方对齐，`relative` 为靠上方对齐
