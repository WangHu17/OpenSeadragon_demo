# OpenSeadragon_demo
使用 OpenSeadragon 框架在线预览大型图片

## 第一步：生成 dzi 文件（将高分辨率大图像转换为 DZI 文件）
### 方式一：Deep Zoom Composer
#### 下载
官方下载链接已失效，自行网上下载
#### 使用
1. 新建项目
2. Import - Add image
![image](https://github.com/WangHu17/OpenSeadragon_demo/assets/39235304/7b00352d-a276-4bc0-9967-14bfbbbd89f8)
3. Export - Export
![image](https://github.com/WangHu17/OpenSeadragon_demo/assets/39235304/53a6d32b-9141-4e31-9da9-abebc7ef9788)
#### 生成文件
只需要以下两个文件，将它们拷贝到项目目录下：
- 文件夹内是分割后的图像
- xml 是写程序时用到的相关参数
![image](https://github.com/WangHu17/OpenSeadragon_demo/assets/39235304/69777fda-ac88-493c-afb0-e570321e2785)

** 由于我在使用 Deep Zoom Composer ，Add image 时会出错（如下图），添加小图片时正常，几百兆上G的图片就会失败，不知道为什么，知道怎么解决的朋友请评论告诉我，不胜感激。因此我是使用的方式二生成 dzi 文件的。 **

### 方式二：vips
