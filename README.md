# BioASQ 
Repository for the TU Vienna Course Advanced Information Retrieval.

## Task Description

Large-scale biomedical semantic indexing and question answering. 

__Task goal__: Biomedical questions (English) + expert (reference) answers.
The participants have to respond with (retrieve) relevant articles, and
snippets from designated resources, as well as exact and "ideal"
answers.

Irrespective of the chosen task, three different approaches need to be
implemented and submitted for evaluation:
1. a “traditional” IR model, cf. Crash Course IR Block
2. a “neural” NLP representation learning approach
3. a “neural” re-ranking model

Depending on the task models discussed in the online lectures might
be applicable more directly or might need adaptation. Follow the rules of the respective shared task on whether pre-trained
models are allowed, and which requirements need to be met.

You can choose the complexity of the approaches as long as you make
a valid point why they fall in the corresponding categories; no trivial
or random submissions other than exploring baselines (no extra points)
$\Rightarrow$ Make your own contribution, i.e., do not just use a repository from a
past year, but improve upon existing solutions

__Report:__
- How you addressed the challenges faced
- Which approaches and resources you used to address the challenges
- Where your own contribution lies
- How your submissions performed (metrics), how you did on the leaderboard

## Dataset Information

- Document, passage, entity retrieval – you can pick one or many!
- Status: Training data available, test data later
- Released at https://participants-area.bioasq.org/datasets/ - here we consider the dataset for task b BioASQ13 (year 2025)
- Needs extra registration for downloading
- Data available & evaluated in batches, individual winners, multiple phases
- The development dataset consists of biomedical questions in English, along with their gold concepts, articles, snippets, RDF triples, "exact" answers, and "ideal" answers in the following JSON format.


### Types of Questions

The benchmark datasets contain four types of questions:
- _Yes/no questions_: These are questions that, strictly speaking, require "yes" or "no" answers, though of course in practice longer answers will often be desirable. For example, "Do CpG islands colocalise with transcription start sites?" is a yes/no question.
- _Factoid questions_: These are questions that, strictly speaking, require a particular entity name (e.g., of a disease, drug, or gene), a number, or a similar short expression as an answer, though again a longer answer may be desirable in practice. For example, "Which virus is best known as the cause of infectious mononucleosis?" is a factoid question.
- _List questions_: These are questions that, strictly speaking, require a list of entity names (e.g., a list of gene names), numbers, or similar short expressions as an answer; again, in practice additional information may be desirable. For example, "Which are the Raf kinase inhibitors?" is a list question.
- _Summary questions_: These are questions that do not belong in any of the previous categories and can only be answered by producing a short text summarizing the most prominent relevant information. For example, "What is the treatment of infectious mononucleosis?" is a summary question.

## Grading

Points for documented valid submissions
1. “Traditional” IR model: max. 10 pts
2. “Representation learning” approach: max. 20 pts
3. “Neural” re-ranking model: max. 20 pts
Report quality: max. 10 pts

__Bonus point opportunities__
- For creative extra work, e.g., other subtasks, if you have fun and time, go for it and you’ll get extra points
- Best AIR teams per task get bonus points too!

