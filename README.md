# IUT Datathon — Final Phase Submissions

This repository is an archive of the submissions from the finalist teams selected for the onsite round of the **IUT Datathon**. The competition focused on Bengali hallucination detection and evaluation. The original competition page is available on [Kaggle](https://www.kaggle.com/competitions/bengali-hallucination/overview).

The repository preserves the participating teams’ notebooks, technical reports, and presentation slides so that their approaches can be studied, reproduced, and used as a reference for future Bengali NLP research and competitions.

## Repository contents

| Directory | Description |
| --- | --- |
| [`inference_notebooks/`](./inference_notebooks) | Inference notebooks submitted by each finalist team. |
| [`training_notebooks/`](./training_notebooks) | Training notebooks included by teams that submitted them. |
| [`reports/`](./reports) | Technical reports describing the teams’ methods, experiments, and findings. |
| [`presentations/`](./presentations) | Presentation slides from the onsite final phase. |
| [`By Team/`](./By%20Team) | Team-wise copies of the submitted materials. |

A CSV file containing onsite-round confirmation responses is also included in the repository as part of the original archive.

## Finalist teams

The archive contains materials from the following teams:

- [4ier](./By%20Team/4ier)
- [ArektaGenericTeam](./By%20Team/ArektaGenericTeam)
- [BUET_NeuralX](./By%20Team/BUET_NeuralX)
- [Bitwiz](./By%20Team/Bitwiz)
- [CUET_AL_Masaar](./By%20Team/CUET_AL_Masaar)
- [CutiePookieUrza](./By%20Team/CutiePookieUrza)
- [DU_Outliers](./By%20Team/DU_Outliers)
- [DU_RDANTO](./By%20Team/DU_RDANTO)
- [Huntrix](./By%20Team/Huntrix)
- [JD Crew](./By%20Team/JD%20Crew)
- [Labyrinth](./By%20Team/Labyrinth)
- [Reverse_Attention](./By%20Team/Reverse_Attention)
- [Team ReActive](./By%20Team/Team%20ReActive)
- [hawkeye](./By%20Team/hawkeye)
- [wrongCha](./By%20Team/wrongCha)

## How the archive is organized

Most teams have three kinds of artifacts:

1. **Inference notebook** — the notebook used to generate predictions or demonstrate the final inference pipeline.
2. **Technical report** — a written explanation of the approach, preprocessing, modeling choices, experiments, and conclusions.
3. **Presentation** — the slides prepared for the onsite final round.

Some teams also provide a **training notebook** with additional implementation and experimentation details. The consolidated directories make it easy to compare the same artifact type across teams, while the `By Team` directory keeps each team’s original submission together.

## Exploring a submission

To review a team’s work, start with its report and presentation, then open the corresponding notebook:

```text
reports/<team>_report.pdf
presentations/<team>_presentation.pdf
inference_notebooks/<team>_inference_notebook.ipynb
training_notebooks/<team>_training_notebook.ipynb   # when available
```

Notebook files can be opened with Jupyter Notebook, JupyterLab, or another compatible notebook viewer. PDF files can be viewed directly in GitHub or downloaded for offline reading.

## Running the notebooks

The notebooks are preserved competition submissions rather than a single packaged application. As a result, their dependencies, data paths, model checkpoints, and runtime requirements may differ between teams. Before running a notebook:

1. Open the notebook and review its imports and configuration cells.
2. Check whether it expects files or datasets that are not included in this archive.
3. Install the required Python packages in an isolated environment.
4. Update local paths or credentials only where the notebook requires them.
5. Run the notebook from top to bottom and record the environment used for reproducibility.

The repository does not guarantee that every notebook can be executed unchanged outside the original competition environment.

## Citation and attribution

When reusing an approach, notebook, report, or presentation, please credit the relevant team and link back to this repository. The artifacts remain organized under their original team names to preserve attribution.

## License and data notice

No separate open-source license or redistribution terms are defined in this repository. Review the original competition rules and the terms of any referenced dataset, model, or third-party dependency before reusing the materials or sharing derived work.
