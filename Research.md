## 1. [Jailbreak is (Mostly) Simpler Than You Think.(2025)](https://arxiv.org/pdf/2503.05264v1)
|字段|内容|
|----------|---------------------------------|
|**作者**|Mark Russinovich, Ahmed Salem.|
|**录用**|Arxiv|
|**核心贡献**|
|**代码链接**|
|**研究不足**|
|**BibTex**|
|**标签**|#Jailbreak #

## 2. [Prompt, Divide, and Conquer: Bypassing Large Language Model Safety Filters via Segmented and Distributed Prompt Processing.(2025)](https://arxiv.org/pdf/2503.21598v1)
|字段|内容|
|----------|---------------------------------|
|**作者**| Johan Wahréus, Ahmed Hussain, and Panos Papadimitratos.|
|**录用**|Arxiv|
|**核心贡献**|
|**代码链接**|
|**研究不足**|
|**BibTex**|
|**标签**|# 

## 3. [Formalizing and Benchmarking Prompt Injection Attacks and Defenses.(2024)](https://www.usenix.org/system/files/usenixsecurity24-liu-yupei.pdf)
|字段|内容|
|----------|---------------------------------|
|**作者**|  Yupei Liu, Yuqi Jia, Runpeng Geng, et al.|
|**录用**|33rd USENIX Security|
|**核心贡献**|
|**代码链接**|
|**研究不足**|
|**BibTex**|
|**标签**|# 

## 4. [Empirical Analysis of Large Vision-Language Models against Goal Hijacking via Visual Prompt Injection.(2024)](https://arxiv.org/pdf/2408.03554v1)
|字段|内容|
|----------|---------------------------------|
|**作者**|  Subaru Kimura, Ryota Tanaka, Shumpei Miyawaki, et al.|
|**录用**|NAACL(SRW) 2024|
|**核心贡献**|
|**代码链接**|
|**研究不足**|
|**BibTex**|
|**标签**|# 

## 5. [Empirical Analysis of Large Vision-Language Models against Goal Hijacking via Visual Prompt Injection.(2024)](https://arxiv.org/pdf/2408.03554v1)
|字段|内容|
|----------|---------------------------------|
|**作者**|  Subaru Kimura, Ryota Tanaka, Shumpei Miyawaki, et al.|
|**录用**|NAACL(SRW) 2024|
|**核心贡献**|
|**代码链接**|
|**研究不足**|
|**BibTex**|
|**标签**|# 

## 6. [AUTODAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models.(2024)](https://openreview.net/pdf?id=7Jwpw4qKkb)
|字段|内容|
|----------|---------------------------------|
|**作者**|  Xiaogeng Liu, Nan Xu, Muhao Chen, et al.|
|**录用**|ICLR 2024|
|**核心贡献**|1.攻击方法生成的prompt是语义可理解的；2.利用遗传算法从句子和段落两个水平寻找prompt。|
|**代码链接**|https://github.com/SheltonLiu-N/AutoDAN|
|**思考**|1.开销太大；[2.是不是可以加入分形特征来优化prompt.](https://papers.nips.cc/paper_files/paper/2024/file/cd004fa45fc1fe5c0218b7801d98d036-Paper-Conference.pdf)|
|**BibTex**|@inproceedings{liu2024autodan, title={Auto{DAN}: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models}, author={Xiaogeng Liu and Nan Xu and Muhao Chen and Chaowei Xiao}, booktitle={The Twelfth International Conference on Learning Representations}, year={2024}, url={https://openreview.net/forum?id=7Jwpw4qKkb}}|
|**标签**|#Jailbreak #Prompt #Genetic policies|

## 7. [Jailbreaking as a Reward Misspecification Problem.(2025)](https://openreview.net/pdf?id=uBnM3EFovQ)
|字段|内容|
|----------|---------------------------------|
|**作者**|  Zhihui Xie, Jiahui Gao1, Lei Li, et al.|
|**录用**|ICLR 2025|
|**核心贡献**|1.提出了新观点：LLM安全的脆弱性是由于在对齐过程中的奖励误设；2.对齐模型可以被解释为强化学习问题的一个解；3.提出新的指标ReGAP,利用对齐模型与推理模型输出的差值作为奖励函数，通过输出有害与无害回复的奖励函数差值小于0来寻找suffix实现攻击；4.利用随机集束搜索寻找具有可读性的对抗suffix；5.利用llamaguard判断模型回复是否有害。|
|**代码链接**|https://github.com/zhxieml/remiss-jailbreak.|
|**思考**|1.奖励函数必须利用两个模型，一个目标模型，一个推理模型，推理模型的选择是否影响结果呢；2.有没有可能利用一个模型就能达到目的。|
|**BibTex**|@inproceedings{xie2025jailbreaking, title={Jailbreaking as a Reward Misspecification Problem}, author={Zhihui Xie and Jiahui Gao and Lei Li and Zhenguo Li and Qi Liu and Lingpeng Kong}, booktitle={The Thirteenth International Conference on Learning Representations}, year={2025}, url={https://openreview.net/forum?id=uBnM3EFovQ}}|
|**标签**|#Jailbreak #Prompt #Reward #Adversarial attack|

## 8. [Masterkey: Automated Jailbreaking of LLM Chatbots.(2024)](https://www.ndss-symposium.org/wp-content/uploads/2024-188-paper.pdf)
|字段|内容|
|----------|---------------------------------|
|**作者**|   Gelei Deng, Yi Liu, Yuekang Li, et al.|
|**录用**|NDSS 2024|
|**核心贡献**|1.通过逆向工程对大模型中的防御机制进行了探讨，主要是通过不同问题组合提问，计算回答的时间差，得到大模型内部的数据流向，从而逆向出LLM Chatbot内部jailbreak 防御的模块；2.受time-based SQL injection启发，提出POC攻击方法，|
|**代码链接**|https://github.com/LLMSecurity/MasterKey.|
|**思考**|1.|
|**BibTex**|@misc{liu2024jailbreaking, title={Jailbreaking ChatGPT via Prompt Engineering: An Empirical Study}, author={Yi Liu and Gelei Deng and Zhengzi Xu and Yuekang Li and Yaowen Zheng and Ying Zhang and Lida Zhao and Tianwei Zhang and Kailong Wang and Yang Liu}, year={2024}, eprint={2305.13860}, archivePrefix={arXiv}}|
|**标签**|#Jailbreak |
