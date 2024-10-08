# Stat 360 -- Introduction to Generative AI Winter 2025
Stat 360 course materials



# Course Lectures 

Lecture notes can be found on the course Canvas website. 


| Lecture                  |  Date | Material | Readings                
|--------------------------|-------|----------|----------------------------|
| Week 1, Thursday         | January 4 |   Introduction  | [Perplexity](https://thegradient.pub/understanding-evaluation-metrics-for-language-models/), [Perplexity 2](https://web.stanford.edu/~jurafsky/slp3/3.pdf), [Linear Models](https://see.stanford.edu/materials/aimlcs229/cs229-notes1.pdf)  |
| Week 2, Tuesday           | January 9  | Attention |  [Attention is All You Need](https://arxiv.org/pdf/1706.03762.pdf), [Attention Mechanisms](https://lilianweng.github.io/posts/2018-06-24-attention/), [Attention with code](https://sebastianraschka.com/blog/2023/self-attention-from-scratch.html), [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) |
| Week 2. Thursday       | January 11 | Transformers |  [Intro to Transformers](https://arxiv.org/pdf/2304.10557.pdf), [Discussion](https://www.columbia.edu/~jsl2239/transformers.html), [Blog post](https://peterbloem.nl/blog/transformers), [Skip connections](https://theaisummer.com/skip-connections/), [Layer normalization](https://www.kaggle.com/code/halflingwizard/how-does-layer-normalization-work), [Byte-Pair Encoding](https://huggingface.co/learn/nlp-course/chapter6/5?fw=pt) |
| Week 3, Tuesday        | January 18| BERT, GPT, LLAMA | [Annotated GPT 2](https://jalammar.github.io/illustrated-gpt2/),  [GPT-2 paper](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf), [Adversarial attacks on GPT-2](https://arxiv.org/abs/2012.07805) [LLAMA Paper](https://scontent-ord5-1.xx.fbcdn.net/v/t39.8562-6/333078981_693988129081760_4712707815225756708_n.pdf?_nc_cat=108&ccb=1-7&_nc_sid=e280be&_nc_ohc=it_GnOgZ1hMAX_qDhzS&_nc_ht=scontent-ord5-1.xx&oh=00_AfCZyg0NnnD2SfBipL7DBQ467rntvBHugEZo7maieJZNTQ&oe=65ACEFE2), [BERT](https://arxiv.org/pdf/1810.04805.pdf), [Understanding BERT](https://jalammar.github.io/illustrated-bert/)|
| Week 3, Thursday           | January 23| Prompt Tuning, chain of thought, hindsight chain of thought, backwards chain of thought, Graph of Thought, Tree of Thought, Training Chain-of-Thought via Latent-Variable Inference, prompt engineering | [Language Models are Few Shot Learners](https://arxiv.org/abs/2005.14165), [Zero shot chain of thought](https://arxiv.org/abs/2205.11916), [LLMs are human-level prompt engineers](https://arxiv.org/abs/2211.01910), [Tree of Thought](https://arxiv.org/abs/2305.10601), [Chain of verification](https://arxiv.org/abs/2309.11495), [Promptbreeder](https://arxiv.org/abs/2309.16797), [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide?tab=readme-ov-file), [Open-AI Prompting Guide](https://platform.openai.com/docs/guides/prompt-engineering/six-strategies-for-getting-better-results)  |
| Week 4, Tuesday         | January 4 |   Multi-Agent LLMs  | [Wonderful Team](https://wonderful-team-robotics.github.io/), [ReWoo](https://arxiv.org/abs/2305.18323), [Reasoning with Language Model](https://arxiv.org/abs/2305.14992), [LLM+P](https://arxiv.org/abs/2304.11477), [ReACT](https://arxiv.org/abs/2210.03629), [AgentVerse](https://arxiv.org/abs/2308.10848)  |
| Week 4, Thursday          | January 25| Fine tuning, tool use, parameter-efficient fine tuning, LORA, Instruction Tuning (SFT), Neftune, quantization | [LORA](https://arxiv.org/abs/2106.09685), [PEFT](https://huggingface.co/blog/peft), [Quantization](https://arxiv.org/abs/2305.14314), [Quantization Blog](https://lilianweng.github.io/posts/2023-01-10-inference-optimization/),  [Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html), [ToolEMU](https://toolemu.com/), [NEFTune](https://arxiv.org/abs/2310.05914), [Tool Use code](https://python.langchain.com/docs/modules/agents/how_to/intermediate_steps), [Model Calibration](https://arxiv.org/abs/2012.15723) |
| Week 5, Tuesday        | January 30 | Hugging face, fine tuning LLAMA    | [Mistral Fine Tuning](https://github.com/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb), [LLAMA fine tuning](https://github.com/facebookresearch/llama-recipes/blob/main/examples/quickstart.ipynb)|
| Week 5, Thursday          | February 1| No class | |
| Week 6, Tuesday        | February 6|  RAG, when to use RAG vs SFT, lexacagraphical vs semantic search, sentence transformers, Retrieval transformers and long term memory in transformers, RAG Code. | [RAG](https://arxiv.org/pdf/2312.10997.pdf), [RAG code](https://python.langchain.com/docs/use_cases/question_answering/#quickstart), [Sentence Transformers](https://arxiv.org/abs/1908.10084), [Retrieval Transformers](https://jalammar.github.io/illustrated-retrieval-transformer/), [Improving Neural Language Models with a Continuous Cache](https://openreview.net/forum?id=B184E5qee), [Advanced RAG](https://github.com/NisaarAgharia/Advanced_RAG) |
| Week 6, Thursday       | February 8| ChatGPT and RLHF, rejection sampling, DPO, Gopher Cite   |[Stack LLAMA](https://huggingface.co/blog/stackllama), [Instruct GPT](https://arxiv.org/pdf/2203.02155.pdf), [PPO](https://arxiv.org/abs/1707.06347), [DPO](https://arxiv.org/abs/2305.18290), [RLHF References](https://github.com/opendilab/awesome-RLHF), [TRL](https://github.com/huggingface/trl), [Gopher Cite](https://arxiv.org/abs/2203.11147), [Chain of hindsight](https://arxiv.org/abs/2302.02676) |
| Week 7, Tuesday           | February 13| Asking questions about images. Conditional layer norm, FILM, CLIP, BLIP, LAVA | [BLIP](https://arxiv.org/abs/2301.12597), [CLIP](https://openai.com/research/clip), [Llava](https://llava-vl.github.io/), [FiLM](https://arxiv.org/pdf/1709.07871.pdf)  |
| Week 7, Thursday       | February 15| Diffusion models, DDPM, classifier-free guidance   | [Diffusion](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/), [DDPM](https://arxiv.org/abs/2006.11239), [Diffusion as SDEs](https://arxiv.org/abs/2011.13456), [Classifier Free Guidance](https://sander.ai/2022/05/26/guidance.html), [Diffusion code](https://github.com/huggingface/diffusion-models-class/blob/main/unit1/01_introduction_to_diffusers.ipynb), [More low level code](https://github.com/acids-ircam/diffusion_models/blob/main/diffusion_03_waveform.ipynb)|
| Week 8, Tuesday       | February 20| Stable Diffusion, tuning stable diffusion, Brian’s code  | [Stable Diffusion](https://en.wikipedia.org/wiki/Stable_Diffusion), [Illustrated Stable Diffusion](https://jalammar.github.io/illustrated-stable-diffusion/), [Understanding Stable Diffusion](https://scholar.harvard.edu/binxuw/classes/machine-learning-scratch/materials/stable-diffusion-scratch)  |
| Week 8, Thursday   | February 22| Frontiers, using LLMs to help diffusion models by planning out images. Instance recognition and inserting new objects %s tricks. Consistency models, SD Edit,  Diffusion in robotics.                                      | |
| Week 9, Tuesday |  February 27| Presentations  | |
| Week 9, Thursday   |  February 29| Presentations |  |
| Week 10, Tuesday   |  March 5th| Presentations  |  |



# Homeworks and Due Dates


| Project title                  | Date released | Due date                
|--------------------------------|---------------|-------------------------|
|   Assignment 1       | Jan 9   | Jan 25  |
|     Assignment 2      |  Jan 30   | Feb 15  |
| Final presentation topic proposals |       |  Feb 15   | 
|  Final presentations        |       | Feb 27  |
