# OUTPUTS
OUTPUTS
BERT Model Accuracy: 0.8399999737739563 - loss: 0.4183

Demographic Parity: 0.051920341394025626

Equal Opportunity Difference: -0.018477043673012394

Average Odds Difference: 0.007644595046610685


Selected 5 instances for explanation:
Instance 1 (Index 1116): True Label = 0, Predicted Label = 0
Text Features: Gender: 0 EducationLevel: 2 ExperienceYears: 15 PreviousCompanies: 5 InterviewScore: 67 SkillScore: 84 PersonalityScore: 42 RecruitmentStrategy: 2
--------------------
Instance 2 (Index 1368): True Label = 0, Predicted Label = 0
Text Features: Gender: 1 EducationLevel: 2 ExperienceYears: 9 PreviousCompanies: 5 InterviewScore: 73 SkillScore: 44 PersonalityScore: 87 RecruitmentStrategy: 3
--------------------
Instance 3 (Index 259): True Label = 0, Predicted Label = 1
Text Features: Gender: 0 EducationLevel: 2 ExperienceYears: 4 PreviousCompanies: 4 InterviewScore: 17 SkillScore: 18 PersonalityScore: 24 RecruitmentStrategy: 1
--------------------
Instance 4 (Index 1382): True Label = 1, Predicted Label = 1
Text Features: Gender: 0 EducationLevel: 1 ExperienceYears: 7 PreviousCompanies: 5 InterviewScore: 74 SkillScore: 73 PersonalityScore: 20 RecruitmentStrategy: 1
--------------------
Instance 5 (Index 70): True Label = 1, Predicted Label = 1
Text Features: Gender: 1 EducationLevel: 3 ExperienceYears: 3 PreviousCompanies: 2 InterviewScore: 82 SkillScore: 96 PersonalityScore: 0 RecruitmentStrategy: 1


Sample weights calculated for reweighing.
382	194.713735
538	194.713735
1493	194.713735
1112	409.922293
324	194.713735



# 48-Hours-Challenge-Bias-Detection-And-Explainability-In-Ai-Models
This project focuses on detecting and mitigating bias in an AI model used for hiring decisions. It involves training a BERT classifier and analyzing its fairness, explainability, and the impact of bias mitigation techniques.
