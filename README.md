# 🛒 AWS Serverless eCommerce Backend

This project demonstrates a full-stack **serverless product catalog backend** using:

- **AWS Lambda**
- **DynamoDB**
- **API Gateway**
- **IAM Roles**
- **Python (boto3)**

It exposes a `GET /products` API endpoint that fetches product data from a DynamoDB table.

---

## 📦 Features

- Serverless product catalog backend
- JSON response via `GET /products`
- CORS-enabled for frontend compatibility
- Fully deployable on free-tier AWS services

---

## 🧪 Sample Product JSON

```json
{
  "productId": "prod001",
  "name": "Wireless Headphones",
  "price": 79.99,
  "description": "Noise-cancelling over-ear headphones",
  "image": "https://your-bucket.s3.amazonaws.com/prod001.jpg"
}
