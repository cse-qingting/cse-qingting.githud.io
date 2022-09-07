###阻止dom节点的冒泡

-e.stopPropagation() 完成了当前节点的动作以后阻止冒泡

### DOM节点的类型
 
- nodeType属性返回节点类型的常数值。
	不同的类型对应不同的常数值，12种类型分别对应1到12的常数值
-html dom节点
	- 元素节点  Node.ELEMENT_NODE(1)
		- 对应网页的HTML标签元素
	- 属性节点  Node.ATTRIBUTE_NODE(2)
		- 对应网页中HTML标签的属性
	- 文本节点  Node.TEXT_NODE(3)
		- 代表网页中的HTML标签内容
	- CDATA节点  Node.CDATA_SECTION_NODE(4)
		- 只针对基于XML的文档，只出现在XML文档中，表示的是CDATA区域
	- 注释节点  Node.COMMENT_NODE(8)
		- 表示网页中的HTML注释
	- 文档节点  Node.DOCUMENT_NODE(9)
		- 表示HTML文档，也称为根节点，指向document对象
	- 文档类型节点  Node.DOCUMENT_TYPE_NODE(10)
		- 包含着与文档的doctype有关的所有信息
	- 文档片段节点  Node.DOCUMENT_FRAGMENT_NODE(11)
		- 在文档中没有对应的标记，是一种轻量级的文档，可以包含和控制节点，但不会像完整的文档那样占用额外的资源
	- DTD声明节点  Node.NOTATION_NODE(12)
		- 代表DTD中声明的符号
-xml dom节点
	- 实体名称节点  Node.ENTITY_NODE(6)
		- 实体是一个声明，指定了在XML中取代内容或标记而使用的名称
	- 实体引用名称节点 Node.ENTRY_REFERENCE_NODE(5)
		- 实体包含两个部分， 首先，必须使用实体声明将名称绑定到替换内容。其次，在实体声明中定义的名称随后将在 XML 中使用
	
	- 处理指令节点  Node.PROCESSING_INSTRUCTION_NODE(7)
- nodeName属性返回节点的名称

- nodeValue属性返回或设置当前节点的值，格式为字符串

### dom节点的操作（增删改查）

- 增
	- 创建元素
		- createElement("标签名")
	- 创建文本
		- createTextNode("文本")
	- 创建属性
		- setAttribute("属性名","属性值")
	- 追加到尾部
		- appendChild(子节点)
	- 插入到某个元素的前面
		- insertBefore(新元素,旧元素)
- 删
	- removeChild(子节点)
- 改
	- 修改节点的属性和该节点包含的文本
		- setAttribute(“属性名”,“值”)

- 查
	- 根据Id获得单个元素
		- getElementById 
	- 根据标签名获得元素数组
		- getElementsByTagName	
	- 通过利用属性来获取指定父节点下的所有子节点
		- getElementsByClassName


