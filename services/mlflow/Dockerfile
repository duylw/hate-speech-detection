FROM ghcr.io/mlflow/mlflow:v3.11.1

# Cài đặt driver PostgreSQL (psycopg2) và AWS SDK (boto3) 
# để MLflow Server có thể kết nối RDS/PostgreSQL làm backend store và S3/MinIO làm artifact store
RUN pip install --no-cache-dir psycopg2-binary boto3
