# Video Caption Dataset

本仓库提供视频描述标注文件 `test.json`，适用于多模态（视频-文本）任务研究，如视频理解、跨模态检索等。

---

## 数据集内容

### 标注文件 (`test.json`)
- **字段说明**：
  - `id`: 样本唯一标识符
  - `video`: 视频文件路径（对应原始数据集的相对路径）
  - `caption`: 对视频内容的详细文本描述（英文）
- **数据量**：共 `X` 条标注（具体数量请查看文件）

---

## 视频来源与版权声明

### 原始数据集
标注中的视频文件来源于以下公开数据集：
1. **AFEW-VA**  
   - 描述：包含带有情感强度标注的视频片段  
   - 下载链接：[AFEW-VA Dataset](https://www.openu.ac.il/home/hassner/AFEW-VA/)（需申请访问权限）

2. **CAER_mp4**  
   - 描述：上下文感知情感识别的视频数据集  
   - 下载链接：[CAER GitHub](https://github.com/ok1nagi/caer)

3. **DFEW**  
   - 描述：动态面部表情在野视频数据集  
   - 下载链接：[DFEW Dataset](https://dfew-dataset.github.io/)

4. **FERV39k**  
   - 描述：大规模面部表情视频数据集  
   - 下载链接：[FERV39k GitHub](https://github.com/Facial-Expression-Recognition/FERV)

5. **MAFW**  
   - 描述：多属性情感在野视频数据集  
   - 下载链接：[MAFW Dataset](https://mafw-dataset.github.io/)

6. **MER24**  
   - 描述：24 类微表情视频数据集  
   - 下载链接：[MER24 Dataset](https://mer24-dataset.org/)（需邮件申请）

7. **RAVDESS**  
   - 描述：多模态情感表达视频/音频数据集  
   - 下载链接：[RAVDESS Download](https://zenodo.org/record/1188976)

### 版权声明
- ⚠️ **本仓库不包含原始视频文件**，仅提供标注信息。
- 用户需**自行下载原始数据集**并遵守其许可协议（通常仅限研究用途）。

---

## 结果对比

我们基于本标注数据的实验结果对比请参考：[结果对比表格](./results_comparison.pdf)  
（建议下载后查看以获取清晰排版）

---

## 引用

如果本标注数据对您的研究有帮助，请引用：

```bibtex
@misc{your_work_2023,
  author       = {Your Name and Co-authors},
  title        = {Your Paper Title},
  year         = {2023},
  publisher    = {arXiv},
  howpublished = {\url{https://arxiv.org/abs/xxxx.xxxxx}}
}
