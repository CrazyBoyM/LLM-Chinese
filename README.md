# LLM-Chinese
本仓库偏教程性质，希望以「模型中文化」为一个典型的模型训练需求场景，指导读者上手掌握LLM二次微调训练流程。


## gemma2 中文版
shareAI-DPO对齐中文版 （教程撰写中...)
- 感谢opencsg的8 * A800 训练机器赞助
- 9b中文对话版本：https://opencsg.com/models/shareAI/gemma-2-9b-it-Chinese-DPO
- 2b中文对话版本：https://opencsg.com/models/shareAI/gemma-2-2b-it-Chinese-DPO
- gguf格式量化版本下载（ollama、lmstudio可直接用）：https://huggingface.co/shareAI/gemma-2-it-Chinese-DPO-GGUF  
   
<img width="800" alt="image" src="https://github.com/user-attachments/assets/565946d2-7d46-4173-8a88-f589e4504c9c">
截图为2b版本的演示，实测当对话轮次增多后会与9b有一些明显性能差距，但10轮以内对话表现比较好。（测试了英文原版也是这样）
