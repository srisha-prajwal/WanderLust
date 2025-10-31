# 🏡 WanderLust

WanderLust is a **full-stack web application** inspired by Airbnb, designed for exploring, listing, and booking vacation rentals around the world.
Built on MVC Architecture it focuses on seamless user experience and modern web practices.

---

## 🚀 Features

* 🌍 **Browse listings** from different locations
* 🏠 **Add new listings** with images, descriptions, and pricing
* 🧑‍💼 **User authentication** (login/signup)
* 💬 **Reviews & ratings** for each property
* ☁️ **Cloudinary integration** for image uploads
* 📍 **Map view** using Mapbox 

---

## 🧰 Tech Stack

**Frontend:**

* React.js
* HTML5, CSS3, JavaScript
* Bootstrap / Tailwind CSS

**Backend:**

* Node.js
* Express.js
* MongoDB + Mongoose

**Other Integrations:**

* Cloudinary (image storage)
* Mapbox (maps)
* Passport.js (authentication)

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/srisha-prajwal/WanderLust.git
cd WanderLust
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory and add:

```
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_key
CLOUDINARY_SECRET=your_secret
MAPBOX_TOKEN=your_mapbox_token
MONGO_URL=your_mongodb_url
SESSION_SECRET=your_secret
PORT=8080
```

### 4. Start the Server

```bash
npm start
```

Then open: [http://localhost:8080](http://localhost:8080)

---



## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 💡 Future Enhancements

* Wishlist / Favorites system
* Booking and payment integration
* Improved map filtering
* Admin dashboard for property management

---

### 💻 Author

**Srisha Prajwal**
[GitHub Profile](https://github.com/srisha-prajwal)

---
