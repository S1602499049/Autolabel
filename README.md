# Autolabel
##第一步
  1.下载detectAuto_v8-main.zip
  2.pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple  #安装依赖库（在自己创建的虚拟环境下）
  3.cmd中conda activate <你自己的虚拟环境名字>
  4.输入python detect_auto.py运行此文件即可
##第二步
  1.请选择你要标注的图片文件夹（选择图片所在的文件夹）
  2.请选择你要保存的xml文件夹(.xml)  （看你自己想保存在哪）
  3.请选择使用的模型(.pt) (在github上下载YOLOv8权重文件)
  4.请选择需要自动标注的类别文件(.txt) （选择classes.txt，里面内容可改）
##第三步
  1.直接运行兄弟们！
##额外
  如果要用yolov8则需要在文件中添加data文件
