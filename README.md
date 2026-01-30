# LOX/LOXL ML Drug Discovery Starter (from: ChEMBL)

A simple educational Python notebook (Google Colab) that:
- downloads bioactivity data (IC50) for a LOX/LOXL target from ChEMBL,
- converts SMILES into Morgan fingerprints (RDKit),
- trains a basic ML model (Random Forest),
- predicts activity for new SMILES you provide.

> Note: public datasets usually contain many more inhibitors than activators...

## How to run (easiest)
1. Open the `.ipynb` notebook in Google Colab.
2. Run the cells from top to bottom.

## Files
- `lox_model.ipynb` — main notebook
- `requirements.txt` — dependency list (optional)

## Data source
- ChEMBL (public bioactivity database)

## License
MIT
