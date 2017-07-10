声明方法
:root{
	--theme-color:gray;
}
使用方法
.button{
	color:var(--theme-color);
}
这样就可以一次声明，全局使用，修改起来也很简单。

css 计算函数使用calc();
.image-grid > .image {
  margin: 8px;
  width: calc(100% - 16px);
}