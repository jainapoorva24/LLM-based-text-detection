This project aims to assess the quality of text summaries by employing a two-step evaluation process. The initial step involves determining whether a summary is AI-generated or not, utilizing a Language Model (LLM). If the summary is identified as AI-generated, it is assigned a reward of 0. On the other hand, if the summary is not classified as AI-generated, it proceeds to the next stage of evaluation.

Two-Step Evaluation:
Step 1: AI Detection using LLM

Objective: Identify whether the given text summary is generated by an AI model.

Model Used: Language Model (LLM)

Reward Assignment: If AI-generated, the summary is rewarded with 0.

Step 2: Content and Wording Evaluation using RandomForest

Objective: Assess the quality of non-AI-generated summaries based on content and wording.

Model Used: RandomForest

Scoring Criteria:
Content Score: Evaluates the richness and relevance of information in the summary. 
Wording Score: Assesses the coherence and fluency of language used in the summary.
