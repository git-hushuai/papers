+ Swift实现懒加载必须使用"Var"关键字来定义延时加载的属性，而不可以使用let关键字，因为let关键字定义的是常量，而常量必须在实例创建时赋值，Swift中懒加载的规则，即”后面通过等号赋值一个闭包，闭包后面必须“