# zkillborad 进阶搜索

zkillborad 通常只能搜索某一船只的击毁，而无法指定某一星系，因为地区的不同，每艘船的配置也将不同，较难提供装备的参考。

但是通过编辑 URL（网页地址）的方式，即可进行所需的过滤

其中类似角色 ID，舰船 ID，星系 ID，可通过自行在 zbk 搜索并复制网址对应数字获得

注：**url 最后需保留反斜杠 /**

以下是比较基本的链接

| url | 描述 |
| :--- | :--- |
| [https://zkillboard.com/kills/5b/](https://zkillboard.com/kills/5b/) | 超过 5B 的 km |
| [https://zkillboard.com/kills/10b/](https://zkillboard.com/kills/10b/) | 超过 10B 的 km |
| [https://zkillboard.com/kills/bigkills/](https://zkillboard.com/kills/bigkills/) | 旗舰的 km |
| [https://zkillboard.com/kills/citadels/](https://zkillboard.com/kills/citadels/) | 建筑的 km |
| [https://zkillboard.com/kills/awox/](https://zkillboard.com/kills/awox/) | 蓝星击杀的 km |
| [https://zkillboard.com/kills/t1/](https://zkillboard.com/kills/t1/) | T1 的 km，可通过修改 url 自定义 t\[n\] |
| [https://zkillboard.com/kills/frigates/](https://zkillboard.com/kills/frigates/) | 护卫舰的 km，可通过修改 url 自定义吨位 |
| [https://zkillboard.com/kills/capitals/](https://zkillboard.com/kills/capitals/) | 小旗舰的 km |
| [https://zkillboard.com/kills/freighters/](https://zkillboard.com/kills/freighters/) | 工业舰、货舰的 km |
| [https://zkillboard.com/kills/rorquals/](https://zkillboard.com/kills/rorquals/) | 大鲸鱼的 km |
| [https://zkillboard.com/kills/supers/](https://zkillboard.com/kills/supers/) | 超期的 km |
| [https://zkillboard.com/kills/solo/](https://zkillboard.com/kills/solo/) | 击杀者仅为 1 人的 km |
| [https://zkillboard.com/kills/nullsec/](https://zkillboard.com/kills/nullsec/) | 在 00 的 km，可通过修改 url 自定义高低安 |
| [https://zkillboard.com/kills/w-space/](https://zkillboard.com/kills/w-space/) | 在虫洞的 km |
| [https://zkillboard.com/kills/ganked/](https://zkillboard.com/kills/ganked/) | 被高安强暴的 km |
| [https://zkillboard.com/kills/abyssal/](https://zkillboard.com/kills/abyssal/) | 在深渊的 km |

下面为你可以直接在 zkb 网站搜到的 url

| url 段 | 描述 |
| :--- | :--- |
| system/systemID | 指定星系的 km（ [https://zkillboard.com/system/30000142/）](https://zkillboard.com/system/30000142/）) |
| character/characterID | 指定角色的 km（ [https://zkillboard.com/character/96393303/）](https://zkillboard.com/character/96393303/）) |
| corporation/corporationID | 指定公司的 km（ [https://zkillboard.com/corporation/1000181/）](https://zkillboard.com/corporation/1000181/）) |
| alliance/allianceID | 指定联盟的 km（ [https://zkillboard.com/alliance/99007498/）](https://zkillboard.com/alliance/99007498/）) |
| faction/factionID | 指定势力的 km（ [https://zkillboard.com/faction/500004/）](https://zkillboard.com/faction/500004/）) |
| ship/shipID | 指定舰船的 km（ [https://zkillboard.com/ship/601/）](https://zkillboard.com/ship/601/）) |
| group/groupID | 指定吨位的 km（ [https://zkillboard.com/group/237/）](https://zkillboard.com/group/237/）) |
| region/regionID | 指定星域的 km（ [https://zkillboard.com/region/10000005/）](https://zkillboard.com/region/10000005/）) |
| constellation/constellationID | 指定星座的 km（[https://zkillboard.com/constellation/20000072/）](https://zkillboard.com/constellation/20000072/）) |

下一段则是本文的重点，也就是可以过滤星系、舰船的部分，可任意组合，更多请自行尝试

| url 段 | 描述 |
| :--- | :--- |
| character/characterID/system/systemID | 指定角色在指定星系的 km\([https://zkillboard.com/character/2113153259/system/30003229/](https://zkillboard.com/character/2113153259/system/30003229/)\) |
| group/groupID/system/systemID/ | 指定星系的指定吨位的\(km\([https://zkillboard.com/system/30002813/group/237/）](https://zkillboard.com/system/30002813/group/237/）) |
| ship/shipID/system/systemID/ | 指定星系的指定舰船的 km（[https://zkillboard.com/ship/596/）](https://zkillboard.com/ship/596/）) |
| character/characterID/ship/shipID/system/systemID/ | 指定角色的指定舰船在指定星系的 km\([https://zkillboard.com/character/2113153259/ship/34590/system/30003258/](https://zkillboard.com/character/2113153259/ship/34590/system/30003258/)\) |
| ship/shipID/abyssal/ | 指定舰船在深渊的 km\( [https://zkillboard.com/ship/626/abyssal/](https://zkillboard.com/ship/626/abyssal/)\) |

以上不难看出一个规律，url 的组成为： [https://zkillboard.com/](https://zkillboard.com/) \[character/角色 ID\] / \[group/吨位 ID\] or \[ship/舰船 ID\] / \[system/星系 ID\]or \[其他地点编号\]

以下提供一些选项的参考

| 选项 | 描述 |
| :--- | :--- |
| lowsec | 低安 |
| highsec | 高安 |
| nullsec | 00 |
| w-space | 虫洞 |
| abyssal | 深渊 |

