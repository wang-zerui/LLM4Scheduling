# SchedMate: Large Language Models are DL Scheduling Enhancers

Existing deep learning cluster schedulers make their scheduling decisions on partial job information, such as resource utilization metrics obtained through profiling. Incorporating a broader range of information dimensions could enable these schedulers to make more optimal decisions. Recent advancements in Large Language Models (LLMs) present a promising avenue for efficiently extracting valuable insights from original code base and execution logs, potentially enhancing scheduling efficacy. In this work, we propose SchedMate, designed to enhance the performance of deep learning schedulers by incorporating LLMs and several advanced techniques. It employs an LLM-based agent to meticulously analyze user files within the working directory, extracting comprehensive metadata based on scheduling parameters. SchedMate utilizes a version management module to store and track the historical jobs metadata and their fine-grained changes, enabling fast extraction of metadata for repeated jobs and lower token consumption. We plan to integrate SchedMate into multiple novel DL schedulers to further improve their performance.

```
@inproceedings{zerui2024schedmate,
  title={SchedMate: Large Language Models are DL Scheduling Enhancers},
  author={Wang, Zerui and Hu, Qinghao and Ana Klimovic and Xingcheng Zhang and Peng Sun},
  booktitle={21st USENIX Symposium on Networked Systems Design and Implementation Poster Session (NSDI 24 Poster)},
  year={2024}
}
```
