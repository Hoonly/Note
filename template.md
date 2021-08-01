# 03. 函数模板

## <font color=cyan>01. 显示指定模板参数</font>

## <font color=cyan>02. 函数模板实例化</font>

> *If you have several identical instantiations, even in different modules, only one copy of the instantiation will end up in the executable file.*

## <font color=cyan>03. 使用extern关键字阻止类成员函数自动实例化</font>

## <font color=cyan>04. 数模板特化</font>

> <font color=red>模板特化是为了针对特定类型需要实现特殊行为设置的，需要有自己的函数体</font>
>
> <font color=red>模板实例化不需要有自己的函数体，和通用模板行为一致</font>

## <font color=cyan>04. 实例化偏序机制</font>

<font color=yellow>如果在函数调用时，参数列表可以匹配多个函数模版，则选择最特化的那一个: 如果一个模版参数列表有效适配另一个模版，但是反过来不行，那么这个模版就不够特化</font> 

