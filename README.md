# Question-Answering-System

A small, self-contained example showing how to build and experiment with a question-answering
workflow over a tabular dataset using the included Jupyter notebook.

## Project structure

- `main.ipynb` — Jupyter notebook with the end-to-end demo (data loading, preprocessing,
  retrieval/QA experiments and examples).
- `dataset/dataset.csv` — CSV file used by the notebook as the knowledge source.

## Quickstart

1. (Optional) Create and activate a virtual environment:

	Windows (PowerShell):

	```powershell
	python -m venv .venv
	.\.venv\Scripts\Activate.ps1
	```

2. Install the Python packages required by the notebook. The notebook lists the exact
	packages used; common ones include `pandas`, `scikit-learn`, and `jupyter`.

	```powershell
	pip install -r requirements.txt
	```

	If the project does not include `requirements.txt`, install packages referenced in
	`main.ipynb` manually.

3. Start Jupyter and open the notebook:

	```powershell
	jupyter notebook main.ipynb
	```

4. Run the notebook cells in order. The notebook explains each step and how to adapt the
	pipeline to your own dataset.

## Notes

- The notebook is the primary entry point — it contains runnable code and inline explanations.
- If you want a reproducible environment, I can add a `requirements.txt` or a `pyproject.toml`.

## Contributing

Contributions and suggestions are welcome. Open an issue or send a short description of the
change you'd like to make.

## License

This repository does not include a license file. Add one if you plan to publish or share the
project publicly.
