# 本地图片管理指南

## 图片目录结构

网站使用以下目录结构存储图片：

```
images/
├── avatar/      # 头像图片
├── gallery/     # 相册图片
└── family/      # 家庭成员图片
```

## 图片文件命名

### 头像图片 (`images/avatar/`)

- `inny-garden.jpg` - Inny在花园的照片
- `inny-portrait.jpg` - Inny的肖像照
- `inny-smile.jpg` - Inny的笑脸照片

### 相册图片 (`images/gallery/`)

- `inny-playing.jpg` - Inny玩玩具的照片
- `inny-family-park.jpg` - Inny和家人在公园的照片
- `inny-painting.jpg` - Inny画画的照片

### 家庭图片 (`images/family/`)

- `mother.jpg` - 妈妈的照片
- `father.jpg` - 爸爸的照片

<br />

## 图片格式要求

- **支持格式**：JPG, PNG, GIF, WebP
- **推荐大小**：
  - 头像：300x300px
  - 相册：800x600px
  - 家庭：400x400px
- **文件大小**：建议不超过2MB

## 注意事项

1. **保持文件名一致**：修改HTML中的图片引用后，确保实际文件名与之匹配
2. **定期备份**：建议定期备份 `images` 文件夹
3. **图片优化**：使用图片管理系统上传时，系统会自动优化图片
4. **路径验证**：在图片管理系统中使用路径验证功能检查路径设置

## 问题排查

- **图片不显示**：检查文件路径和文件名是否正确
- **路径错误**：使用图片管理系统的路径验证功能
- **上传失败**：检查文件大小和格式是否符合要求

***

