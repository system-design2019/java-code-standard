# 前言

   本手册以Java开发者为中心视角，划分为编程规约、异常日志、单元测试、安全规约、工程结构、MySQL数据库六个维度，再根据内容特征，细分成若干二级子目录。根据约束力强弱及故障敏感性，规约依次分为强制、推荐、参考三大类。对于规约条目的延伸信息中，“说明”对内容做了适当扩展和解释；“正例”提倡什么样的编码和实现方式；“反例”说明需要提防的雷区，以及真实的错误案例。   
    本手册的愿景是**码出高效，码出质量**。现代软件架构都需要协同开发完成，高效协作即降低协同成本，提升沟通效率，所谓无规矩不成方圆，无规范不能协作。众所周知，制订交通法规表面上是要限制行车权，实际上是保障公众的人身安全。试想如果没有限速，没有红绿灯，谁还敢上路行驶。对软件来说，适当的规范和标准绝不是消灭代码内容的创造性、优雅性，而是限制过度个性化，以一种普遍认可的统一方式一起做事，提升协作效率。代码的字里行间流淌的是软件生命中的血液，质量的提升是尽可能少踩坑，杜绝踩重复的坑，切实提升质量意识。 

# 目录

* [前言](p3c-gitbook.md)
* 一、编程规约
  * [（一）命名风格](bian-cheng-gui-yue/ming-ming-feng-ge.md)
  * [（二）常量定义](bian-cheng-gui-yue/chang-liang-ding-yi.md)
  * [（三）代码格式](bian-cheng-gui-yue/dai-ma-ge-shi.md)
  * [（四）OOP规范](bian-cheng-gui-yue/oop-gui-fan.md)
  * [（五）集合处理](bian-cheng-gui-yue/ji-he-chu-li.md)
  * [（六）并发处理](bian-cheng-gui-yue/bing-fa-chu-li.md)
  * [（七）控制语句](bian-cheng-gui-yue/kong-zhi-yu-ju.md)
  * [（八）注释规约](bian-cheng-gui-yue/zhu-shi-gui-yue.md)
* 二、异常日志
  * [（一）异常处理](yi-chang-ri-zhi/yi-chang-chu-li.md)
  * [（二）日志规范](yi-chang-ri-zhi/ri-zhi-gui-yue.md)
  * [（三）其他](yi-chang-ri-zhi/qi-ta.md)
* [三、单元测试](dan-yuan-ce-shi.md)
* [四、安全规约](an-quan-gui-yue.md)
* 五、MySQL数据库
  * [（一）建表规约](mysql-shu-ju-ku/jian-biao-gui-yue.md)
  * [（二）索引规约](mysql-shu-ju-ku/suo-yin-gui-yue.md)
  * [（三）SQL语句](mysql-shu-ju-ku/sql-yu-ju.md)
  * [（四）ORM映射](mysql-shu-ju-ku/orm-ying-she.md)
* 六、工程结构
  * [（一）应用分层](gong-cheng-jie-gou/ying-yong-fen-ceng.md)
  * [（二）二方库依赖](gong-cheng-jie-gou/er-fang-ku-yi-lai.md)
  * [（三）服务器](gong-cheng-jie-gou/fu-wu-qi.md)
* [七、RESTful设计规范](qi-restful-she-ji-gui-fan.md)

