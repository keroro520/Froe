
froe, Scheme interpreter
因为之前看过了天弋娘的代码, 又很喜欢他那优美的码风, 不知不觉就按他的框架来写了.





TODO : 

	* scheme宏		不太了解,待学习
 



Situation 

	* 错误恢复策略 

		* 词法错误 : 结束程序

		* 其他错误 : 给出错误提示, 结束掉该表达式, 继续解析下面的

	* gc
		* 想想还是算了, 虽说原理很简单, 但实现起来好麻烦, 要嵌好多gc语句到代码里.=_=
