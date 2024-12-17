# **👑 King'o News**

![Logo](src/assets/screenshots/logo.png)

A dynamic **news portal** application built with **Angular** that allows users to read trending articles, manage accounts, and interact with live news content via **NewsAPI**. The project features user authentication, CRUD operations, and admin management capabilities.

---

## **Features**

- 🔐 **Google Authentication** for secure user login.
- 👤 **User Management** (CRUD): Create, Read, Update, and Delete user accounts.
- 📰 **Trending News**: List of the most recent news articles.
- 🗂️ **Category Filtering**: Filter news articles by specific categories.
- 🔎 **Search Functionality**: Search for articles of your choice.
- 📨 **Contact Form**: Send us a message for any issues.
- 🌐 **API Integration**: Full manipulation of the **NewsAPI**.

---

## **Screenshots**

### **1. Home Page (Before Login)**
The first page a user sees with an interactive header and display poster.
![1](src/assets/screenshots/1.png)

### **2. Home Page (User Logged In)**
The logged-in user sees additional functionalities.
![9](src/assets/screenshots/9.png)

### **3. Home Page (Admin Logged In)**
The admin sees enhanced features.
![6](src/assets/screenshots/6.png)

### **4. Manage Account Page**
Accessible to logged-in users for editing or deleting their account.
![7](src/assets/screenshots/7.png)

### **5. Firebase Integration**
User data is stored in Firebase Realtime Database, updated automatically.
![10](src/assets/screenshots/10.png)
![11](src/assets/screenshots/11.png)

### **6. Trending News Page**
Displays news articles fetched from NewsAPI with category filtering.
![3](src/assets/screenshots/3.png)

### **7. Article Details Page**
Detailed information for a selected news article.
![4](src/assets/screenshots/4.png)

### **8. FAQ Page**
Frequently asked questions about the site.
![5](src/assets/screenshots/5.png)

### **9. Admin Panel**
Accessible only to administrators for managing all user data.
![8](src/assets/screenshots/8.png)

---

## **Tech Stack**

- **Front-End**: Angular, Bootstrap
- **Back-End**: NewsAPI, Firebase, FormSubmit

---

## **API Reference**

### **Get Top Headlines**
```http
GET https://newsapi.org/v2/top-headlines?country={COUNTRY}&apiKey={API_KEY}
```
| Parameter     | Type     | Description                                               |
| :------------ | :------- | :-------------------------------------------------------- |
| `apiKey`      | `string` | **Required**. Your API Key                                |
| `country`     | `string` | 2-letter ISO 3166-1 code of the country for top headlines |
| `category`    | `string` | Filter news by category (e.g., business, sports, tech).   |
| `pageSize`    | `int`    | Number of results per request (default 20, max 100).      |

### **Search for Articles**
```http
GET https://newsapi.org/v2/everything?q={SEARCH_TERM}&apiKey={API_KEY}
```
| Parameter     | Type     | Description                                |
| :------------ | :------- | :----------------------------------------- |
| `apiKey`      | `string` | **Required**. Your API Key                 |
| `q`           | `string` | Keywords or phrases to search for articles |

---

## **Run Locally**

Clone the project:
```bash
git clone https://github.com/RedaBoi12/kingo-news
```

Go to the project directory:
```bash
cd kingo-news
```

Install dependencies:
```bash
npm install
```

Run the development server:
```bash
ng serve
```

Access the project at:
```
http://localhost:4200
```

---

## **Color Reference**

| Color       | Hex Code               |
|-------------|------------------------|
| Primary     | ![#1266f1](https://via.placeholder.com/10/1266f1?text=+) `#1266f1` |
| Danger      | ![#f93154](https://via.placeholder.com/10/f93154?text=+) `#f93154` |
| Warning     | ![#ffa900](https://via.placeholder.com/10/ffa900?text=+) `#ffa900` |
| Footer Blue | ![#0d6efd](https://via.placeholder.com/10/0d6efd?text=+) `#0d6efd` |

---

## **Roadmap**

- 🚀 **Upcoming Features**:
  - Like System for Articles
  - Comment System for Articles
  - Premium Subscription Plans
  - Cross-Browser Support

---

## **Feedback**

If you have any feedback, suggestions, or encounter issues, please reach out:
**Email**: [redabusiness10@gmail.com](mailto:redabusiness10@gmail.com)

---

## **Version History**

- **v0.1**: Initial views created.
- **v0.2**: Completed main views.
- **v0.3**: Integrated NewsAPI for article management.
- **v0.4**: Added Google authentication and account management.
- **v1.0**: Finalized complete feature set with admin panel and CRUD operations.

---

## **About the Creator**

Hi, I’m [ElGoumri Reda](https://www.github.com/RedaBoi12), the creator of **King'o News**. This project is my first step into learning Angular, integrating APIs, and building dynamic web applications.

---

## **🛠 Skills**

**Languages**: HTML, CSS, JavaScript, TypeScript  
**Frameworks**: Angular, Bootstrap  
**Tools**: Firebase, RxJS, FormSubmit

---

## **Lessons Learned**

Working on this project taught me:
- How to fully manipulate APIs using Angular's `HttpClient`.
- Building modular, reusable components in Angular.
- Debugging errors effectively and enhancing problem-solving skills.
- Seamlessly integrating authentication systems like Firebase.

This project was a great opportunity to test and expand my front-end development skills while creating a functional, user-friendly news portal.

---
