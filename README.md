## 环境

```bash
pip install -r requirement.txt
```
test image 下载地址
下载后解压缩到当前文件夹下。
[google drive](https://drive.google.com/file/d/1wDn45WJyzXyUztv8T7hQDMwrPtobKeCp/view?usp=sharing)

## 训练

训练的图片已经提取了sift特征并使用PCA处理保存在train_data.txt和train_label.txt文件中了.

run `Part_img_train.py`

## 测试

run `Part_img_test.py`

注程序只会输出识别错误的图片，识别结果在最后输出。

