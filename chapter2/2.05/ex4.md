本题不做代码编写,因为..

如提示所说问题转化为归并排序。分布到m个机器上计算。每个机器提供K'个文档。使得归并之后可以从这m*K'个文档中取出K个，使得结果包括理想结果的90%。

要求算出K'的值

对于特定的机器，它包含全部文档前K排名的文档个数期望值是K/m, 要达到90%准确率的期望值，则每台机器要提供90%*K/m个最佳文档。

当然，如果想保证90%， 则每台机器要提供90%*K

网上提供另一种做法，对每台机器维护一个堆，然后对堆顶归并
