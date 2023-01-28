# 我个人对“Google在LLM怎么就被动了”做一点反思。
`纯个人行为，和公司无关。`

一直到chatGPT发布以前，我都觉得Google在大语言模型（LLM）方面是领先的，但”被动“一词，是现在大家都认可的用来形容Google面对ChatGPT的状态。我希望直接做一些事，但工作内容不是我自己说了算，也有更厉害的同事去做。所以我只能工作之余多做一些学习，去思考一些问题，比如到底是什么时候哪些地方Google的选择造成现在的被动？

## ChatGPT有几项关键技术，大致列了一下，希望大家指正补充。
- 17年6月，DeepMind提出了RLHF概念，但是在游戏和机器人模拟环境下。有意思的是博客中还提到和OpenAI合作，那时候OpenAI在Robotics投入很大。
- 17年6月，Google发布Transformer，成为后来所有LLM的基础架构。
- 18年6月，OpenAI发布只有解码器的GPT-1（1.1亿参数），没有激起浪花。
- 18年10月，Google发布只有编码器的BERT（最大3.5亿参数），可以用来微调下游任务，风光无限。
- 19年2月，OpenAI发表了GPT-2系列论文，最大的模型有15亿参数。OpenAI说这个模型太危险不能分享，被群嘲。
- 19年9月，OpenAI使用RLHF（但是论文说human preference而不是human feedback）用来微调GPT2（7.7亿参数版本），没有引起关注。
- 19年10月，Google发布基于编码解码器的T5（BERT只有编码，GPT只用解码）。最大模型110亿参数并开放。兼容BERT和GPT的下游任务，再风光。
- 20年5月，OpenAI公布GPT-3论文（1750亿参数），谈到prompt engineering（著名的“Lets think step by step”），模型不公开，只通过API形式半开放。
- 20年9月，OpenAI用小型GPT3（130亿参数）使用RLHF技术来总结长文（ChatGPT用到了RLHF），算法也是PPO。
- 21年10月，Google发表FLAN论文（1370亿参数），这里开始转向decoder-only，还提出了ChatGPT用到的instruction tuning概念。
- 21年11月，DeepMind发表Gopher论文（2800亿参数），加入LLM大战，没有太多浪花。
- 22年1月，Google发表LaMDA论文（1370亿参数，decoder-only），就是那个著名的“有意识”（sentient）的内部模型。当时觉得Google在LLM遥遥领先。
- 22年3月，OpenAI发表InstructGPT（1750亿参数），提到用到了instruction finetune和RLHF，效果不错，但是没有引起关注。
- 22年3月，DeepMind发表Chinchilla（700亿参数)，卖点是发现新的scaling law（计算资源更多应该怎么平衡数据量和模型增长），有一些关注。
- 22年4月，Google发布Jeff Dean的下一代Pathways系统的旗舰PaLM（5400亿参数，decoder-only），文中提到了神奇的“Chain of Thought”
- 22年9月，DeepMind发表Sparrow（700亿），加入了RLHF，还加入了Retrieval（Google Search），但是反应平平。
- 22年12月，OpenAI发布ChatGPT产品，号称用了InstructGPT技术，大家一用，惊呼未来已来，Google要挂。

## 从现在2023年1月当事后诸葛亮回过去看，有这么几个点Google错失了一些时间
- 如果decoder-only（只有解码器）是王道，Google同时期押注encoder-decoder的T5（还花很多资源做T5X架构并开源），错失20个月。2019年2月GPT2出来，号称写假新闻以假乱真的时候，Google看起来不喜欢decoder-only，而是投入了encoder-decoder的T5。一直到2021年10月FLAN才开始转变到decoder-only。
- 如果紧密大模型（dense LLM）是王道，Jeff Dean押注了Mixture of Experts的松散多模态结构全力投入Pathways下一代AI架构，而DeepMind又加入LLM竞争太晚，这里错失了18个月。2020年5月GPT3出来，参数增加100倍，加一些炫酷的prompt还能解数学，但可能让很多严谨的Google科学家不认可。18个月后，DeepMind2021年11月才训练去GPT3更大模型，Google2022年4月才发布3倍于GPT3的PaLM。话说这波Mixture of Experts中国国内有几个跟风的比如智源和阿里都训练的万亿参数的MoE模型。
- RLHF上（GPT3.5到ChatGPT），DeepMind和Google起了个大早，但迟到了24个月。2017年6月DeepMind就提出RLHF，2020年9月OpenAI用了RLHF在GPT3上面。DeepMind到2022年9月在Sparrow才用到RLHF（Anthropic这家startup都已经发表他们的RLHF论文5个月了）。Google到现在好像还没有RLHF在LLM上的论文。

## 反观OpenAI的速度
- Instruction finetune（用来训练GPT3.5）如果是关键，那Google和DeepMind在2021年10月发明了它以后，一直到2022年12月没有重视过（去将基础模型聊天化）。OpenAI只花了5个月用到了InstructGPT（chatgpt的基础论文）。
- Chain of Thought如果是一些ChatGPT解题的关键（个人猜测，没有数据或论文），那Google还在用它玩票一样训练一些做大学功课的大模型，ChatGPT默默在产品化。

## 不是总结的总结
看起来OpenAI现在走在了最前面，微软的联姻让两者更强。Meta的Lecun大神说OpenAI的ChatGPT也就搞了点技术，没啥研究突破。我倒怀疑ChatGPT不写论文应该还是有些私货的，起码数据方面有很多技巧。但即使真的研究没差距，比的还有技术实现和用户体验嘛。作为一个小小股东，希望Google和DeepMind尽快赶上。
