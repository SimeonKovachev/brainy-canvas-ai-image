
# Brainy Canvas AI Image

Brainy Canvas AI Image is an advanced web application that enables users to generate, edit, and manipulate images using AI-powered tools. With seamless integrations such as **Cloudinary** for image processing and storage, **Clerk** for user authentication, and **MongoDB** for data storage, this project offers a modern solution for AI-driven image editing directly from the browser.

## 🚀 Features

-   🖼 **AI-Powered Image Generation**: Generate images from prompts using powerful AI models, providing unique and creative image outputs.
-   ✏️ **Image Editing and Transformation**: Modify and enhance images in real-time by applying filters, transformations, and overlays.
-   ☁️ **Cloudinary Integration**: Store, optimize, and transform images via the robust Cloudinary API.
-   🔐 **User Authentication with Clerk**: Secure and easy user authentication with Clerk, supporting sign-in, sign-up, and session management.
-   📂 **MongoDB Integration**: Persistent data storage for user-generated content and image history using MongoDB.
-   ⚡ **Next.js Framework**: Fast, SEO-friendly, and performant web application built with Next.js.
-   📱 **Responsive Design**: Fully optimized for both desktop and mobile devices.

## 🛠 Tech Stack

### Frontend:

-   **Next.js** - The React-based framework enabling server-side rendering and static site generation.
-   **Tailwind CSS** - Utility-first CSS framework for rapid UI development.

### Backend:

-   **Cloudinary** - Manages image storage, transformations, and optimizations.
-   **Clerk** - Manages user authentication, sessions, and security.
-   **MongoDB** - NoSQL database for storing user data and image metadata.

### Deployment:

-   **Vercel** - Hosting and deployment for Next.js applications.

----------

## 🎮 Demo

You can check out a live demo of **https://brainy-canvas-ai-image.vercel.app/**: Live Demo

----------


## 🚀 Getting Started

Follow these instructions to set up and run the **Brainy Canvas AI Image** project on your local machine.

### Prerequisites

Ensure you have the following installed:

-   **Node.js** (v14 or higher)
-   **npm** or **yarn**
-   **Cloudinary** account (API Key, API Secret, Cloud Name)
-   **MongoDB** instance (connection URI)
-   **Clerk** account (Publishable Key and Secret Key)

----------

### 🔧 Installation

1.  **Clone the repository**:

    `git clone https://github.com/SimeonKovachev/brainy-canvas-ai-image.git
	cd brainy-canvas-ai-image` 

2.  **Install dependencies**:

  `npm install
  or
  yarn install` 

3.  **Configure environment variables**:

Create a `.env.local` file in the root directory and add your credentials:

    NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    NEXT_PUBLIC_CLOUDINARY_API_KEY=your_cloudinary_api_key
    NEXT_PUBLIC_CLOUDINARY_API_KEY=your_cloudinary_api_key
    NEXT_PUBLIC_CLOUDINARY_API_SECRET=your_cloudinary_api_secret
    
    MONGODB_URL=your_mongodb_url
    
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=your_clerk_sign_in_url
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=your_clerk_sign_up_url
    NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=your_after_sign_in_url
    NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=your_after_sign_up_url 
    
    CLERK_SECRET_KEY=your_clerk_secret_key

4.  **Run the development server**:

`npm run dev` 

Your app will be running at [http://localhost:3000](http://localhost:3000).

----------

## 🛠️ Usage

### Image Generation and Editing:

-   **Generate Images**: Use AI-powered models to generate creative images.
-   **Edit Images**: Apply real-time transformations, filters, and effects to images.
-   **Upload and Store**: Store your edited images on Cloudinary, which handles optimization and transformation.
-   **Download**: Download your edited images or save them to your Cloudinary account.

----------

## 🎉 Key Features

### 1. AI Image Generation

Using AI models, this app can generate images based on user prompts. The generated images can be further edited or transformed on the canvas.

### 2. Cloudinary Image Storage and Processing

The app integrates seamlessly with Cloudinary for image management. Users can upload images, apply transformations (resize, filter, crop), and download their images.

### 3. User Authentication with Clerk

Secure user authentication is managed by Clerk. Users can sign up, sign in, and manage their sessions, with Clerk handling session persistence.

### 4. MongoDB Integration

User-generated content and session data are stored in a MongoDB database, ensuring persistent and scalable data management.

----------

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

----------

## 🤝 Contributing

Contributions are welcome! Here's how you can contribute:

1.  **Fork the repository**.
2.  **Create a new branch** (e.g., `feature/awesome-feature`).
3.  **Commit your changes** (`git commit -m 'Add an awesome feature'`).
4.  **Push to the branch** (`git push origin feature/awesome-feature`).
5.  **Open a pull request**.

----------

## 🙏 Acknowledgments

-   **Cloudinary** for providing an exceptional platform for image storage and transformation.
-   **Clerk** for seamless user authentication and session management.
-   **Next.js** for powering the frontend with server-side rendering and static site generation.
-   **MongoDB** for scalable data storage solutions.

----------

## 📧 Contact

For any questions, suggestions, or feedback, feel free to reach out at simokovachev04@gmail.com
