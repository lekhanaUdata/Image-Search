# 🔍 Image Search Application

A responsive web application that allows users to search and browse images dynamically using the Unsplash API. Users can enter keywords, view high-quality images, and load additional results through pagination.

---

## 🚀 Features

* Search images using keywords
* Real-time image retrieval from Unsplash
* Responsive and modern user interface
* Load more images with pagination
* Click images to view them on Unsplash
* Dynamic content rendering using JavaScript
* Mobile-friendly design

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Fetch API
* Unsplash API

---

## 📂 Project Structure

```text
Image-Search-App/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## ⚙️ How It Works

1. User enters a search term.
2. The application sends a request to the Unsplash API.
3. Unsplash returns matching image results.
4. Images are displayed dynamically on the webpage.
5. Clicking an image opens the original image page on Unsplash.
6. The "Show More" button loads additional images using pagination.

---

## 🔄 Workflow

```text
User Enters Search Keyword
            │
            ▼
      Search Button
            │
            ▼
      Unsplash API
            │
            ▼
      Fetch Results
            │
            ▼
 Display Images Dynamically
            │
            ▼
      Show More Button
            │
            ▼
   Load Next Page Results
```

---

## 🌐 API Integration

The application uses the Unsplash Search API to retrieve images based on user queries.

Example Request:

```text
https://api.unsplash.com/search/photos?page=1&query=nature&client_id=YOUR_ACCESS_KEY
```

The API returns image metadata including:

* Image URL
* Description
* Photographer details
* Unsplash page links

---

## 🧠 Key Concepts Demonstrated

### DOM Manipulation

Creating and displaying image elements dynamically.

### Fetch API

Retrieving image data from external services.

### Async/Await

Handling asynchronous API requests efficiently.

### Pagination

Loading additional search results without refreshing the page.

### Event Handling

Responding to form submissions and button clicks.

### Responsive Design

Ensuring compatibility across desktop, tablet, and mobile devices.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Image-Search-App.git
```

Navigate to the project folder:

```bash
cd Image-Search-App
```

Open `index.html` in your browser.

---

## 🔑 API Configuration

1. Create an account on Unsplash.
2. Generate an API Access Key.
3. Replace the placeholder value in `script.js`.

```javascript
const accessKey = "YOUR_UNSPLASH_ACCESS_KEY";
```

4. Save the file and run the application.

---

## 🎯 Learning Outcomes

This project helped in understanding:

* REST API Integration
* JavaScript Fetch API
* Dynamic Content Rendering
* Pagination Techniques
* Responsive UI Design
* Event Handling
* Async Programming

---

## 🔮 Future Enhancements

* Infinite scrolling
* Image download functionality
* Search history
* Favorite images feature
* Advanced filtering options
* Dark mode support
* Search suggestions

---

## 💡 Interview Questions

### Why did you use the Unsplash API?

The Unsplash API provides access to a large collection of high-quality images and supports keyword-based searches.

### What is pagination?

Pagination divides large datasets into smaller chunks, improving performance and user experience.

### Why use async/await instead of callbacks?

Async/await improves code readability and simplifies asynchronous operations.

### What is DOM Manipulation?

DOM manipulation allows JavaScript to dynamically create, update, and remove webpage elements.

### What happens when the user clicks "Show More"?

The page number increases and another API request is sent to retrieve additional image results.

### Why is API key security important?

Exposing API keys publicly can lead to unauthorized usage and rate-limit issues.

---

## 👨‍💻 Author

**Udata Lekhana Surya Bhanu**

GitHub: https://github.com/lekhanaUdata

---

## 📄 License

This project is open source and available under the MIT License.
