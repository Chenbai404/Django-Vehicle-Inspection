# 基于Django的车辆检测系统

## 项目简介
简要描述项目的目的、功能和特点
使用KITTI数据集(  https://www.cvlibs.net/datasets/kitti/index.php  )， 训练FastRCNN和YOLOv5模型，将训练好的参数集成到Django框架中。
可以实现**实时车辆检测**以及**图片检测功能**。 
检测结果将以边界框、类别及置信度进行展示

## 技术栈
- **使用语言**: Python
- **模型使用**: FastRCNN, YOLOv5
- **后端框架**: Django + Wagtail
- **计算机视觉**: OpenCV
- **数据库**: SQLite
- **前端**: HTML5, CSS3, JavaScript, Bootstrap, jQuery
- **API**: Django REST Framework
- **其他**: NumPy, Matplotlib



## 功能模块

### 1. 实时视频流处理 (cam_app)
- 摄像头视频捕获
- 人脸检测
- 眼睛检测
- 实时视频流传输

### 2. 图像上传和处理 (cam_app2)
- 批量图像上传
- 图像处理（灰度转换等）
- 结果保存和展示

### 3. 内容管理 (streams)
- 标题文本块
- 卡片块
- 富文本编辑

### 4. 菜单系统 (menus)
- 自定义菜单创建
- 内外部链接管理

## 结果展示
#####  **首页信息展示**
  
<img width="1262" height="565" alt="image" src="https://github.com/user-attachments/assets/7b37fe92-c149-4841-a31f-44e8497efeb8" />  
<img width="1249" height="569" alt="image" src="https://github.com/user-attachments/assets/2427c93b-efc9-44fb-a97e-ace8d604fd4f" />  
<img width="1250" height="568" alt="image" src="https://github.com/user-attachments/assets/c00da9c8-0d33-4a62-ad54-b9392c136bef" />  
  
#####  **其余页面展示**  
  
<img width="1246" height="508" alt="image" src="https://github.com/user-attachments/assets/5e1d8b30-3e07-45ff-8ba5-8551a663f0e2" />
  

##### **实时识别功能展示**
<img width="1247" height="504" alt="image" src="https://github.com/user-attachments/assets/209ce50a-6a2b-460b-b9ce-c2cbae149e08" />
  
**点击运行后**  
<img width="500" height="442" alt="image" src="https://github.com/user-attachments/assets/93351029-8766-4a1e-8bba-991d962976f2" />
  
  
##### **图片识别功能展示**  
<img width="1261" height="563" alt="image" src="https://github.com/user-attachments/assets/e74ea0a5-5354-485a-83bd-eb4285907faa" />  
    
**点击运行后**  
<img width="1248" height="560" alt="image" src="https://github.com/user-attachments/assets/d58b37cb-3c0c-4e54-bef1-49d08ae2d72c" />








