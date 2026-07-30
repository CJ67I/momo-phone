# Momo Phone

SillyTavern（酒馆）第三方扩展：超拟真虚拟手机系统。支持微信、朋友圈、微博热搜、音视频通话、音乐播放，并接入 AtlasCloud Seedream 生图。

---

## 安装

### 扩展管理器（推荐）

1. 打开 SillyTavern「扩展」面板 →「安装扩展」
2. 粘贴仓库地址（必须用这个，不要再用任何 `yuzuki-phone` 地址）：

```text
https://github.com/CJ67I/momo-phone.git
```

3. 分支留空（默认 `main`）
4. 安装成功后会生成目录：`public/scripts/extensions/third-party/momo-phone/`
5. 刷新页面，在扩展菜单找到 **Momo Phone**

### 手动安装

把仓库内容放到：

```text
SillyTavern/public/scripts/extensions/third-party/momo-phone/
```

确认该目录下直接包含 `manifest.json`、`index.js`、`momo-phone.css`，然后重启 SillyTavern。

> 请勿安装到 `public/plugins/`。  
> 本扩展目录名是 `momo-phone`，与残留的 `yuzuki-phone` 无关。若旧扩展仍在列表里，请禁用旧版，只保留 Momo Phone。

---

## Seedream 生图

设置 → 生图 → 供应商选择 **Seedream / AtlasCloud**，填写 [AtlasCloud](https://console.atlascloud.ai) API Key 后测试连接。

---

*Momo Phone*
