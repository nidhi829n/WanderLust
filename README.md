<div align="center">

# 🌍 WanderLust

### *Discover Your Next Adventure, Anywhere in the World.*

[![MERN Stack](https://img.shields.io/badge/Stack-MERN-blue?style=for-the-badge&logo=mongodb)](https://mongodb.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://gitpoint.co)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=for-the-badge)]()

*A modern, full-stack vacation rental marketplace web application designed for seamless property listing, interactive exploration, and trusted peer reviews.*

</div>

---

## 🚀 Overview

**WanderLust** is a feature-rich clone of a premier vacation rental platform. Built using the **MERN** stack (MongoDB, Express.js, React, Node.js), it offers a robust MVC architecture, highly responsive user interface, secure authentication protocols, dynamic mapping integrations, and cloud-backed media storage.

---

## 🛠️ Tech Stack

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Frontend** | React, Bootstrap, CSS3 | Dynamic, responsive user interface with component-driven architecture. |
| **Backend** | Node.js, Express.js | Scalable RESTful API development and middleware management. |
| **Database** | MongoDB, Mongoose ODM | Flexible NoSQL database schema design with robust data validation. |
| **Authentication** | Passport.js, Express Sessions | Secure session-based authentication with encrypted credential storage. |
| **Maps & Geo** | Mapbox GL JS | Interactive client-side map rendering and geocoding services. |
| **Media Storage** | Cloudinary, Multer | Optimized cloud-based image hosting and multi-part form parsing. |

---

## ✨ Key Features

*   **🔐 Advanced Authentication & Authorization:** Comprehensive sign-up, secure login/logout workflows, and protected route management via Passport.js.
*   **🏠 Dynamic Listing Lifecycle:** Full CRUD operations allowing hosts to create, read, update, and delete vacation stays effortlessly.
*   **🌍 Interactive Map Integration:** Real-time visual coordinates powered by Mapbox, pinning precise locations for every available property.
*   **📝 Peer Review System:** Interactive feedback ecosystem enabling verified users to write, grade, and inspect community reviews.
*   **🖼️ Cloud Image Management:** Seamless multi-image uploading capability utilizing Cloudinary for fast, secure content delivery.
*   **🛡️ Robust Security Measures:** Input sanitization, password hashing, and error-handling wrappers ensuring absolute application stability.
*   **🧱 MVC Architecture:** Clean separation of concerns following the Model-View-Controller design pattern for supreme maintainability.

---

## 📸 Visual Showcase

| Explore Listings | Create New Listing | Interactive Map View |
| :---: | :---: | :---: |
| ![Explore Listings](explore-page.png) | ![Create Listing](create-listing.png) | ![Map View](map.png) |

---

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/nidhi829n/WanderLust.git
cd WanderLust
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in the project root and add the following environment variables:

```env
PORT=8080
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret
CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
MAPBOX_TOKEN=your_mapbox_access_token
```

### 4️⃣ Run the Application

```bash
node app.js
```

The application will be available at:

```text
http://localhost:8080/listings
```

---

# 📡 API Endpoints Overview

| Method | Endpoint | Description | Access Control |
| :------ | :-------- | :---------- | :------------- |
| `GET` | `/listings` | View all vacation stays | Public |
| `GET` | `/listings/new` | Display form to create a new listing | Authenticated Users |
| `POST` | `/listings` | Create a new listing | Authenticated Users |
| `GET` | `/listings/:id` | View detailed information about a listing | Public |
| `GET` | `/listings/:id/edit` | Display form to edit a listing | Listing Owner |
| `PUT` | `/listings/:id` | Update an existing listing | Listing Owner |
| `DELETE` | `/listings/:id` | Delete a listing | Listing Owner |
| `POST` | `/listings/:id/reviews` | Add a review to a listing | Authenticated Users |
| `DELETE` | `/listings/:id/reviews/:reviewId` | Delete a review | Review Author |
---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/nidhi829n/WanderLust/issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

<div align="center">
  <p>Crafted with ❤️ by <a href="https://github.com/nidhi829n">Nidhi</a></p>
</div>

