# LitEval-15: Literary Interpretation Explorer

**Beyond Emotion Labels: Evidence-Grounded Literary Interpretation with Language Models**

This repository contains a small research pilot exploring how language models interpret emotions, context, and implicit meaning in literary excerpts, and whether their interpretations are grounded in textual evidence.

## Research question

How reliably do language models interpret emotions, context, and implicit meaning in literary excerpts, and are those interpretations grounded in textual evidence?

## Repository contents

- `prototype/index.html` — interactive explorer for the pre-generated pilot outputs, model comparisons, evaluation notes, and rubric.
- `data/LitEval-15_dataset.xlsx` — manually prepared dataset of 15 excerpts from five public-domain literary works.
- `experiments/raw_model_outputs.xlsx` — raw structured model responses for the evaluated excerpts.
- `experiments/model_evaluation.xlsx` — qualitative evaluation records.
- `experiments/rubric.xlsx` — five-criterion evaluation rubric and rating guidance.
- `prompts/fixed_literary_interpretation_prompt.txt` — fixed prompt used to request structured interpretations.
- `docs/research_pilot_presentation.pptx` — presentation describing the research question, method, pilot, limitations, and proposed future work.
- `docs/research_scope_and_status.md` — scope, current status, and limitations.

## Dataset and pilot scope

LitEval-15 contains 15 manually prepared excerpts from five public-domain works:

- *Hamlet*
- *Jane Eyre*
- *Alice's Adventures in Wonderland*
- *A Tale of Two Cities*
- *The Strange Case of Dr Jekyll and Mr Hyde*

The dataset includes fields such as summary, dominant and secondary emotions, key characters, theme, primary evaluation skill, difficulty, and evaluation purpose.

**The current exploratory model-comparison pilot covers only four excerpts evaluated by three language models (Gemini, Claude, and DeepSeek), for 12 model outputs.** The remaining dataset excerpts should not be described as evaluated in this pilot.

## Evaluation approach

The pilot uses five qualitative criteria:

1. Interpretive accuracy
2. Evidence grounding
3. Emotional precision
4. Unsupported inference
5. Uncertainty calibration

The prototype displays pre-generated outputs and recorded qualitative assessments. It does not make live model calls, calculate a validated aggregate score, or rank the models.

## Current status

This is an exploratory research prototype, not a validated benchmark or a completed AI product. The annotations have not been independently validated as gold-standard labels, and the pilot has not undergone statistical testing.

## Running the prototype

Open `prototype/index.html` in a modern web browser. The page is self-contained and uses data embedded in the HTML; no server or API key is required.

## Research inspiration and future direction

The project is inspired in part by work on descriptive emotional interpretation, including *Emotion Transcription in Conversation*. This repository does not reproduce that paper's method. Audiovisual dialogue analysis, multimodal experiments, and the immersive narrative reader are proposed future directions; they are not implemented here.

## Notes on source files

The workbook files are included as supplied research records. Some source entries contain inconsistent spelling or labels (for example, a model name is misspelled in one evaluation row). The prototype contains its own embedded presentation data; consult the original workbooks when checking individual records. No unsupported corrections or aggregate scores have been added in this repository.
