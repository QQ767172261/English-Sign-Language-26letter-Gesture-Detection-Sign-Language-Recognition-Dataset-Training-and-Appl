英文手语26字母手势检测、手语识别
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a6304afca4e44a14b090b167ade97791.png)

【英文手语26字母手势检测】数据集模型共1728张\YOLO预训练模型YOLOV5、YOLOv8、YOLOv11:

【英文手语26字母手势检测】数据数据集共包含【1728】张图图像，其中：
Train集: 1512 张图片
Val集: 144 张图片
Test集: 72 张图片![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/4a9aed31226c4efe899fcbccf1f1dc17.png)


总类别数: 【26】,各类别图片数量和标注框数量为：
英文名称：【A】 中文名称：【A】: 图片数量【75】，标注框数量【75】
英文名称：【B】 中文名称：【 B】: 图片数量【51】，标注框数量【51】
英文名称：【C】 中文名称：【 C】: 图片数量【61】，标注框数量【61】
英文名称：【D】 中文名称：【 D】: 图片数量【70】，标注框数量【70】
英文名称：【E】 中文名称：【 E】: 图片数量【67】，标注框数量【67】
英文名称：【F】 中文名称：【 F】: 图片数量【70】，标注框数量【70】
英文名称：【G】 中文名称：【 G】: 图片数量【70】，标注框数量【70】
英文名称：【H】 中文名称：【 H】: 图片数量【63】，标注框数量【63】
英文名称：【I】 中文名称：【 I】: 图片数量【82】，标注框数量【82】
英文名称：【J】 中文名称：【 J】: 图片数量【90】，标注框数量【90】
英文名称：【K】 中文名称：【 K】: 图片数量【61】，标注框数量【61】
英文名称：【L】 中文名称：【 L】: 图片数量【76】，标注框数量【76】
英文名称：【M】 中文名称：【 M】: 图片数量【62】，标注框数量【62】
英文名称：【N】 中文名称：【 N】: 图片数量【67】，标注框数量【67】
英文名称：【O】 中文名称：【 O】: 图片数量【64】，标注框数量【64】
英文名称：【P】 中文名称：【 P】: 图片数量【59】，标注框数量【59】
英文名称：【Q】 中文名称：【 Q】: 图片数量【66】，标注框数量【66】
英文名称：【R】 中文名称：【 R】: 图片数量【57】，标注框数量【57】
英文名称：【S】 中文名称：【 S】: 图片数量【76】，标注框数量【76】
英文名称：【T】 中文名称：【 T】: 图片数量【53】，标注框数量【53】
英文名称：【U】 中文名称：【 U】: 图片数量【57】，标注框数量【57】
英文名称：【V】 中文名称：【 V】: 图片数量【66】，标注框数量【66】
英文名称：【W】 中文名称：【 W】: 图片数量【65】，标注框数量【65】
英文名称：【X】 中文名称：【 X】: 图片数量【68】，标注框数量【68】
英文名称：【Y】 中文名称：【 Y】: 图片数量【58】，标注框数量【58】
英文名称：【Z】 中文名称：【 Z】: 图片数量【74】，标注框数量【74】![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/8ef93d10211548fabea5852bea41354d.png)


验证集中各模型性能如下：
yolov5m map50 = 0.96281
yolov8m map50 = 0.97128
yolo11m map50 = 0.96662![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/f75d3aafcba44569a19dbb8a24f6ebce.png)
# 英文26字母手语手势检测（数据集+多模型+全套训练代码）
适用于算法研究、学习开发、项目部署、毕业设计，标准YOLO标注格式，拿到即可直接训练

## 一、项目核心信息表
|项目|详情|
|----|----|
|项目名称|英文字母手语26分类手势检测与识别|
|图片总数|1728张|
|训练集|1512张|
|验证集|144张|
|测试集|72张|
|分类数量|26类（A-Z26个英文字母）|
|标注格式|YOLO标准txt标注，开箱训练|
|支持算法|YOLOv5、YOLOv8、YOLOv11|
|最优精度|YOLOv8m mAP@0.5=0.97128|
|适用场景|手语翻译识别、人工智能实训、系统演示、毕业设计|

## 二、26类类别明细
|类别编号|字母|图片数量|标注框数量|
|----|----|----|----|
|0|A|75|75|
|1|B|51|51|
|2|C|61|61|
|3|D|70|70|
|4|E|67|67|
|5|F|70|70|
|6|G|70|70|
|7|H|63|63|
|8|I|82|82|
|9|J|90|90|
|10|K|61|61|
|11|L|76|76|
|12|M|62|62|
|13|N|67|67|
|14|O|64|64|
|15|P|59|59|
|16|Q|66|66|
|17|R|57|57|
|18|S|76|76|
|19|T|53|53|
|20|U|57|57|
|21|V|66|66|
|22|W|65|65|
|23|X|68|68|
|24|Y|58|58|
|25|Z|74|74|

## 三、各模型验证集精度指标
|模型|mAP@0.5精度|
|----|----|
|YOLOv5m|0.96281|
|YOLOv8m|0.97128|
|YOLOv11m|0.96662|

## 四、数据集配置文件 sign_lang.yaml
```yaml
train: ./images/train
val: ./images/val
test: ./images/test

nc: 26
names:
  0: A
  1: B
  2: C
  3: D
  4: E
  5: F
  6: G
  7: H
  8: I
  9: J
  10: K
  11: L
  12: M
  13: N
  14: O
  15: P
  16: Q
  17: R
  18: S
  19: T
  20: U
  21: V
  22: W
  23: X
  24: Y
  25: Z
```

## 五、完整训练代码（YOLOv8/YOLOv11通用）train_sign.py
```python
from ultralytics import YOLO

def train():
    # 可选权重：yolov8m.pt / yolov11m.pt / yolov5m.pt
    model = YOLO("yolov8m.pt")

    model.train(
        data="sign_lang.yaml",
        epochs=150,
        imgsz=640,
        batch=16,
        device=0,
        patience=15,
        project="sign_train",
        name="yolov8m_sign_26class",
        save=True,
        save_period=10,
        pretrained=True
    )
    # 模型评估
    metrics = model.val()
    print(f"最终mAP@0.5：{metrics.box.map50}")

if __name__ == "__main__":
    train()
```

## 六、图片推理测试代码 test_sign.py
```python
from ultralytics import YOLO
import cv2

# 加载训练完毕权重
model = YOLO("sign_train/yolov8m_sign_26class/weights/best.pt")

# 测试单张图片
img_path = "test.jpg"
results = model.predict(img_path, conf=0.25, iou=0.45)

# 展示检测结果
result_img = results[0].plot()
cv2.imshow("手语字母检测", result_img)
cv2.waitKey(0)
cv2.destroyAllWindows()
```

## 七、环境部署命令
```bash
conda create -n sign_lang python=3.9
conda activate sign_lang

pip install ultralytics torch==1.13.1 opencv-python numpy pillow
```


