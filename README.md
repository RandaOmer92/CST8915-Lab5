# CST8915 Lab 5: Containerizing the Algonquin Pet Store with Docker

**Student Name**: Randa Omer

**Student ID**: 041079985

**Course**: CST8915 Full-stack Cloud-native Development

**Semester**: Fall 2026

---

## Demo Video

🎥 [Watch Demo Video](https://youtu.be/6NWZ0vUBrT4)

---

## Service Repositories (Forks)

- Order Service: https://github.com/RandaOmer92/order-service-L4
- Product Service (Python): https://github.com/RandaOmer92/product-service-python-L4
- Store Front: https://github.com/RandaOmer92/store-front-L4

---

## Docker Hub Images

- Order Service: https://hub.docker.com/r/randaomer92/order-service
- Product Service: https://hub.docker.com/r/randaomer92/product-service
- Store Front: https://hub.docker.com/r/randaomer92/store-front

---

## Deployment Notes

- **Product Service implementation:** Python
- **API host embedded in the Store Front image:** `4.204.238.178` (Azure VM running Docker)
  - Order Service: `http://4.204.238.178:3000`
  - Product Service: `http://4.204.238.178:3030`