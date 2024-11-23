FROM quay.io/astronomer/astro-runtime:9.20.0-python-3.9-base


RUN python -m venv dbt_venv && . dbt_venv/bin/activate && \
    pip install --no-cache-dir dbt-snowflake && deactivate

