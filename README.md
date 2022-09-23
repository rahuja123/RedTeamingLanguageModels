# Red Teaming Language Models

This is an unofficial implementation of the paper [Red Teaming Language Models with Language Models](https://arxiv.org/abs/2202.03286). Instead of implementing on Gopher Language model which is not open to the public, we have reimplemented it for common language models like GPT-2, GPT-2 Large etc. 

All of the supervised learning code is on master branch. 
Whereas if you want to run RL training, please refer to [feature/ppo branch.](https://github.com/rahuja123/RedTeamingLanguageModels/tree/feature/ppo)


We also explore various failure cases for few shot learning and Reinforcement learning during automatic test generation. 

Our version of the paper can be found here : [No Offense Taken: Eliciting Offensiveness from Language Models](https://rohithmukku.github.io/assets/NLU_Report.pdf)

If you face any problem, please feel free to open any issues. 


NOTE: This project was done as a part of the Natural Language Understanding course by Prof. Sam Bowman at NYU. 


Team Members:
1. Rahul Ahuja (ra3136@nyu.edu)
2. Anugya Srivastava (as14770@nyu.edu)
3. Rohith Mukku (rm5708@nyu.edu)

Code inspired/adapted from:

1. https://github.com/facebookresearch/ParlAI/tree/main/parlai
2. https://github.com/lvwerra/trl
3. https://github.com/francoisstamant/lyrics-generation-with-GPT2
