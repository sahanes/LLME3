<p align = "center" draggable=”false” ><img src="https://github.com/AI-Maker-Space/LLM-Dev-101/assets/37101144/d1343317-fa2f-41e1-8af1-1dbb18399719" 
     width="200px"
     height="auto"/>
</p>

<h1 align="center" id="heading"> 🚇 Session 7: Fine-Tuning</h1>

### [Quicklinks](https://github.com/AI-Maker-Space/LLM-Engineering-Foundations-to-SLMs/tree/main/00_AIM_Quicklinks)

| 🤓 Pre-work | 📰 Session Sheet | ⏺️ Recording     | 🖼️ Slides        | 👨‍💻 Repo         | 📝 Homework      | 📁 Feedback       |
|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|
| [Session 7: Pre-Work](https://www.notion.so/Session-7-Fine-Tuning-Coming-Soon-143cd547af3d80a9af10fade95ad3a20?pvs=4#d21a3fa3f2684b4db256c708336c6712) | [Session 7: Fine-Tuning](https://www.notion.so/Session-7-Fine-Tuning-Coming-Soon-143cd547af3d80a9af10fade95ad3a20) |  [Recording](https://us02web.zoom.us/rec/component-page?action=viewdetailpage&sharelevel=meeting&useWhichPasswd=meeting&clusterId=us02&componentName=need-password&meetingId=-n2vdN6PWvEgNdydcp_6WCIAXZRRq5gOCCFDwuo3t_rLbd2Zff_pCBkxdRDwn7Ok.hsgair8mCe2uMpJF&originRequestUrl=https%3A%2F%2Fus02web.zoom.us%2Frec%2Fshare%2FoZp_0ZXoeaJlgy37hD1mgPQPZlfyPFRrn7fKaGMyChUiHVlK74cyae-wF95zmv5v.bqKOThUv5gRQoyKd)  (G25yk@E0) | [Session 7: Fine-Tuning](https://www.canva.com/design/DAGY7ZxFsRU/-pDrpf61S1_c60nC1ufwnQ/edit?utm_content=DAGY7ZxFsRU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) | You Are Here!  | [Session 7 Assignment: Fine-Tuning](https://forms.gle/oiyErT4ZZgkm6gfN6) |  [Feedback: LLME3 Cohort, Session 7](https://forms.gle/6MvFhqA29L3FAsbY8) |


### Assignment: 

Today's assignments are available in Colab:
- Assignment #1: 
    - [Assignment](https://colab.research.google.com/drive/18KDy41LCsTKpg6M03A94VkGqRuVJx4yA?usp=sharing)
    - [Hardmode Assignment](https://colab.research.google.com/drive/1lXa2jU2_7aEduHI5x2TWZ5x3VawLKSKa?usp=sharing)

1. Breakout Room #1:
  - Task #1: Loading the Model
    - 👪❓ Discussion Question #1
    - ❓ Question #1
    - ❓ Question #2
2. Breakout Room #2:
  - Task #2: Data and Data Prep.
    - 🏗️ Activity #1
  - Task #3: Setting up PEFT LoRA
    - ❓ Question #3
  - Task #4: Training the Model
    - ❓ Question #4
    - ❓ Question #5
  - Task #5: Share Your Model!
    - ❓ Question #6
   
### Hardmode:

Take the [base](https://huggingface.co/meta-llama/Llama-3.1-8B) Llama 3.1 8B model and instruction-tune it using TRL on [this](https://huggingface.co/datasets/yahma/alpaca-cleaned) instruction following dataset. 

Evaluate your final model using the Eleuther AI's [`lm-evaluation-harness`](https://github.com/EleutherAI/lm-evaluation-harness/tree/main) on the [`IFEval`](https://github.com/EleutherAI/lm-evaluation-harness/blob/main/lm_eval/tasks/ifeval/README.md) task.

Report the baseline Llama 3.1 8B model's performance and your model's performance, then compare and contrast your results with Llama 3.1 8B Instruct.

> NOTE: This will consume a large volume of compute credits - and take a long time! Only embark on this journey if you really want to get deep into the weeds!
