# Research scope and status

## Completed in this pilot

- A manually prepared dataset of 15 literary excerpts from five public-domain works.
- A fixed prompt requesting structured JSON interpretation.
- A five-criterion qualitative evaluation rubric.
- A preliminary comparison of four excerpts across Gemini, Claude, and DeepSeek (12 model outputs).
- An interactive HTML explorer that presents the pre-generated outputs and qualitative evaluation records.
- A research presentation outlining the motivation, method, preliminary observations, limitations, and proposed next phase.

## Not completed

- Evaluation of all 15 excerpts across all models.
- Independent validation of the dataset annotations or gold-standard labels.
- A statistically tested benchmark or validated aggregate scoring method.
- A demonstration that one model is generally superior.
- Live inference inside the HTML prototype.
- Movie-clip experiments, multimodal model training, or audiovisual emotion transcription.
- The immersive narrative reader interface or scene visualisation.

## Evaluation criteria

The rubric covers interpretive accuracy, evidence grounding, emotional precision, unsupported inference, and uncertainty calibration. The current review is qualitative; ratings and comments should not be treated as statistically validated measurements.

## Data handling note

The source workbooks are retained in `experiments/` and `data/`. The prototype contains embedded copies of data used for display. When discrepancies arise, inspect the original workbooks and document any future corrections rather than silently changing source records.
