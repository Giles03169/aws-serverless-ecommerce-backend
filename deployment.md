🚀 Deployment Guide

1. Create DynamoDB Table
	•	Table Name: ecommerce-products
	•	Partition Key: productId (String)

2. Add Sample Products

Add several product entries with productId, name, price, description, and image.

3. Deploy Lambda Function
	•	Runtime: Python 3.12
	•	Permissions: Allow access to dynamodb:Scan
	•	Code file: lambda_function.py

4. Configure API Gateway
	•	Create an HTTP API
	•	Route: GET /products
	•	Integration: Lambda function
	•	Enable CORS (allow all origins)
