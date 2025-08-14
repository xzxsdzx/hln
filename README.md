字母圈论坛(cn)夫妻找单论坛(官方)聚凤楼论坛

这个所谓的自动完成指的是当用户曾经使用过的字符提交[submit]过，保存在浏览器cookie里面的用户使用痕迹。和AJAX里的全文检索Autocomplete是另外一回事。

1. 有时候我们并不需要AutoComplete，例如需要用户自己再次输入而非自动完成。只要将所在表单元素的autocomplete属性设置为off即可。

<form action="form_action.asp">
名字：<input type="text" name="FirstName" value="" autocomplete="off" /><br />
姓氏：<input type="text" name="LastName" value="" autocomplete="on" /><br />
<input type="password" naem="pass" autocomplete="on" /> 在html5中实验过没有起作用 但为了安全起见最好不要加这个。
<input type="submit" value="提交" />
</form>

2. 如果整个表单元素都不使用autocomplete功能的话,做如下设置就可以了.
<form autocomplete="off">
除了<input>还有<textarea>也有这个属性。

