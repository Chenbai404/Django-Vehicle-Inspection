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

## 安装部署

### 环境要求
- Python 3.9+
- 虚拟环境

### 安装步骤
1. 克隆项目
```bash
git clone <repository-url>

