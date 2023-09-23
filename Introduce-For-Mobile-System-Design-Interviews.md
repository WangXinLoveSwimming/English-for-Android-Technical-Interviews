## Script
今天和大家讲讲中西方移动端开发职位面试的最大差异， 就是目前国外面试会引入系统设计这个环节。大家都知道这几年国内大厂和一般互联网公司喜欢用leetcode来考察开发人员的技术水平， 但有些题目过于怪癖， 以我在外企， 包括一段时间在欧洲的工作经历， 还有这几年在国内大厂的实际工作中， 其实很难用到这些算法知识， 绝大部分公司的业务是集中在应用层面， 并不需要去攻克那些技术难题。所以大家调侃说， 招聘时要求会做航天飞机， 实际来了后去拧螺丝钉。 相比之下， 系统设计会更加的务实， 更能反应开发人员在之前工作中积累的经验， 因此， 现在国内大厂也开始重点引入系统设计。 那么针对， 未来打算去国外工作的人来说， 有些英文表达是需要单独重点准备的。 在视频最后， 我会列出来一些核心词汇和用法的中英文对照表。
那么好， 今天来讲第一个题目。如果面试官让你文件下载库， 你要如何来回答。 我会尽量用中文先讲一遍， 然后用英文再重复一遍， 让大家熟悉比较地道的英文表达。

第一步， 收集需求信息。先不要紧张， 给自己2分钟脑子里想一下自己用这个产品或是功能时， 最常用的几个核心功能。之后要和面试官明确和缩小需求范围, 明确核心要求。
例如， 你可以问， 对文件类型, 文件尺寸是否有限制， 下载后的文件是否要保存到本地。是否要支持暂停， 取消和继续， 是否需要有个页面来展示下载列表。是否要支持并行下载。对并行下载的数量是否要有限制。
是否支持断点续传， 和是否要处理登录认证。
通过这些问题， 一方面达到MVP (Minimum Viable Product)的要求， 避免找不到重点， 另一方面， 可以体现你和产品经理是否能够高效沟通， 这都是你之后在国外入职非常重要的特质。

然后列出来
Functional requirements
和
Non-functional requirements
和非必要功能
Out of scope


第二步， 给出high level design 和核心的Client Public API (Optional)
面试官可能会对他感兴趣的module， 更深入的问一些问题。


Major Concerns and Trade-Offs



## refer
[https://proandroiddev.com/a-simple-framework-for-mobile-system-design-interviews-89f6f4134b84](https://proandroiddev.com/mobile-system-design-exercise-file-downloader-library-ccb8ac0e5be4)

## Vocabulary

|     英文                       	|     中文              	|     音标           	|     重要程度    	|
|--------------------------------	|-----------------------	|--------------------	|-----------------	|
|     build a robust system         	|     建立一个健壮的系统            	|        	|     🌟🌟🌟🌟🌟       	|
|     MVP (Minimum Viable Product)         	|     最小可运行产品            	|        	|     🌟🌟🌟🌟🌟       	|
|     encapsulate         	|     封装            	|    /ɪnˈkæpsjuleɪt/    	|     🌟🌟🌟🌟🌟       	|
|     time complexity            	|     时间复杂度        	|     kəmpleksɪti    	|     🌟🌟🌟🌟🌟       	|
|     n squared                  	|     n的平方           	|     skweəʳd        	|     🌟🌟🌟🌟🌟       	|
|     length                     	|     长度              	|                    	|     🌟🌟🌟🌟🌟       	|
|     array                      	|     数组              	|     əreɪ           	|     🌟🌟🌟🌟🌟       	|
|     element                    	|     元素              	|     elɪmənt        	|     🌟🌟🌟🌟🌟       	|
|     store                      	|     存储              	|                    	|     🌟🌟🌟🌟🌟       	|
|     key-value pair             	|     键值对            	|                    	|     🌟🌟🌟🌟🌟       	|
|     iterate over / go through this array    	|     遍历这个数组      	|     ɪtəˌreɪt       	|     🌟🌟🌟🌟🌟       	|
|     sum up to                  	|     总和为            	|                    	|     🌟🌟🌟🌟🌟       	|
|     add / plus                 	|     加上              	|                    	|     🌟🌟🌟🌟🌟       	|
|     index / indices            	|     索引 （单/复）    	|                    	|     🌟🌟🌟🌟🌟       	|
|     declare a variable         	|     声明一个变量      	|     dɪkleəʳ        	|     🌟🌟🌟🌟🌟       	|
|     is equal to / equals       	|     等于              	|     iːkwəl         	|     🌟🌟🌟🌟🌟       	|
|     minus         	|     减去              	|     maɪnəs         	|     🌟🌟🌟🌟🌟       	|
|     combination                	|     组合              	|     kɒmbɪneɪʃən    	|     🌟🌟🌟         	|
|     Repeat the same steps      	|     重复同样的步骤    	|                    	|     🌟🌟🌟         	|
|     In this case               	|     在这种情况下      	|                    	|     🌟🌟🌟         	|
|     by default                 	|     默认              	|     dɪfɔːlt        	|     🌟🌟🌟         	|
|     find out                   	|     发现              	|                    	|     🌟🌟          	|
|     difference                 	|     差值              	|                    	|     🌟🌟          	|
|     move on to                 	|     移动到            	|                    	|     🌟🌟          	|
