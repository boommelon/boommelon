# Hi, I'm Zhang Kai

Data Science and Big Data Technology undergraduate at Shanghai University of Electric Power.  
I focus on AI applications, machine learning experiments, computer vision, and practical full-stack tools.

## About Me

- Interested in AI engineering, machine learning, RAG, computer vision, and model deployment.
- Comfortable building small end-to-end projects from data preparation and model training to API, UI, and documentation.
- Currently working with Python, PyTorch, YOLOv8, Transformers, FastAPI, Vue, MySQL, and Neo4j.

## Tech Stack

**AI / Machine Learning**

- PyTorch, scikit-learn, Ultralytics YOLOv8, OpenVINO
- Transformers, Qwen, RAG, BM25, knowledge distillation
- FGSM adversarial attack, continual learning, GAN, few-shot learning

**Development**

- Python, Java, SQL
- FastAPI, Flask, Streamlit
- Vue 3, Vite, Tailwind CSS
- MySQL, Neo4j / Cypher
- Pandas, NumPy, Jupyter Notebook

## Featured Projects

### YOLOv8 Hand Gesture Detection

Repository: [python-big-homework1](https://github.com/boommelon/python-big-homework1)

- Built a Grab / Release hand gesture detector based on Ultralytics YOLOv8.
- Completed dataset preparation, label checking, transfer learning, command-line inference, and Streamlit Web GUI.
- Reached about 0.995 mAP50 and 0.915 mAP50-95 on the validation set.
- Achieved about 15 ms single-frame inference at 640x480 on RTX 3060 Laptop GPU.

### AI Paper Study Assistant

Repository: [ai-paper-study-assistant](https://github.com/boommelon/ai-paper-study-assistant)

- Built a local AI study assistant for reading papers and technical documents.
- Supports local folders and uploaded `md`, `txt`, `pdf`, and `docx` files.
- Uses a FastAPI backend and Vue 3 frontend to generate summaries, beginner-friendly explanations, review questions, and folder-level study maps.
- Added Markdown export and JSON cache to reduce repeated generation.

### RAG Knowledge QA Experiment

- Built a Chinese RAG workflow using document chunking, `jieba`, BM25 retrieval, and Qwen generation.
- Used the 2023 Power Load Management Measures as the knowledge base.
- Implemented fixed-size chunking, Top-K retrieval, RAG prompt construction, and local model inference with Transformers.

### OpenVINO Blind Travel Assistance System

- Participated in a team project for assisting visually impaired people in travel scenarios.
- Worked on backend inference service and frontend interaction.
- Integrated YOLO object detection with Flask and Vue, then optimized the inference workflow with Intel OpenVINO.
- The team won a national third prize among 200+ participating teams.

## Machine Learning Experiments

- **Adversarial Attack:** Implemented FGSM on a handwritten digit classifier. Accuracy dropped from 94.17% to 4.17% at epsilon=0.20.
- **Knowledge Distillation:** Implemented CrossEntropy + KLDiv distillation loss and compared teacher, normal student, and distilled student models.
- **Continual Learning:** Compared naive sequential learning with experience replay. Forgetting dropped from 0.9336 to 0.0265 after adding replay samples.
- **Other Practice:** GAN digit generation, Prototypical Networks for few-shot classification, Qwen3-4B cloud inference, and Neo4j knowledge graph construction.

## Other Projects

- Gym membership and course management system with Python, Tkinter, and MySQL.
- Graduation project management system with JavaWeb, Servlet, JSP, MySQL, and Tomcat.

## Contact

- Email: yyymelon521@gmail.com
- GitHub: [github.com/boommelon](https://github.com/boommelon)
