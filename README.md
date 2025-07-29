
# 📈 Fear & Greed Tracker Frontend

This is the frontend for the **Market Sentiment Tracker**, designed to visualize the **Fear & Greed Index** data provided by the backend API. It's built using **React**, **Tailwind CSS**, and **Chart.js** for rich interactivity and responsive visualizations.

---

## 🔥 Features

* 🎯 Displays **today's Fear & Greed Index** with dynamic styling based on sentiment.
* 💬 Provides a **brief commentary** to help interpret market sentiment.
* 📊 Shows **historical trends** for the **last 7 days** and **last 30 days** in separate charts.
* 🗓️ Allows selection of **month and year** to view specific historical data.
* 🚫 Gracefully handles missing data (e.g., weekends, no data).
* 📱 Fully **responsive design** optimized for desktop and mobile devices.

---

## 🛠️ Technology Stack

| Tech             | Purpose                                  |
| ---------------- | ---------------------------------------- |
| **React**        | Component-based UI structure             |
| **Tailwind CSS** | Utility-first CSS for styling            |
| **Chart.js**     | Graphs for historical data visualization |
| **JavaScript**   | Logic and API data handling              |
| **Google Fonts** | Modern typography (e.g., Inter)          |

---

## 🚀 Getting Started Locally

### 🔧 Prerequisites

* A modern web browser (Chrome, Firefox, Edge, Safari).
* A local HTTP server to avoid CORS issues with `file://`.

#### Option A (Recommended): **VS Code Live Server**

1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code.
2. Right-click on `index.html` and choose **"Open with Live Server"**.

#### Option B: **Node.js + http-server**

```bash
npm install -g http-server
cd your-folder/
http-server . -p 8000
```

Then, open [http://localhost:8000](http://localhost:8000) in your browser.

---

### ⚙️ Backend Dependency

This frontend depends on a running Spring Boot backend.
 Ensure your backend is running at:
   `http://localhost:8080`


---

## 🧪 Configuration

The API base URL is hardcoded in your frontend:

```js
const API_BASE_URL = `The RESTapi you have at backend`;
```

> 🛠️ **For production**, change this URL to match your deployed backend (e.g. Render, Railway).

---

## 🌍 Deployment

Since this is a **static site**, you can deploy it easily to:

* 🔼 [Netlify](https://www.netlify.com/)
* ⚡ [Vercel](https://vercel.com/)
* 🐙 [GitHub Pages](https://pages.github.com/)

### Steps:

1. Push your code (including `index.html` and any assets) to a GitHub repo.
2. Connect your repo to a hosting service.
3. Deploy and share your live sentiment tracker!
