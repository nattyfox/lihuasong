## 文件结构
* 文件分为四个部分，Huluwa.java是葫芦娃类的数据及方法描述，sortByChoreography.java是葫芦娃互相协作排序，sortByOrchestration.java 是旁人指挥排序。
Huluwa继承自Human类，有共享的静态类：抚养着，以及共享的静态方法，回答其抚养着，另外的排行以及名字属于private，提供有读写接口：getRank(),getName(),setRank();setName().
sortByOrchestration.java中有sortByOrchestration类，可视为指挥葫芦娃排序的爷爷，也是继承自Human类，有指挥葫芦娃排序的sort_By_Orchestration方法。

* 整个包放置于nattyfox下

## 类图
[类图](http://www.plantuml.com/plantuml/png/dL7DQiCm33x7Jo7OPQEaZr1ATzak6wmFK4JY9cQ9L2Hb8sHvzvdLX6JDgRxv-_diJzgheLZNDgveK1LUkXPf6ATRqttZuB8SZYQ1AY1ilODqSWXa84YV4xJvWowiBjia--FJZAsyVKJzV-mjnYumNT7ffCiUu8j32GLtP7m-psI9SQExlWvv_hExragbZYnsw9zh5i-LuANk1vTSiKhvIi42DZ4oWHhrfqD_cZiYEoxYtgMelPgW1QOxyrQIOBlTfJ6wstyls5lplFhUKnct_0i0)