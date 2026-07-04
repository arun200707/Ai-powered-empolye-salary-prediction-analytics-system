# TODO — XGBoost training crash fix

- [ ] Update `salary_prediction/src/train_models.py` to skip XGBoost training/tuning when GridSearchCV fails due to sklearn tag incompatibility.
- [ ] Ensure other models still train and evaluation artifacts are generated.
- [ ] Run the full pipeline (`python salary_prediction/src/run_pipeline.py`) and confirm no crash.

