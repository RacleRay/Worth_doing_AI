# Worth_doing

名称 | 描述
--- | ---
[style transfer](style_tansfer/) | 使用预训练的vggnet，训练使内容损失和Gram Matrix计算出的风格损失最小化，详见项目文件夹
[image caption](image_caption/) | show and tell的tensorflow实现，模型可加入attention以及top-down lstm优化
[DCGAN](DCGAN/) | 编写该模型实现MNIST数字图片生成，对Cycle、Pix2Pix等简述
[Yolo](Yolo/) | 使用预训练yolo模型，计算yolo output，使用non max suppression和score filtering，对输出的多类预测boxes进行筛选
[Face Recognition](FaceRecognition/) | 使用triplet loss训练多层inception block网络，实现对face image编码。encoding用于1：1的verification和1：k的recognition
[WritingShakespeare](WritingShakespeare/) | 模型很简单，utils对sample的处理，对train data的处理更有用
[DebiasWordVectors](DebiasWordVectors/) | 关键在算法，线性代数转换，使gender bias关于orthogonal axis对称
[sentence2Emoji](sentence2Emoji/) | average vector方法忽略了词序，而LSTM效果更好；使用pretrianed word vec，即使只有127条数据，也有较好的效果
[Translation](Translation/) | seq2seq model的常用data process，使用全局共享的layer进行部分计算，attention的简答实现
[TriggerWordDetection](TriggerWordDetection/) | 音频数据的处理方法，生成含Trigger Word的数据，同时使用Conv 1D将输入的长序列频谱图转换成较短长度的输入。注意，不要使用Bidirection model，因为模型要求的是“立即”反馈检测结果。

