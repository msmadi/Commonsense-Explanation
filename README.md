# Commonsense-Explanation
A Benchmark Arabic Dataset for Commonsense Explanation
# Introduction
Language comprehension and commonsense knowledge validation by machines are challenging tasks that are still under researched and evaluated for Arabic text. In this paper, we present a benchmark Arabic dataset for commonsense explanation. The dataset consists of Arabic sentences that does not make sense along with three choices to select among them the one that explains why the sentence is false. Furthermore, this paper presents baseline results to assist and encourage the future evaluation of research in this field. The dataset is distributed under the Creative Commons CC-BY-SA 4.0 license.

# Example
Select the most corresponding reason why this statement is against common sense.

Statement: He put an elephant into the fridge.

Reasons:

A: An elephant is much bigger than a fridge. (correct)

B: Elephants are usually white while fridges are usually white.

C: An elephant cannot eat a fridge.

# Dataset
The Arabic dataset for commonsense validation is based on the  Commonsense Validation and Explanation (ComVE) task https://github.com/wangcunxiang/SemEval2020-Task4-Commonsense-Validation-and-Explanation We translated the original English dataset for commonsense Explanation. Each example in the provided dataset is composed of four sentences: \{s1, o1, o2, o3\} . S1 is a natural sentence against the fact and does not make sense, where o1, o2, and o3 are three options that explain why that sentence does not make sense and the task is to select the most correct out of them.

To the best of our knowledge, there is no Arabic dataset publicly available for commonsense Explanation. The provided dataset has 12k rows and consists of three files: train, validation, and test file. 

# Evaluation
The task is evaluated using accuracy. 

# Citation
If you find this project helpful, you can cite:

Saja AL-Tawalbeh, Mohammad AL-Smadi : A Benchmark Arabic Dataset for Commonsense Explanation, arXiv, 2020


@misc{altawalbeh2020benchmark,
      title={A Benchmark Arabic Dataset for Commonsense Explanation}, 
      author={Saja AL-Tawalbeh and Mohammad AL-Smadi},
      year={2020},
      eprint={2012.10251},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}

# Related Research 
Is this sentence valid? An Arabic Dataset for Commonsense Validation
https://arxiv.org/abs/2008.10873

@misc{tawalbeh2020sentence,
    title={Is this sentence valid? An Arabic Dataset for Commonsense Validation},
    author={Saja Tawalbeh and Mohammad AL-Smadi},
    year={2020},
    eprint={2008.10873},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}

# License
The dataset is distributed under the CC BY-SA 4.0 license.
