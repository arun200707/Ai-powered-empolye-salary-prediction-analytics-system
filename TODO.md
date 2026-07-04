# TODO — Production-ready Streamlit Cloud deployment

- [x] Repo audit: identified deployment risks (Streamlit app location, deprecated APIs, eager loading)
- [x] Add Streamlit Community Cloud config: `.streamlit/config.toml` with correct `app_location`
- [ ] Replace deprecated Streamlit argument `use_container_width` in `salary_prediction/src/app.py`
- [ ] Optimize startup: lazy-load dataset/results/artifacts only for needed pages
- [ ] Improve exception handling: friendly errors around model prediction and artifact loading

- [ ] Re-run local sanity: `python salary_prediction/src/run_pipeline.py` and `streamlit run salary_prediction/src/app.py`
- [ ] Verify requirements completeness and Linux compatibility

