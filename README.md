# llm-primer
A primer on large language models (LLM) and ChatGPT as of April 2023
- [A video recording for V2.1 Slides, assisted by AI](https://www.youtube.com/watch?v=DoTO-0iHouI)

## Update 05/2023
- [A special side version](/other/chatgpt_primer_05_2023_guyu_v1.pdf) for [谷雨书苑](https://valleyrain.org/)
- A new side project to [Brainstorm how to possibly train better chatbots than ChatGPT](https://github.com/hululuzhu/better-chatbot-than-chatgpt)

## V2 Covers
<details>
  <summary>Intro: Building blocks & capabilities</summary>

  - LM and LLM
  - Transformer
  - How are LLMs trained?
  - LLM decoding
  - LLM training in parallel
  - LLM capabilities, advanced capabilities and insance capabilities
</details>
<details>
  <summary>Core: Models, players, concepts, toolings & applications</summary>

  - Selected LLMs
    - BERT
    - GPT family
    - T5
    - GLM
  - LLM Players
    - big companies
    - institutes and startups)
  - LLM concepts
    - Pretraining, finetuning, prompt tuning
    - Scaling laws
    - Prompt engineering
    - Prompt tuning (soft prompt)
    - "Emergent abilities"
    - Chain of thoughts (CoT)
    - Least-to-most prompting
    - Hallucination
    - Retrieval LLM
    - RLHF for LLM
    - Mixture of Experts (MoE) LLM
  - LLM Tooling
    - Huggingface
    - TF hub, Torch NLP, PaddleNLP
    - Transformers lib, Colossal-ai, Ray and NanoGPT
    - Other toolings
  - LLM Applications

</details>
<details>
  <summary>Bonus: Deep dive into ChatGPT</summary>

  - ChatGPT model evolvment
  - Research (InstructGPT) overview
  - Possible next steps for ChatGPT?
  - Engineering discussion
  - Rough estimate to train/server chatgpt
  - My thoughts on technical challenges to reproduce ChatGPT
  - What less optimal choices Google made related to ChatGPT delayed Google to release similar product?
  - Fun facts
  - ChatGPT challenges
  - Final question: Will ChatGPT become next iPhone, or next Alexa, or next ClubHouse?
  
</details>

## V2.1 Covers
- LLM basics
- RL basics
- ChatGPT
- Societal Impact

## Slides
- [V2.1 slides, April 2023](https://github.com/hululuzhu/llm-primer/blob/main/llm_primer_v2.1_april_2023_llm_rl_chatgpt.pdf)
  - [Appendix 6-page slides](https://github.com/hululuzhu/llm-primer/blob/main/other/quick_summary_embedding_bert_gpt.pdf) to explaing BERT and GPT training, and their embedding ouput and its size
- [V2 slides, Jan 2023](https://github.com/hululuzhu/llm-primer/blob/main/llm_primer_v2_jan_2023.pdf)
- [Old V1 slides, July 2022](https://github.com/hululuzhu/fun-paper-sharing/blob/main/slides/llm_primer_v1.pdf)


## Additional notes
- [Draft notes](other/draft_notes_llm_primer.pdf) to prepare V2 topics

### Chinese only notes (my personal opinion)
- [对于“纯复现ChatGPT有多难”的一些思考](other/chinese_only_tech_challanges_reproduce_chatgpt.md)
- [对“Google在LLM怎么就被动了”做一点反思](other/chinese_only_thoughts_on_less_optimal_choices_by_google.md)
- [对技术“弯道超车”ChatGPT的一些思考](other/chinese_only_crazy_ideas_surpass_chatgpt.md)

## Recommended quick readings
- [张俊林：通向AGI之路：大型语言模型（LLM）技术精要](https://zhuanlan.zhihu.com/p/597586623)
- [Yao Fu：How does GPT Obtain its Ability? Tracing Emergent Abilities of Language Models to their Sources](https://yaofu.notion.site/How-does-GPT-Obtain-its-Ability-Tracing-Emergent-Abilities-of-Language-Models-to-their-Sources-b9a57ac0fcf74f30a1ab9e3e36fa1dc1)
- [Stephen Wolfram：What Is ChatGPT Doing and Why Does It Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/)
- [李宏毅：ChatGPT (可能)是怎麼煉成的 - GPT 社會化的過程](https://www.youtube.com/watch?v=e0aKI2GGZNg)
- [李沐：InstructGPT 论文精读【论文精读】](https://www.youtube.com/watch?v=zfIGAwD1jOQ)

## ~120 References as of 01/30/2023
<details>
  <summary>Click to expand</summary>

  - [[1706.03741] Deep reinforcement learning from human preferences](https://arxiv.org/abs/1706.03741)
  - [[1706.03762] Attention Is All You Need](https://arxiv.org/abs/1706.03762)
  - [[1810.04805] BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
  - [[1904.00962] Large Batch Optimization for Deep Learning: Training BERT in 76 minutes](https://arxiv.org/abs/1904.00962)
  - [[1907.11692] RoBERTa: A Robustly Optimized BERT Pretraining Approach](https://arxiv.org/abs/1907.11692)
  - [[1910.10683] Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683)
  - [[2001.08361] Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361)
  - [[2005.14165] Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)
  - [[2103.00823] M6: A Chinese Multimodal Pretrainer](https://arxiv.org/abs/2103.00823)
  - [[2104.08691] The Power of Scale for Parameter-Efficient Prompt Tuning](https://arxiv.org/abs/2104.08691)
  - [[2104.09864] RoFormer: Enhanced Transformer with Rotary Position Embedding](https://arxiv.org/abs/2104.09864)
  - [[2106.04554] A Survey of Transformers](https://arxiv.org/abs/2106.04554)
  - [[2111.06377] Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/abs/2111.06377)
  - [[2112.12731] ERNIE 3.0 Titan: Exploring Larger-scale Knowledge Enhanced Pre-training for Language Understanding and Generation](https://arxiv.org/abs/2112.12731)
  - [[2201.08239] LaMDA: Language Models for Dialog Applications](https://arxiv.org/abs/2201.08239)
  - [[2201.11903] Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)
  - [[2203.15556] Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556)
  - [[2204.05862] Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2204.05862)
  - [[2205.01068] OPT: Open Pre-trained Transformer Language Models](https://arxiv.org/abs/2205.01068)
  - [[2205.05198] Reducing Activation Recomputation in Large Transformer Models](https://arxiv.org/abs/2205.05198)
  - [[2205.10625] Least-to-Most Prompting Enables Complex Reasoning in Large Language Models](https://arxiv.org/abs/2205.10625)
  - [[2205.11916] Large Language Models are Zero-Shot Reasoners](https://arxiv.org/abs/2205.11916)
  - [[2206.07682] Emergent Abilities of Large Language Models](https://arxiv.org/abs/2206.07682)
  - [[2207.01780] CodeRL: Mastering Code Generation through Pretrained Models and Deep Reinforcement Learning](https://arxiv.org/abs/2207.01780)
  - [[2208.03299] Atlas: Few-shot Learning with Retrieval Augmented Language Models](https://arxiv.org/abs/2208.03299)
  - [[2210.02414] GLM-130B: An Open Bilingual Pre-trained Model](https://arxiv.org/abs/2210.02414)
  - [[D] GPT-3, The $4,600,000 Language Model : r/MachineLearning](https://www.reddit.com/r/MachineLearning/comments/h0jwoz/d_gpt3_the_4600000_language_model/)
  - [Alibaba Cloud Launches 'ModelScope,' An Open-Source Model-as-a-Service (MaaS) Platform that Comes with Hundreds of Artificial Intelligence (AI) Models - MarkTechPost](https://www.marktechpost.com/2022/11/21/alibaba-cloud-launches-modelscope-an-open-source-model-as-a-service-maas-platform-that-comes-with-hundreds-of-artificial-intelligence-ai-models/)
  - [Aligning Language Models to Follow Instructions](https://openai.com/blog/instruction-following/)
  - [AlphaGo](https://www.deepmind.com/research/highlighted-research/alphago)
  - [Anthropic](https://www.anthropic.com/)
  - [BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension | Facebook AI Research](https://ai.facebook.com/research/publications/bart-denoising-sequence-to-sequence-pre-training-for-natural-language-generation-translation-and-comprehension/)
  - [Better Language Models and Their Implications](https://openai.com/blog/better-language-models/)
  - [BigScience](https://bigscience.huggingface.co/)
  - [BlenderBot 3: An AI Chatbot That Improves Through Conversation | Meta](https://about.fb.com/news/2022/08/blenderbot-ai-chatbot-improves-through-conversation/)
  - [Building safer dialogue agents](https://www.deepmind.com/blog/building-safer-dialogue-agents)
  - [Chat GPT (可能)是怎麼煉成的 - GPT 社會化的過程](https://www.youtube.com/watch?v=e0aKI2GGZNg)
  - [ChatGPT cheats? Triangle professors grapple with viral AI technology as semester starts](https://www.newsobserver.com/news/local/article270952057.html)
  - [ChatGPT produces made-up nonexistent references | Hacker News](https://news.ycombinator.com/item?id=33841672)
  - [ChatGPT, Open AI's Chatbot, Is Spitting Out Biased, Sexist Results - Bloomberg](https://www.bloomberg.com/news/newsletters/2022-12-08/chatgpt-open-ai-s-chatbot-is-spitting-out-biased-sexist-results)
  - [ChatGPT: Optimizing Language Models for Dialogue](https://openai.com/blog/chatgpt/)
  - [Code for CodeT5: a new code-aware pre-trained encoder-decoder model.](https://github.com/salesforce/CodeT5)
  - [Colossal-AI](https://colossalai.org/)
  - [DeepMind’s AlphaCode AI writes code at a competitive level | TechCrunch](https://techcrunch.com/2022/02/02/deepminds-alphacode-ai-writes-code-at-a-competitive-level/)
  - [Democratizing access to large-scale language models with OPT-175B](https://ai.facebook.com/blog/democratizing-access-to-large-scale-language-models-with-opt-175b/)
  - [Don’t Ban ChatGPT in Schools. Teach With It. - The New York Times](https://www.nytimes.com/2023/01/12/technology/chatgpt-schools-teachers.html)
  - [EleutherAI](https://www.eleuther.ai/)
  - [EleutherAI/gpt-neox-20b · Hugging Face](https://huggingface.co/EleutherAI/gpt-neox-20b)
  - [Exploring Transfer Learning with T5: the Text-To-Text Transfer Transformer – Google AI Blog](https://ai.googleblog.com/2020/02/exploring-transfer-learning-with-t5.html)
  - [galactica research model by Meta](https://galactica.org/)
  - [Generative adversarial network - Wikipedia](https://en.wikipedia.org/wiki/Generative_adversarial_network)
  - [GitHub - f/awesome-chatgpt-prompts: This repo includes ChatGPT prompt curation to use ChatGPT better.](https://github.com/f/awesome-chatgpt-prompts)
  - [GitHub - google/BIG-bench: Beyond the Imitation Game collaborative benchmark for measuring and extrapolating the capabilities of language models](https://github.com/google/BIG-bench)
  - [GitHub - huggingface/transformers: 🤗 Transformers: State-of-the-art Machine Learning for Pytorch, TensorFlow, and JAX.](https://github.com/huggingface/transformers)
  - [GitHub - karpathy/nanoGPT: The simplest, fastest repository for training/finetuning medium-sized GPTs.](https://github.com/karpathy/nanoGPT)
  - [GitHub - openai/openai-cookbook: Techniques to improve reliability](https://github.com/openai/openai-cookbook/blob/main/techniques_to_improve_reliability.md)
  - [GitHub - PaddlePaddle/PaddleNLP](https://github.com/PaddlePaddle/PaddleNLP)
  - [GitHub Copilot · Your AI pair programmer](https://github.com/features/copilot)
  - [github: Jianlin Su bojone](https://github.com/bojone)
  - [GitHub's AI Coding Assistant Copilot Launches - Voicebot.ai](https://voicebot.ai/2022/06/22/githubs-ai-coding-assistant-copilot-launches/)
  - [GLM-130B: An Open Bilingual Pre-Trained Model](https://github.com/THUDM/GLM-130B)
  - [gluebenchmark Leaderboard](https://gluebenchmark.com/leaderboard/)
  - [Google AI Introduces Minerva: A Natural Language Processing (NLP) Model That Solves Mathematical Questions - MarkTechPost](https://www.marktechpost.com/2022/07/04/google-ai-introduces-minerva-a-natural-language-processing-nlp-model-that-solves-mathematical-questions/)
  - [Google Sidelines Engineer Who Claims Its A.I. Is Sentient - The New York Times](https://www.nytimes.com/2022/06/12/technology/google-chatbot-ai-blake-lemoine.html)
  - [Google's Massive New Language Model Can Explain Jokes](https://www.datanami.com/2022/04/22/googles-massive-new-language-model-can-explain-jokes/)
  - [Got It AI creates truth checker for ChatGPT 'hallucinations' | VentureBeat](https://venturebeat.com/ai/got-it-ai-creates-truth-checker-for-chatgpt-hallucinations/)
  - [GPT-3 Powers the Next Generation of Apps](https://openai.com/blog/gpt-3-apps/)
  - [GSM8K Dataset | Papers With Code](https://paperswithcode.com/dataset/gsm8k)
  - [How come GPT can seem so brilliant one minute and so breathtakingly dumb the next?](https://garymarcus.substack.com/p/how-come-gpt-can-seem-so-brilliant)
  - [How does GPT Obtain its Ability? Tracing Emergent Abilities of Language Models to their Sources](https://yaofu.notion.site/How-does-GPT-Obtain-its-Ability-Tracing-Emergent-Abilities-of-Language-Models-to-their-Sources-b9a57ac0fcf74f30a1ab9e3e36fa1dc1)
  - [HUAWEI Noah's Ark Lab · GitHub](https://github.com/huawei-noah/Pretrained-Language-Model/tree/master/PanGu-%CE%B1)
  - [HuggingFace: Deploy Hugging Face models easily with Amazon SageMaker](https://huggingface.co/blog/deploy-hugging-face-models-easily-with-amazon-sagemaker)
  - [HuggingFace: Fine-tune a pretrained model](https://huggingface.co/docs/transformers/training)
  - [HuggingFace: How to generate text: using different decoding methods for language generation with Transformers](https://huggingface.co/blog/how-to-generate)
  - [HuggingFace: Models](https://huggingface.co/docs/transformers/main_classes/model)
  - [HuggingFace: Pipelines](https://huggingface.co/docs/transformers/main_classes/pipelines)
  - [HuggingFace: Tokenizer](https://huggingface.co/docs/transformers/main_classes/tokenizer)
  - [HuggingFace: Uploading models](https://huggingface.co/docs/hub/models-uploading)
  - [Improving language models by retrieving from trillions of tokens](https://www.deepmind.com/publications/improving-language-models-by-retrieving-from-trillions-of-tokens)
  - [Improving Language Understanding by Generative Pre-Training](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)
  - [Introducing FLAN: More generalizable Language Models with Instruction Fine-Tuning](https://ai.googleblog.com/2021/10/introducing-flan-more-generalizable.html)
  - [Introducing Pathways: A next-generation AI architecture](https://blog.google/technology/ai/introducing-pathways-next-generation-ai-architecture/)
  - [Jonathan Hui: How much do I like ChatGPT?](https://jonathan-hui.medium.com/how-much-do-i-like-chatgpt-3d8a3216e137)
  - [LaMDA and the Sentient AI Trap | WIRED](https://www.wired.com/story/lamda-sentient-ai-bias-google-blake-lemoine/)
  - [LaMDA: our breakthrough conversation technology](https://blog.google/technology/ai/lamda/)
  - [Language Model – AI2 Blog](https://blog.allenai.org/tagged/language-model)
  - [Large Language Models and Where to Use Them: Part 1](https://txt.cohere.ai/llm-use-cases/)
  - [M6 by Alibaba: MultiModality-to-MultiModality Multitask Mega-transformer](https://www.infoq.cn/article/xIX9lekuuLcXewc5iphF)
  - [Microsoft dumping ton of cash into ChatGPT Office infusion | AppleInsider](https://appleinsider.com/articles/23/01/10/microsoft-dumping-ton-of-cash-into-chatgpt-office-infusion)
  - [Microsoft Set To Integrate ChatGPT With Bing | CDOTrends](https://www.cdotrends.com/story/17758/microsoft-set-integrate-chatgpt-bing)
  - [Minerva: Solving Quantitative Reasoning Problems with Language Models – Google AI Blog](https://ai.googleblog.com/2022/06/minerva-solving-quantitative-reasoning.html)
  - [Mosaic LLMs (Part 2): GPT-3 quality for <$500k](https://www.mosaicml.com/blog/gpt-3-quality-for-500k#:~:text=The%20bottom%20line%3A%20it%20costs,10x%20less%20than%20people%20think.)
  - [nanoGPT/scaling_laws.ipynb at master](https://github.com/karpathy/nanoGPT/blob/master/scaling_laws.ipynb)
  - [New and Improved Content Moderation Tooling](https://openai.com/blog/new-and-improved-content-moderation-tooling/)
  - [New York City Department of Education Bans ChatGPT](https://www.govtech.com/education/k-12/new-york-city-department-of-education-bans-chatgpt)
  - [OpenAI ‘GPT-f’ Delivers SOTA Performance in Automated Mathematical Theorem Proving | Synced](https://syncedreview.com/2020/09/10/openai-gpt-f-delivers-sota-performance-in-automated-mathematical-theorem-proving/)
  - [OpenAI begins piloting ChatGPT Professional, a premium version of its viral chatbot | TechCrunch](https://techcrunch.com/2023/01/11/openai-begins-piloting-chatgpt-professional-a-premium-version-of-its-viral-chatbot/)
  - [OpenAI Codex](https://openai.com/blog/openai-codex/)
  - [OpenAI Just Released the AI It Said Was Too Dangerous to Share](https://futurism.com/the-byte/openai-released-ai-dangerous-share)
  - [OpenAI Model index for researchers](https://beta.openai.com/docs/model-index-for-researchers)
  - [OpenAI says its text-generating algorithm GPT-2 is too dangerous to release.](https://slate.com/technology/2019/02/openai-gpt2-text-generating-algorithm-ai-dangerous.html)
  - [OpenAI's new ChatGPT bot: 10 dangerous things it's capable of](https://www.bleepingcomputer.com/news/technology/openais-new-chatgpt-bot-10-dangerous-things-its-capable-of/)
  - [Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer – Google Research](https://research.google/pubs/pub45929/)
  - [Pathways Language Model (PaLM): Scaling to 540 Billion Parameters for Breakthrough Performance](https://ai.googleblog.com/2022/04/pathways-language-model-palm-scaling-to.html)
  - [PyTorch-NLP](https://modelzoo.co/model/pytorch-nlp)
  - [Ray Distributed Computing - Anyscale](https://www.anyscale.com/ray-open-source)
  - [Research | Stanford HAI](https://hai.stanford.edu/research)
  - [Researcher Tells AI to Write a Paper About Itself, Then Submits It to Academic Journal](https://futurism.com/gpt3-academic-paper)
  - [Salesforce’s CodeRL Achieves SOTA Code Generation Results With Strong Zero-Shot Transfer Capabilities | Synced](https://syncedreview.com/2022/07/07/salesforces-coderl-achieves-sota-code-generation-results-with-strong-zero-shot-transfer-capabilities/)
  - [Solving (Some) Formal Math Olympiad Problems](https://openai.com/blog/formal-math/)
  - [Stable Diffusion 2-1 - a Hugging Face Space by stabilityai](https://huggingface.co/spaces/stabilityai/stable-diffusion)
  - [SuperGLUE: A Stickier Benchmark for General-Purpose Language Understanding Systems](https://papers.nips.cc/paper/2019/hash/4496bf24afe7fab6f046bf4923da8de6-Abstract.html)
  - [Techniques for Training Large Neural Networks](https://openai.com/blog/techniques-for-training-large-neural-networks/)
  - [Temporary policy: ChatGPT is banned - Meta Stack Overflow](https://meta.stackoverflow.com/questions/421831/temporary-policy-chatgpt-is-banned)
  - [TensorFlow Hub](https://www.tensorflow.org/hub)
  - [The Annotated Transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html)
  - [Twitter @goodside as of Jan 2023](https://twitter.com/goodside/status/1598874674204618753?lang=en)
  - [Twitter @goodside as of Jan 2023](https://twitter.com/goodside/status/1610482565106012160)
  - [Twitter @Grady_Booch as of Jan 2023](https://twitter.com/Grady_Booch/status/1593033061423550464)
  - [Twitter @sama as of Jan 2023](https://twitter.com/sama/status/1599671496636780546?lang=en)
  - [What is GPT-3? Everything your business needs to know about OpenAI’s breakthrough AI language program | ZDNET](https://www.zdnet.com/article/what-is-gpt-3-everything-business-needs-to-know-about-openais-breakthrough-ai-language-program)
  - [Who Ultimately Owns Content Generated By ChatGPT And Other AI Platforms?](https://www.forbes.com/sites/joemckendrick/2022/12/21/who-ultimately-owns-content-generated-by-chatgpt-and-other-ai-platforms/?sh=50c960845423)
  - [Why Meta’s latest large language model only survived three days online | MIT Technology Review](https://www.technologyreview.com/2022/11/18/1063487/meta-large-language-model-ai-only-survived-three-days-gpt-3-science/)
  - [Wu Dao 2.0: China’s Answer To GPT-3. Only Better](https://analyticsindiamag.com/wu-dao-2-0-chinas-answer-to-gpt-3-only-better/)
  - [Zhuiyi Technology](https://en.zhuiyi.ai/)
</details>


## TODO: V2.1 Reference list
