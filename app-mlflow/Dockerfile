# Use the official MLflow image
FROM ghcr.io/mlflow/mlflow:v2.19.0

ENV MLFLOW_BACKEND_STORE_URI=sqlite:////app/data/mlflow.db
ENV MLFLOW_ARTIFACT_ROOT=/app/data/mlruns

# or, in the CMD:
CMD ["mlflow", "server", \
     "--backend-store-uri", "sqlite:////app/data/mlflow.db", \
     "--default-artifact-root", "/app/data/mlruns", \
     "--host", "0.0.0.0", \
     "--port", "5000"]

