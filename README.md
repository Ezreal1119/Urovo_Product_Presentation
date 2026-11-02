# UROVO 产品 HTML PPT 合集

双击 **UROVO_Complete_Product_Presentation.html** 或 **index.html** 即可打开完整演示，共 **27 页**，支持离线浏览。

## 使用

- 左右方向键、Page Up / Page Down、底部按钮：上一页 / 下一页。
- 空格：下一页；Home / End：第一页 / 最后一页。
- 顶部选页菜单：支持按产品型号、标题关键词或页码即时搜索；点击结果或按 Enter 跳转，× 清空搜索。
- **F** 或 Full screen：全屏；**N**：当前产品来源备注。
- **C**：打开目录。来源备注打开时，Esc 关闭备注。
- 浏览器地址中的 `#slide-数字` 可定位总演示的一页。

## 文件夹内容

- `UROVO_Complete_Product_Presentation.html`：完整演示入口。
- `index.html`：相同入口，方便本地服务器自动打开。
- `products/`：14 份产品独立版 HTML，保留原内容和来源备注。
- `assets/`：产品图片、应用示意图和本地演示视频。
- `manifest.json`：27 页顺序、原文件路径、校验值和图片清单。
- `UROVO_Complete_Product_Presentation_Image_Based.pptx`：27 页图片版，使用最新网页的 3200×1800 整页画面。
- `UROVO_Complete_Product_Presentation_Editable.pptx`：27 页可编辑版，文字、图片和比较表格保留为独立对象。
- `README.md`：本说明。

**发送或移动时请携带整个文件夹**，保留 `products/` 与 `assets/` 的相对位置。原 HTML 的图片是嵌入的，本合集将它们提取为共享附件，所以单独复制入口 HTML 不足以显示内容。运行时不需要 CDN、字体下载或外部网络，也不依赖原工作区的位置。

## 页序

| 总页码 | 产品 | 页数 |
| --- | --- | --- |
| 1–2 | DT610 | 2 |
| 3–4 | DT630 | 2 |
| 5–6 | DT66 | 2 |
| 7–11 | DT50 Series | 5 |
| 12–13 | RT40S | 2 |
| 14–15 | SP35 | 2 |
| 16–17 | UPad | 2 |
| 18–19 | K388 Pro | 2 |
| 20–21 | i9600 Mini（非金融版） | 2 |
| 22–23 | D81R Series（D812R / D813R） | 2 |
| 24–25 | GS-2208D（GAINSCHA 产品参考） | 2 |
| 26 | K329 + K389 | 1 |
| 27 | ESL | 1 |

DT50 Series 五页版已含 DT50S 两页及 DT50 Pro、DT50P、DT50D 各一页。`products/DT50S_Product_Presentation.html` 另行保留，但不重复加入总演示。

## 交付说明

保留当前各产品定稿的内容与版式，没有添加封面或过渡页。总入口统一控制连续翻页与全局页码。嵌入模式隐藏产品自己的导航，单独打开产品文件仍可使用其原有导航。

HTML 与两份 PPTX 均为 27 页，内容顺序一致。PPTX 于 2026-11-02 按最新网页同步，加入 i9600 Mini、D81R 与 GS-2208D 共 6 页，统一全局页码。原稿目录未移动或删除，未修改产品知识库或 Agent Runtime。

两份 PPTX 的第 25 页均已嵌入完整的瑞幸参考视频，无需随文件携带外部视频。放映时点击图片上的 Play video，使用 PowerPoint 的原生全屏视频播放方式。已检查嵌入文件与媒体关系；当前环境没有 Microsoft PowerPoint，未实测该应用中的播放行为。

i9600 Mini 的两页位于 K388 Pro 之后：规格与卖点、应用场景与配件及竞品对比。使用 20260908 Smart Mobile 非金融版资料，独立入口为 `products/i9600_Mini_Product_Presentation.html`，来源和图像说明见 `products/i9600_Mini_Sources.md`。

D81R 的两页位于 i9600 Mini 之后：系列规格、型号选型与卖点；应用、配件与桌面竞品配置。独立入口为 `products/D81R_Product_Presentation.html`，来源和图像说明见 `products/D81R_Sources.md`。目录支持 D81R、D812R、D813R 搜索。

GS-2208D 的两页位于 D81R 之后，使用 GAINSCHA 两寸桌面热敏打印机资料，保留制造商品牌，独立入口为 `products/GS2208D_Product_Presentation.html`。第二页咖啡场景图右下角的 Play video 按钮可播放客户提供的瑞幸参考视频；支持暂停、拖动、全屏，关闭时停止并复位。来源和图像提示词见 `products/GS2208D_Sources.md`。本地视频随 `assets/` 文件夹一同携带。
