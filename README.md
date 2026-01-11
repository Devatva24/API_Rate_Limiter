# API Rate Limiter – Spring Boot

## 📌 Overview
This project implements an API Rate Limiter using Spring Boot and Bucket4j.
It limits the number of requests per client IP.

## ⚙️ Tech Stack
- Java
- Spring Boot
- Redis
- Bucket4j

## 🚦 Rate Limiting Rule
- 5 requests per minute per IP

## 🧠 Algorithm Used
- Token Bucket Algorithm

## 🏗️ Architecture
Client → Filter → Rate Limiter → Controller

## ▶️ How to Run
1. Start Redis
2. Run Spring Boot app
3. Hit endpoint `/api/test`

## 🧪 Test
Send more than 5 requests in a minute:
You will receive `429 Too Many Requests`
