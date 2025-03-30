# stat
## 混淆矩阵 Confusion Matrix
![image](https://github.com/user-attachments/assets/67b613f7-6008-4b4f-af7c-78a2740a76cf)

## Precision 和 Recall
![image](https://github.com/user-attachments/assets/731fb719-523a-4fd5-8521-f99fadb81977)

![image](https://github.com/user-attachments/assets/3c08098c-517b-43a9-8602-38cee75b7f97)

![image](https://github.com/user-attachments/assets/36fa9cd2-cae9-4196-9256-321bd896693f)

## F1-score：平衡精度与召回
![image](https://github.com/user-attachments/assets/6a7e6311-4f9e-4123-978f-7dfee221f41c)

## ROC 曲线（Receiver Operating Characteristic）
横轴：FPR（假正率） = FP / (FP + TN)

纵轴：TPR（真正率） = Recall = TP / (TP + FN)

## AUC（Area Under Curve）
AUC=ROC曲线下的面积

“从所有正例中随机抽一个，负例中也抽一个，你的模型有多大概率把正例排在前面？”

所以 AUC 是一个排序质量指标 —— 对于你们这种需要根据情绪严重程度优先干预的系统（情绪干预 Agent），AUC 的排名能力特别重要！
