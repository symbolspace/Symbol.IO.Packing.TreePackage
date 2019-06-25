# 程序集    [使用说明](https://github.com/symbolspace/Symbol.IO.Packing.TreePackage/wiki/Home)
> 运行时支持 .net framework v2.0/3.5/4.0/4.5、.net standard 2.x、.net core app 2.x。

* Symbol.IO.Packing.TreePackage.dll [![Available on NuGet https://www.nuget.org/packages/Symbol.IO.Packing.TreePackage/](https://img.shields.io/nuget/v/Symbol.IO.Packing.TreePackage.svg?style=flat)](https://www.nuget.org/packages/Symbol.IO.Packing.TreePackage/) 


# 最近更新   [版本历史](https://github.com/symbolspace/Symbol.IO.Packing.TreePackage/wiki/Version-history)
> v4.0.0.2 2019-06-26
* 分离到子仓库；
* 本次没有重大更新，可以选择不更新；

# 简介
> 为兼容以前的老项目移植，可以视情况使用它。

* 类似JSON结构的Tree结构体，早期没有JSON的时候开发的；
* 支持基础类型的保存：int、long、bool、byte、string、DateTime等；
* 支持TreePackage嵌套保存结构；
* 与JSON不同之处在于，它可以为key/value设置特殊的属性，不仅限于数据；
* 支持加密，加密算法可以扩展改进；
* 对数据较大的对象可以选择压缩算法；
