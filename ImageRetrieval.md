# 关于图像检索的资料整理
如果链接无法使用请善用搜索引擎，或者找我要pdf；如果链接错误请及时与我联系。  
这里面一些我觉得比较重要的文章会加粗处理。
## 建立在SIFT特征基础上的
之前的图像检索使用的特征基本都是SIFT特征，现在CNN模型的发展已经基本取代了SIFT特征了。所以这部分可以只作了解，不过**其中很多思想和方法现在仍然有用**。
* 关于SIFT特征：Lowe D G. Object recognition from local scale-invariant features[C]. 1999. [link][1].
* 老师给我看的第一篇文章，里面的BOW、tf-idf、inverted files都挺有用的：***Sivic, Zisserman. Video Google: a text retrieval approach to object matching in videos[C]. 2003.*** [link][2].
* Arandjelovic R, Zisserman A. Three things everyone should know to improve object retrieval[C]. 2012. [link][5].

下面的这部分文章基本都是Jegou这个人的，算是图像检索领域的一个大佬，他的主页在这里：[Jegou][3].
* Jegou H, Douze M, Schmid C. Product quantization for nearest neighbor search[J]. 2011. [link][4].
* Jegou H, Perronnin F, Douze M, et al. Aggregating local image descriptors into compact codes[J]. 2012. [link][6].
* Tolias G, Avrithis Y, Jegou H, et al. To Aggregate or Not to aggregate: Selective Match Kernels for Image Search[C]. 2013. [link][7].
* ***Jegou H, Zisserman A. Triangulation embedding and democratic aggregation for image search[C]. 2014.*** [link][8].
* Murray N, Jégou H, Perronnin F, et al. Interferences in match kernels[J]. 2016. [link][9].
* 这篇文章主要可以了解下Burstiness现象：Jegou H, Douze M, Schmid C, et al. On the burstiness of visual elements[C]. 2009. [link][10].
***
## 使用CNN模型的
关于CNN(Convolutional Neural Networks,卷积神经网络)，我自己其实了解的不是很多，目前只是会使用一些模型，也处在学习阶段。建议大家自行寻找一些资料阅读了解。（这里推荐一个 [Convolutional Neural Networks for Visual Recognition][12].）
* 好像是第一篇用CNN做图像检索的：Babenko A, Slesarev A, Chigorin A, et al. Neural Codes for Image Retrieval[C]. 2014. [link][11].
* Karamti H, Tmar M, Gargouri F, et al. Content-based image retrieval system using neural network[C]. 2014. [link][13].

下面这些应该都是对CNN的卷积层特征做处理，是目前比较主流的一些方法或者是一些作为baseline的方法：  
* Babenko A, Lempitsky V S. Aggregating Deep Convolutional Features for Image Retrieval.[J]. 2015. [link][14].
* Kalantidis Y, Mellina C, Osindero S, et al. ***Cross-Dimensional Weighting for Aggregated Deep Convolutional Features[J].*** 2016. [link][15].
* Hoang T, Do T, Tan D L, et al. ***Selective Deep Convolutional Features for Image Retrieval[J].*** 2017. [link][16].
* Tolias G, Sicre R, Jegou H, et al. ***Particular object retrieval with integral max-pooling of CNN activations[J].*** 2016. [link][17].

[1]: https://www.cs.ubc.ca/~lowe/papers/iccv99.pdf "SIFT"
[2]: https://courses.cs.washington.edu/courses/cse576/06sp/papers/sivic.pdf "Video Google"
[3]: http://people.rennes.inria.fr/Herve.Jegou/publications.html "Jegou"
[4]: https://hal.inria.fr/file/index/docid/825085/filename/jegou_pq_postprint.pdf "PQ"
[5]: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.370.7498&rep=rep1&type=pdf "Three Things"
[6]: https://hal.inria.fr/file/index/docid/633013/filename/jegou_aggregate.pdf "VLAD"
[7]: https://hal.inria.fr/file/index/docid/864684/filename/iccv13_tolias.pdf "SMK"
[8]: https://hal.inria.fr/file/index/docid/978462/filename/cvpr2014_democratic_appendices.pdf "TEMB"
[9]: https://arxiv.org/pdf/1611.08194.pdf "Inferences"
[10]: http://lear.inrialpes.fr/pubs/2009/JDS09a/jegou_burstiness.pdf "Burstiness"
[11]: http://vigir.missouri.edu/~gdesouza/Research/Conference_CDs/ECCV_2014/papers/8689/86890584.pdf "Neural Codes"
[12]: http://vision.stanford.edu/teaching/cs231n/index.html "Stanford CNN"
[13]: https://ieeexplore.ieee.org/document/7073271/ "CBIR system"
[14]: https://arxiv.org/pdf/1510.07493v1.pdf "SPoC"
[15]: https://arxiv.org/pdf/1512.04065.pdf "CRoW"
[16]: https://arxiv.org/pdf/1707.00809.pdf "Mask"
[17]: https://arxiv.org/pdf/1511.05879.pdf "RMAC"
