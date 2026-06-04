# Hi, I'm Zhang Kai

上海电力大学数据科学与大数据技术本科在读。  
关注 AI 应用、机器学习实验、计算机视觉、RAG 和小型工程落地。

## About Me

- 对 AI 工程、机器学习、RAG、计算机视觉和模型部署感兴趣。
- 能独立完成从数据整理、模型训练、结果分析到 API、前端页面和文档交付的小型项目闭环。
- 常用技术包括 Python、PyTorch、YOLOv8、Transformers、FastAPI、Vue、MySQL、Neo4j。

## Tech Stack

**AI / Machine Learning**

- PyTorch, scikit-learn, Ultralytics YOLOv8, OpenVINO
- Transformers, Qwen, RAG, BM25, 知识蒸馏
- FGSM 对抗攻击、持续学习、GAN、少样本学习

**Development**

- Python, Java, SQL
- FastAPI, Flask, Streamlit
- Vue 3, Vite, Tailwind CSS
- MySQL, Neo4j / Cypher
- Pandas, NumPy, Jupyter Notebook

## Featured Projects

### YOLOv8 手势检测

Repository: [python-big-homework1](https://github.com/boommelon/python-big-homework1)

- 基于 Ultralytics YOLOv8 构建 Grab / Release 双类手势检测项目。
- 完成数据集整理、标注校验、迁移学习微调、命令行推理和 Streamlit Web GUI。
- 验证集 mAP50 约 0.995，mAP50-95 约 0.915。
- 在 RTX 3060 Laptop GPU 上，640x480 单帧推理约 15 ms。

### AI 论文学习助手

Repository: [ai-paper-study-assistant](https://github.com/boommelon/ai-paper-study-assistant)

- 构建本地 AI 学习助手，用于整理论文和技术资料。
- 支持读取本地目录或上传 `md`、`txt`、`pdf`、`docx` 文件。
- 后端使用 FastAPI，前端使用 Vue 3，支持生成论文总结、初学者解释、复习问题和文件夹学习地图。
- 实现 Markdown 导出与 JSON 缓存，减少重复生成。

### RAG 知识问答实验

- 基于中文文档分块、`jieba` 分词、BM25 检索和 Qwen 生成构建 RAG 问答流程。
- 使用《电力负荷管理办法（2023年版）》作为知识库。
- 实现固定长度分块、Top-K 检索、RAG Prompt 构建和本地 Transformers 推理。

### OpenVINO 盲人辅助出行系统

- 参与面向视障人士出行场景的目标检测辅助系统。
- 负责后端推理服务和前端交互部分实现。
- 使用 Flask + YOLO 完成目标检测服务，配合 Vue 前端展示和语音反馈，并使用 Intel OpenVINO 优化推理链路。
- 团队从 200+ 支参赛队伍中获得全国三等奖。

## Machine Learning Experiments

- **对抗攻击：** 在手写数字分类器上实现 FGSM，原始准确率 94.17%，epsilon=0.20 时降至 4.17%。
- **知识蒸馏：** 实现 CrossEntropy + KLDiv 蒸馏损失，对比教师模型、普通学生模型和蒸馏学生模型。
- **持续学习：** 对比 Naive Sequential Learning 和 Experience Replay，加入 replay 样本后遗忘程度从 0.9336 降至 0.0265。
- **其他实践：** GAN 手写数字生成、Prototypical Networks 少样本分类、Qwen3-4B 云端推理、Neo4j 知识图谱构建。

## Other Projects

- Python + Tkinter + MySQL 健身房会员及课程管理系统。
- JavaWeb + Servlet + JSP + MySQL + Tomcat 毕业设计管理系统。

## Contact

- Email: yyymelon521@gmail.com
- GitHub: [github.com/boommelon](https://github.com/boommelon)
