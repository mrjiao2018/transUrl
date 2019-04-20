### 练手项目
在github上建项目，所用技术也应给出具体的引导，与我们用的技术栈匹配上。
后端
1. 用Go实现一个URL短连接系统，类似于 http://dwz.cn/ ，采用 https://github.com/gin-gonic/gin 这个框架
2. 第1阶段可以先在单进程实现，长短url实现在存放在进程内就好
3. 第2阶段可以将长短url的关联关系放到MySQL中，MySQL驱动采用 https://github.com/jinzhu/gorm 
4. 第3阶段为了提高性能，将热点url放到Redis中缓存，全量数据仍然放到MySQL中 https://github.com/go-redis/redis
5. 每一阶段实现完，做压测、性能调优。没有实验环境的可以尝试使用阿里云
更多题目，请大家一起来出 @洪晓东 @吴英强 @adam 
曾佳的作业：https://github.com/zengjia007/transurl

go 资料：
1.电子书： http://www.runoob.com/go/go-tutorial.html
2.书籍: https://item.jd.com/12187988.html