# 仓库过滤

> 创建仓库过滤条件可以快速选出想要显示的物品种类，科技等级，衍生等级

## 创建

打开仓库，点击左下角 `+`

![](https://github.com/YunYuyuko/Fored/tree/8d1cf07bcc7d93b307afa258f4bd500fa6959b9f/.gitbook/assets/snipaste_2020-08-22_11-08-50.png)

之后即可根据自己需求创建规则

比如：`为真` 即为**过滤出**目标物品，`为假` 则为**过滤掉**目标物品

![](https://github.com/YunYuyuko/Fored/tree/8d1cf07bcc7d93b307afa258f4bd500fa6959b9f/.gitbook/assets/snipaste_2020-08-22_10-59-45.png)

还可过滤科技等级、衍生等级，创建多个规则

![](https://github.com/YunYuyuko/Fored/tree/8d1cf07bcc7d93b307afa258f4bd500fa6959b9f/.gitbook/assets/snipaste_2020-08-22_11-06-15.png)

## 例子

> 以下搬运自[eveuniversity](https://wiki.eveuniversity.org/Filters)

### 所有驱逐舰

![](https://github.com/YunYuyuko/Fored/tree/8d1cf07bcc7d93b307afa258f4bd500fa6959b9f/.gitbook/assets/400px-filter_destroyers.png)

由于我们有四种类型的驱逐舰（T1 /拦截/指挥驱逐舰/战术驱逐舰），我们如果需要创建一个过滤出所有驱逐的条件，可以通过创建以下规则：

* 组为驱逐舰
* 组为拦截舰
* 组为指挥驱逐舰
* 组为战术驱逐舰

### 所有CPU低于30的非T1弹道控制系统

![](https://github.com/YunYuyuko/Fored/tree/8d1cf07bcc7d93b307afa258f4bd500fa6959b9f/.gitbook/assets/400px-filter_bcs.png)

我们希望过滤出所有**CPU低于30.0的非Tech 1 BCS**。我们将创建三个规则，分别过滤一个条件（CPU /非T1 / BCS）：

* 组为装备，小组为弹道控制系统
* CPU使用率小于30.0
* 科技等级非T1

### 所有烟花，雪球

![](https://github.com/YunYuyuko/Fored/tree/8d1cf07bcc7d93b307afa258f4bd500fa6959b9f/.gitbook/assets/400px-firefilter_workssnowballs.png)

我们要过滤名称中包含烟火或雪球的所有物品。我们将创建两个规则：

* 名称包含烟火
* 名称包含雪球

