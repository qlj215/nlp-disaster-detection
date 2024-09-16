# nlp-disaster-detection
这是kaggle上的一个项目，目的是识别推文是否是具有灾难
train.csv文件为训练集，有5个特征列，特征列名为id、keyword、location、text、target，分别代表序号、可能的灾难类型、推文发送地址、推文内容、标签。
test.csv文件为测试集，除了不存在target列，其余与train.csv文件完全一致。
微调bert模型应用于测试集，将所得结果根据序号写入submission.csv文件
