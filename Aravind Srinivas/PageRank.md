# Larry Page and Sergey Brin

## transcript

**Lex Fridman**[(00:32:15)](https://youtube.com/watch?v=e-gwvmhyU7A&t=1935) So what do you find inspiring about Google, about those two guys, Larry Page and Sergey Brin and just all the things they were able to do in the early days of the internet?

**Aravind Srinivas**[(00:32:39)](https://youtube.com/watch?v=e-gwvmhyU7A&t=1959) First of all, the number one thing I took away, there’s not a lot of people talk about this is, they didn’t compete with the other search engines by doing the same thing. They flipped it like they said, “Hey, everyone’s just focusing on text-based similarity, traditional information extraction and information retrieval, which was not working that great. What if we instead ignore the text? We use the text at a basic level, but we actually look at the link structure and try to extract ranking signal from that instead.” I think that was a key insight.

**Lex Fridman**[(00:33:20)](https://youtube.com/watch?v=e-gwvmhyU7A&t=2000) Page rank was just a genius flipping of the table.

**Aravind Srinivas**[(00:33:24)](https://youtube.com/watch?v=e-gwvmhyU7A&t=2004) Page rank, yeah. Exactly. And the fact, I mean, Sergey’s Magic came like he just reduced it to power iteration and Larry’s idea was, the link structure has some valuable signal. So look, after that, they hired a lot of grade engineers who and came and built more ranking signals from traditional information extraction that made page rank less important. But the way they got their differentiation from other search engines at the time was through a different ranking signal and the fact that it was inspired from academic citation graphs, which coincidentally was also the inspiration for us in Perplexity, citations. You are an academic, you’ve written papers. We all have Google scholars, we all, at least first few papers we wrote, we’d go and look at Google’s scholar every single day and see if the citation is increasing. There was some dopamine hit from that, right. So papers that got highly cited was usually a good thing, good signal.

[(00:34:23)](https://youtube.com/watch?v=e-gwvmhyU7A&t=2063) And in Perplexity, that’s the same thing too. We said the citation thing is pretty cool and domains that get cited a lot, there’s some ranking signal there and that can be used to build a new kind of ranking model for the internet. And that is different from the click-based ranking model that Google’s building. So I think that’s why I admire those guys.



# 思考

Aravind Srinivas 强调了"除了text-based similarity等文本信息，还有哪些ranking signal -- link structure" 这个和吴军老师强调的寻找更多的信息，是一个意思



“domains that get cited a lot, there’s some ranking signal there ”，这里提到了 cited a lot，很关键。如果不是大量的，容易失去统计意义



“that is different from the click-based ranking model that Google’s building. ” 这里又提到了Google建立的是一个click-based的ranking model。那什么domain适合click-based，什么domain适合citation-ased？

在大健康这个背景下，严肃医疗问答这个domain，其实不太适合click-based；而健康养生的domain（那些XHS的风格），其实适合click-based。



# 硅谷来信2 谷歌方法论 第92封信，谈谈主观性和客观性



# 原文字幕

十年多前，我在Google负责一些和搜索质量相关的项目。我们的目标当然是把搜索质量做好，不过什么算是质量好，我们其实内部就有些争议。但是我们有一个共识，就是搜索结果的排名要客观，不能像一些搜索引擎那样，谁给钱多，就给谁排在前面。

但接下来，就有几个同事（主要是一些很天真又爱较真的美国人）提出，怎么证明我们根据算法给出的排名就一定是客观的呢？因为算法本身也是人写的，比如Google两位创始人发明的Page Rank算法，它被认为是非常客观地反映了网页质量高低的，但是这个算法所说的网页质量，无非是其他网页通过链接变相投票投出来的。**如果你相信这种投票的有效性，那么它就是客观的，如果你不相信，那么它不过是符合某个信息论原理人为创造的算法的结果。**

因此，我们在后来更多地强调我们的搜索结果是算法产生的结果，没有因为广告商出钱就人为地调整结果，而不专门宣传它是客观的。

Google的搜索，从本质上讲是一种特定的，过滤没用信息，挑出有用信息的工具。它背后的信念是相信互联网的内容能够自己组织起来，好的内容自然而然地获得更多的链接。在很长的时间里，这种做法本身被认为是反映了客观事实的。

但是到了2006年，Google这个信念的挑战者长大了，Facebook从Google抢走了很多流量。Facebook从本质上讲，提供了另一种组织信息，过滤信息的方法，那就是以你信得过的人（朋友圈）以及所谓有影响力的人（大咖们）为过滤信息的依据，当然那些大咖肯定也是你信服的人。这种组织信息的方式你可以认为是主观的，但是很多时候它给你的结果并不差，甚至不比Google差。当然，当世界上存在至少两种有效的组织信息的形式之后，Google挑了一种，这个行为本身其实也是主观的了。



# 思考

其实从问题分类角度，可以有一个基本的判断。哪些问题是主观题（你怎么看待最近几年中美关系发展趋势），哪些问题是客观题（英伟达市值多少）。



那在大健康领域，是不是所有的问题都是客观题呢？（很难相信）其实不是的。譬如一些大专家有自己的观点，譬如Aravind Srinivas提到的COVID的起源（至今尚不明确）



# 原文字幕

在Google工作的后几年，是我相对有时间深入思考一些问题的时期。我对主观性和客观性的思考就源于那个时期的工作。此外，还有两件事让我对主观、客观这一对哲学概念有了更深入的看法。在此之前，我和大家一样，从中学开始接受辩证唯物主义的世界观，是坚定的反对主观，支持客观的人。

第一件事是源于当时Google打的一系列官司。世界上永远是树大招风，当Google上市后，就有一些小公司告Google，说Google的排名不公平，影响了它们的流量。Google没有费太大劲就打赢了这些官司，而打赢官司的方法，说起来奇怪。Google没有向法官陈述自己的排名算法多么客观，反而是引用了宪法的第一修正案，即关于言论自由。也就是说，Google不需要把排名做到绝对客观公平，它可以自由地表达自己的意愿，而它的排名就是它主观意愿的表达。这件事你听起来可能觉得是个悖论，**以追求客观性为目标的Google，打赢官司反而要靠强调主观性。**

第二件事是当时我们有几个工程师在跟高盛和摩根士丹利打擂台，看谁管理资本的回报高，最后的结果是我们赢了，毕竟他们的工程素养比我们差很多，因此做到客观判断市场并不容易



# 硅谷来信2 谷歌方法论 周末放送 谷歌的早起岁月



## 原文字幕

由于当时计算机容量和速度的限制，早期的搜索引擎都存在一个共同的问题：收录的网页太少，而且只能对网页中常见内容相关的实际用词进行索引。对于虚词，比如英语中的to、be和not等是不做索引的。那时，用户难以找到很相关的信息。为了查找一点信息，常常要换好几个搜索引擎

后来DEC为了展示其64位处理器Alpha的超强计算能力，开发了AltaVista搜索引擎，只用一台Alpha服务器，却收录了比以往引擎都多的网页，而且对里面的每个词都进行了索引。

AltaVista一个最经典的搜索查询就是莎士比亚的名句“是生存还是毁灭（to be or not to be）”，里面6个词全部是虚词，以前任何搜索引擎都无法对它进行查找，而AltaVista可以。

于是AltaVista一夜之间成为最流行的搜索引擎。AltaVista虽然能让用户搜索到大量结果，但大部分结果却与查询不太相关，有时找想看的网页需要翻好几页

在信息检索的学术界有两个衡量搜索质量好坏的客观标准，即查全率（Recall）和查准率（Precision）。相比早期的搜索引擎，AltaVista解决了覆盖率（查全率）的问题，但在查准率上还没有什么突破，佩奇和布林决定在这方面做点研究

当时整个学术界和工业界对搜索查准率的研究仍然局限于萨尔顿确定的、针对图书馆文献检索的关键词加权平均的框架。虽然一些学者看到了互联网网页之间的相互联系，但是由于习惯性思维的限制，无非是把这种联系作为一个新的信号，对已有的方法修修补补，因此效果并不好。

佩奇和布林本来不是研究文献检索的，头脑里没有那些条条框框，于是得以从一个全新的角度看待互联网及其搜索问题。

我们问佩奇是如何想到PageRank算法的。他说：“**当时我们觉得整个互联网就像一张大的图（Graph），每个网站就像一个节点，而每个网页的链接就像一个弧。我想，互联网可以用一个图或矩阵描述，我也许可以用这个发现做篇博士论文。**”



# 硅谷来信 第294封信｜Google网页排名算法和传播效果

## 原文字幕

有人讲应该相信官方网站的，不过这又带来两个问题，一个是以当时的互联网搜索技术，只有70%的官方网站能出现在搜索结果的第一位，当时如果在网络上用雅虎或者Alta Vista搜索“清华大学”，说不定是哪条新闻的结果，而不是官网的链接会出现在第一位。第二个问题是很多时候大家也未必相信官方网站的说法，今天中国的网民更是如此。

最终，他们二人想到了用一种民主表决的方式来解决这个问题。打个具体的比方，要在众人中确认谁是“罗胖” （得到App的罗振宇老师），就让大家投票指认，得票多的人就是真的罗胖，其他的可能是同名同姓的人。**具体到搜索网页信息上，就是用指向某一个网页的相关超链接的数量和超链接里面的文字对这个网页作一个表决。**

当然这种做法还有一个问题，就是一人一票似乎不太公平，要确认罗胖，最好是多听一些熟悉他的人，以及说话有影响力的人的声音，比如罗辑思维CEO脱不花和罗辑思维的工作人员，而对其他人的声音给予的重视程度应该低一些。

但接下来的问题是，如何确立每个人的声音是否重要呢？于是佩奇和布林就想了，干脆我们把每一个人意见的重要性打一个分数，做一个排序。比如脱不花的意见重要性是0.3，我的意见重要性是0.25，罗辑思维其他一些同事的重要性分别是0.15，0.1......，假定我们都证明罗胖就是得到App的罗振宇老师，那么把我们意见的重要性加起来，就是罗胖的得分（假定为30.5）。

假如另外还有一个同名同姓的罗振宇，也有人给他投票，那个人的得分是0.77，这样一来，当大家要找罗振宇时，罗胖（得到App的罗振宇老师）就跑到第一位了，因为他的得票多。如果后面那个同名的罗振宇要冒充罗胖，那可不容易，即便他找到一大堆人给他投票，但是除非找到了网上的大咖支持，否则一大堆重要性只有0.00001的人加起来，也没有多少权重。

而网上的大咖能否轻易地被收买呢？也不能，因为大咖们的意见重要性的权重，又是由网络上其他人决定的，如果他们胡乱地投了票，他们自己的权重就逐渐下降了。因此，这个方法看上去似乎很完美。



当然这里面有很多数学的问题，就是如何计算那些权重，这个问题应该是布林解决的，他们二人将这种计算出来的权重称为网页排名（PageRank），而用网页排名实现搜索的程序，应该是佩奇写的。



## 思考

吴军老师讲的 "就是如何计算那些权重，这个问题应该是布林解决的"，

"我们问佩奇是如何想到PageRank算法的。他说：'当时我们觉得整个互联网就像一张大的图（Graph），每个网站就像一个节点，而每个网页的链接就像一个弧。我想，互联网可以用一个图或矩阵描述，我也许可以用这个发现做篇博士论文。' "

和Aravind Srinivas 提到的"Sergey’s Magic came like he just reduced it to power iteration and Larry’s idea was, the link structure has some valuable signal. "

是一致的



吴军老师讲到 "具体到搜索网页信息上，就是用指向某一个网页的相关超链接的数量和超链接里面的文字对这个网页作一个表决"

这里涉及到了2个不同维度的特征，"超链接的数量"，"超链接里面的文字"，那PageRank是否用到了"超链接里面的文字"？通过《数学之美》的介绍，应该是没用到的。但是Robin的搜索专利，应该是用到了。



# 数学之美







## 原文



## 思考



为什么要通过一个矩阵来迭代？直接统计每个网页被多少个其他网页指向不好吗？（这就完全类似于学术论文的citation了）

应该是不行的，如果直接统计，我搞一堆小破网页，很容易hack这个ranking。但是按照迭代的思路，我这一堆小破网页，没有其他的网页指向，所以权重会很低，这样即使有很多小破网页指向一个网页，量大但是质（权重）不行，最后还是提升不了多少的。



按照同样的道理，是不是如果搞学术的ranking，是不是也可以用矩阵迭代一下，而不是直接用citation？





PageRank刻画的是网页的质量，那在搜索中，怎么和相关性结合生效的呢？

最简单的就是 relevance * quality



> 在 PageRank paper的 5.2 Rank Merging中提到：
>
> "Rank merging is known to be a very difficult problem, and we need to spend considerable additional effort before we will be able to do a reasonable evaluation of these types of queries. However, wo do believe that using PageRank as a factor in these queries is quite beneficial."







# 相关资料

https://www.cis.upenn.edu/~mkearns/teaching/NetworkedLife/pagerank.pdf

https://en.wikipedia.org/wiki/PageRank

https://web.stanford.edu/class/cs54n/handouts/24-GooglePageRankAlgorithm.pdf



抖音上搜索"PageRank"，抖音百科也有一些干货
