# tree
一款基于JavaScript原生的树形菜单插件，非常小巧简洁，只通过一个tree（）函数就可以快速形成一个树形菜单！

# 说明
tree(id,json,open)

id：{String} 树形菜单的容器

json：{Array Json String} 树形菜单的json数据或者数组，也可以是字符串的json格式数据或者数组，为空将自动格式化该id容器的静态树形菜单

open：{Boolean} 树形菜单是否全部展开，默认为全部收缩

# 例子
新建一个树形菜单的div容器，设一个id，名字任意

&lt;div id="tree"&gt;&lt;/div&gt;

例子1：tree('tree') 将自动格式化id为tree中的静态树形菜单（具体格式请参照tree.html中&lt;div id="tree"&gt;&lt;/div&gt;中的格式）

例子2：tree('tree', json) 将传入的json数据自动格式化为html格式的树形菜单，并将格式化后的数据传入id为tree的div中

例子3：tree('tree', json, true) 如果第三个参数为true，格式化后的数据将展开全部树形菜单，默认为false，可不填
