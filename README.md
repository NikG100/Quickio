<h1 align="center">

  Quickio - E-commerce Platform

</h1>



<!-- Brief -->
<p align="center">
Quickio is a full-fledged e-commerce platform built with React.js, Tailwind CSS, Node.js, and MongoDB. It provides users with a seamless shopping experience, secure authentication, and an intuitive admin panel for product management.
</p>

<!-- Screenshot -->
![Screenshot](./Thumbnail.png)

</a>

## Key Features

👉 Authentication System: A robust authentication system ensuring security and user privacy

👉 Explore Page: Homepage for users to explore posts, with a featured section for top creators

👉 Like and Save Functionality: Enable users to like and save posts, with dedicated pages for managing liked and saved content

👉 Detailed Post Page: A detailed post page displaying content and related posts for an immersive user experience

👉 Profile Page: A user profile page showcasing liked posts and providing options to edit the profile

👉 Browse Other Users: Allow users to browse and explore other users' profiles and posts

👉 Create Post Page: Implement a user-friendly create post page with effortless file management, storage, and drag-drop feature

👉 Edit Post Functionality: Provide users with the ability to edit the content of their posts at any time

👉 Responsive UI with Bottom Bar: A responsive UI with a bottom bar, enhancing the mobile app feel for seamless navigation

👉 React Query Integration: Incorporate the React Query (Tanstack Query) data fetching library for, Auto caching to enhance performance, Parallel queries for efficient data retrieval, First-class Mutations, etc

👉 Backend as a Service (BaaS) - Appwrite: Utilize Appwrite as a Backend as a Service solution for streamlined backend development, offering features like authentication, database, file storage, and more

and many more, including code architecture and reusability


### Built with

- React
- Appwrite
- React Query
- React Router
- React Hook Form
- Typescript
- React lazy-load-image
- Shadcn
- Vite

### Installation

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/NikG100/Snapgram.git
cd SnapGram
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
VITE_APPWRITE_URL=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_STORAGE_ID=
VITE_APPWRITE_USERS_COLLECTION_ID=
VITE_APPWRITE_POSTS_COLLECTION_ID=
VITE_APPWRITE_SAVES_COLLECTION_ID=
```

Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io/).

**Running the Project**

```bash
npm run dev
```

