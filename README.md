# 🍔 Food Ordering Web App (DevOps Project)

A simple and visually appealing **Food Ordering Web Application** built using HTML, CSS, and JavaScript, and deployed using **Docker + Nginx on AWS EC2**.

This project demonstrates a complete **DevOps workflow** from development to deployment.

---

## 🚀 Features

* 🍕 Interactive food menu (Burger, Pizza, Pasta)
* 🖼️ Attractive UI with images
* 🛒 Order button with instant feedback
* 📱 Responsive layout (basic)
* 🐳 Dockerized for easy deployment

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Web Server:** Nginx
* **Containerization:** Docker
* **Cloud:** AWS EC2
* **Version Control:** Git & GitHub

---

## 📁 Project Structure

```
food-ordering-site/
 ├── index.html
 ├── style.css
 ├── script.js
 └── images/
      ├── burger.jpg
      ├── pizza.jpg
      ├── pasta.jpg
```

---

## ⚙️ How to Run Locally

### 1️⃣ Clone the repository

```bash
git clone <your-repo-url>
cd food-ordering-site
```

---

### 2️⃣ Build Docker Image

```bash
docker build -t food-app .
```

---

### 3️⃣ Run Docker Container

```bash
docker run -d -p 80:80 food-app
```

---

### 4️⃣ Access Application

Open in browser:

```
http://localhost/
```

---

## 🌐 Deployment (AWS EC2)

1. Launch EC2 instance
2. Install Docker
3. Clone repository
4. Build and run container
5. Open port **80** in security group
6. Access using:

```
http://<EC2-PUBLIC-IP>/
```

---

## 🔄 DevOps Workflow

```
GitHub → Docker Build → Container Run → EC2 Deployment
```

---

## 📸 Screenshots

*Add screenshots here after deployment (recommended for LinkedIn & resume)*

---

## 🔥 Future Enhancements

* 🛒 Add cart functionality
* 🧾 Order summary page
* 🔐 User login system
* 🗄️ Backend integration (Spring Boot / Node.js)
* ☁️ CI/CD using Jenkins

---

## 👨‍💻 Author

**Shivaprasad Yadav**
DevOps & Cloud Enthusiast

---

## ⭐ Acknowledgement

Images used from free platforms like Unsplash and Pexels.

---

## 📌 Conclusion

This project is a beginner-friendly demonstration of:

* Web development basics
* Docker containerization
* Cloud deployment

Perfect for showcasing **DevOps skills** in interviews and on LinkedIn 🚀

---
