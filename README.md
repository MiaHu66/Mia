# BIOSTAT 707 Checkpoints

Place the 4,000 Challenge 2012 set-a record files under `data/set-a/` and place `Outcomes-a.txt` at `data/Outcomes-a.txt`. Run `pixi install` once to create or synchronize `pixi.lock`.

- Checkpoint 1: run `pixi run --locked checkpoint1`. This writes `output/checkpoint1.html`, `output/set-a_long.csv`, `output/set-a_wide.csv`, and `output/missingness_outcome_association.csv`. It takes about 1 minute on my laptop.
- Checkpoint 2: run `pixi run --locked checkpoint2`. This writes `output/checkpoint2.html`, `output/cp2_final_model.rds`, and `output/cp2_oof_predictions.csv`. The verified runtime is about 3 minutes on my laptop.

Raw and derived data are ignored by Git. Commit the rendered `output/checkpoint1.html` and `output/checkpoint2.html` as required by the course instructions.
