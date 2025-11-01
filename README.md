# ISA
The code and datasets of our paper "Friend or Foe: How LLMs' Safety Mind Gets Fooled by Intent Shift Attack".

![](ISA.png)

## 📝 Abstract

Large language models (LLMs) remain vulnerable to jailbreaking attacks despite their impressive capabilities.
Investigating these weaknesses is crucial for robust safety mechanisms. Existing attacks primarily distract LLMs by introducing additional context or adversarial tokens, leaving the core harmful intent unchanged. In this paper, we introduce ISA (Intent Shift Attack), which obfuscates LLMs about the intent of the attacks. More specifically, we establish a taxonomy of intent transformations and leverage them to generate attacks that may be misperceived by LLMs as benign requests for information. Unlike prior methods relying on complex tokens or lengthy context, our approach only needs minimal edits to the original request, and yields natural, human-readable, and seemingly harmless prompts. Extensive experiments on both open-source and commercial LLMs show that ISA achieves over 70% improvement in attack success rate compared to direct harmful prompts. More critically, fine-tuning models on only benign data reformulated with ISA templates elevates success rates to nearly 100%. For defense, we evaluate existing methods and demonstrate their inadequacy against ISA, while exploring both training-free and training-based mitigation strategies. Our findings reveal fundamental challenges in intent inference for LLMs safety and underscore the need for more effective defenses.


## 📧 Contact

If you have any questions about our work, please feel free to contact us via the following email:

Peng Ding: dingpeng@smail.nju.edu.cn

Shujian Huang: huangsj@nju.edu.cn