# 📝 Next.js Post Feed App

A modern social feed application built with **Next.js 14 App Router** that allows users to create posts, upload images to Cloudinary, and browse a dynamic feed. The project demonstrates real-world Next.js concepts including Server Actions, form validation, database integration, and image uploads.

---

## 🚀 Features

### 🏠 Home Page
- Displays the **latest 2 posts**.
- Quick introduction to the application.
- Easy navigation to the complete feed.

### 📰 Feed Page
- Displays **all posts** stored in the database.
- Shows uploaded images, titles, and content.
- Like button with instant UI updates.

### ✍️ Create New Post
Users can create a new post by providing:

- Title
- Image
- Content

All fields are **required** before submitting the form.

### 🖼️ Image Upload
- Upload images directly to **Cloudinary**.
- Images are stored in the cloud.
- The returned image URL is saved in the database.

### ❤️ Like Posts
- Like button available for every post.
- Likes update instantly without refreshing the page.

### ✅ Form Validation
- Prevents empty submissions.
- Validates required fields before storing data.

### ⚡ Server Actions
- Uses Next.js Server Actions for creating posts.
- Redirects users after successful submission.

### 🗄️ Database
- Stores all post information.
- Stores image URLs returned from Cloudinary.
- Retrieves posts dynamically.

### ⏳ Loading Delay
- Includes a **1-second artificial delay** to simulate real-world loading and demonstrate loading states.

---

# 🛠️ Tech Stack

- Next.js 14
- React
- JavaScript
- App Router
- Server Actions
- SQLite Database
- Cloudinary
- CSS

---

# 📂 Project Structure

```
app/
├── feed/
├── new-post/
├── layout.js
├── page.js

components/
├── post-form.js
├── post.js
├── form-submit.js
├── header.js

lib/
├── posts.js
├── cloudinary.js

public/

posts.db
```

---

# ⚙️ Installation

Clone the repository.

```bash
git clone <repository-url>
```

Go to the project folder.

```bash
cd project-name
```

Install dependencies.

```bash
npm install
```

Create an environment file.

```
.env.local
```

Add your Cloudinary credentials.

```env
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Start the development server.

```bash
npm run dev
```

Open:

```
http://localhost:3000
```

---

# 📦 Required Packages

Some important packages used in this project include:

- next
- react
- react-dom
- cloudinary
- better-sqlite3

Install all dependencies with:

```bash
npm install
```

---

# 🌐 Environment Variables

This project requires the following environment variables.

```env
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

Without these variables, image uploads will not work.

---

# 💾 Database

This project uses **SQLite** for storing:

- Post title
- Content
- Image URL
- Likes
- User information (if applicable)

---

# 📸 Image Storage

Images are uploaded to **Cloudinary**.

After uploading:

1. Image is stored in Cloudinary.
2. Cloudinary returns an image URL.
3. URL is stored in the SQLite database.
4. Feed displays the uploaded image.

---

# 🎯 Learning Objectives

This project demonstrates:

- Next.js App Router
- Server Components
- Server Actions
- Form Handling
- Cloudinary Image Upload
- SQLite Integration
- Environment Variables
- Loading States
- Validation
- Dynamic Data Rendering
- Component-Based Architecture

---

# 🚧 Future Improvements

- User Authentication
- Comments
- Edit Posts
- Delete Posts
- Search Posts
- Pagination
- User Profiles
- Dark Mode

---

# 👨‍💻 Author

Developed by **Vishwam Patel**

Learning modern Full Stack Development with **Next.js 14**.