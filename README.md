# 自媒体图片管理

## 📖 简介

这是一个用于管理自媒体图片资源的仓库，包含：
- AI 生成的图片
- 设计素材
- 营销图片
- 社交媒体配图

## 🎨 图片资源

### AI 生成图片

使用 ComfyUI + LongCat 模型生成的图片。

#### 示例图片

| 文件名 | 描述 | 生成时间 |
|--------|------|----------|
| `beautiful-landscape.png` | 美丽的风景，山川湖泊日落 | 2026-03-12 |
| `cyberpunk-city-night.png` | 赛博朋克城市夜景，霓虹灯光 | 2026-03-12 |

#### 生成方式

使用 ComfyUI 文生图技能：
```bash
/imagine 画一张：美丽的风景，山川湖泊，日落
/imagine 画一张：赛博朋克风格的城市夜景
```

## 🛠️ 工具

### ComfyUI 文生图

- **模型**: LongCat-Image-Q8_0.gguf (6.2GB)
- **位置**: `~/.openclaw/workspace/skills/comfyui-image-gen/`
- **技能**: ComfyUI 文生图

### 生成参数

- **分辨率**: 512x512
- **步数**: 28
- **CFG**: 7.5
- **采样器**: euler

## 📝 使用说明

### 添加新图片

1. 生成图片
2. 重命名（使用英文或拼音）
3. 提交到仓库
4. 更新此 README

### 图片命名规范

- 使用英文或拼音
- 使用下划线分隔单词
- 包含日期（可选）

示例：
- `beautiful-landscape-20260312.png`
- `cyberpunk-city-night.png`
- `cute-cat-anime-style.png`

## 🎯 用途

- 自媒体文章配图
- 社交媒体内容
- 博客文章
- 营销材料

## 📊 统计

- **图片数量**: 2
- **总大小**: ~26KB
- **生成方式**: AI 生成

## 🔗 相关链接

- [ComfyUI 文生图技能](../../skills/comfyui-image-gen/)
- [LongCat 模型](/Users/zcl/models/longcat-image-gguf/)

## 📄 许可证

MIT License

---

**仓库创建时间**: 2026-03-12  
**更新时间**: 2026-03-12
