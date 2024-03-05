# MUNCH Dataset

The MUNCH (Metaphor Understanding Challenge) dataset,
for testing large language models' capabilities for understanding metaphors as cross-domain mappings.

Overview:
- Input data for testing LLMs are in `tasks/`
    - Prompts: `prompts.md`
    - Paraphrase generation: `generation.json`
    - Paraphrase judgement:
        - For word judgement, input sentences and options are formatted in the same way for all 3 conditions: `word_judge.json`
        - Sentence judgement: `sent_judge_{implicit,msent,mword}.json`
        - Please always shuffle the 2 given options when formatting your prompts.
- Gold labels (human annotations) are in `correct_answers/`
    - For the paraphrase generation task: `for_generation.csv`
    - For the paraphrase judgement task: `for_judgement.csv`
