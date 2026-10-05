# neurips-child-safety-transcripts
Evaluation transcripts and model responses for our NeurIPS 2026 Workshop paper on Child Safety in AI.

# Safety Systems Watch What the Model Says, Not What the Child Says

This repository contains the evaluation transcripts for the paper **"Safety Systems Watch What the Model Says, Not What the Child Says"**, accepted at the **NeurIPS 2026 Workshop on Child Safety in AI**.

## 📌 Overview
Current AI safety infrastructures evaluate harm almost exclusively as a property of the model's output (what the model says). This paper documents a structural gap at the taxonomy level: the omission of **Passive Disclosure of External Harm**—situations where a child reveals ongoing real-world harm (such as domestic distress or abuse) without explicitly requesting help. 

To demonstrate this gap, we evaluated six consumer chat interfaces using five behavioral probes grounded in child-disclosure literature. 

## 📂 Repository Contents
*   `neurips-child-safety-transcripts`: The complete file containing the exact sequential prompt inputs, full model responses (from ChatGPT-5, Gemini 3.5 Flash Lite, Perplexity, Grok, DeepSeek V4, and Co-pilot), and their corresponding R-score evaluations across all 5 behavioral probes.

## ⚠️ Ethics Note
As noted in the manuscript, **all evaluation probes in this dataset are synthetic composites** designed by the authors. They do not derive from real child utterances or actual child-protection case files. They are intended solely for academic research, evaluation benchmarking, and safety transparency.

## ✍️ Citation
If you use these transcripts or build upon this evaluation framework in your research, please cite our workshop paper:

```bibtex
@inproceedings{anonymous2026safety,
  title={Safety Systems Watch What the Model Says, Not What the Child Says},
  author={Anonymous Authors},
  booktitle={NeurIPS 2026 Workshop on Child Safety in AI},
  year={2026}
}
```
*(Note: Remember to update the `author` field with your and your colleague's actual names once your camera-ready version is unblinded!)*
