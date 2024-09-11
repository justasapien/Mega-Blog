# Mega Blog - Free Speech

**Mega Blog - Free Speech** is a dynamic and responsive blogging platform developed using ReactJS, Redux Toolkit, JavaScript, and Tailwind CSS. The application offers a rich blogging experience with features like advanced text formatting, user authentication, and image uploads.

## Features

- **Responsive Design**: Seamless user experience across all devices and screen sizes.
- **Rich Text Editing**: Integrated TinyMCE for advanced formatting in blog posts.
- **State Management**: Utilizes Redux Toolkit for efficient state management.
- **Authentication**: Secure user authentication with Appwrite, allowing users to manage their accounts and content.
- **Image Uploads**: Supports image uploads within blog posts for enhanced content creation.
- **Routing**: React Router DOM for smooth navigation between pages.

## Technologies

- **Frontend**: ReactJS, Redux Toolkit, JavaScript, Tailwind CSS
- **Backend**: Appwrite (for authentication and data management)
- **Rich Text Editor**: TinyMCE
- **Routing**: React Router DOM

## Project Structure

- `src/`
  - `components/` - Contains reusable components like `AuthLayout`, `Login`, etc.
  - `pages/` - Contains page components such as `Home`, `AddPost`, `Signup`, etc.
  - `store/` - Contains the Redux store configuration (`store.js`).
  - `index.css` - Global styles for the application.
  - `App.jsx` - Main application component that integrates the router and layout.

## Installation

To set up and run this project locally:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/Mega-Blog.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd Mega-Blog
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

4. **Create a `.env` file** in the root directory and add your Appwrite credentials:

    ```env
    VITE_APPWRITE_ENDPOINT=your_appwrite_endpoint
    VITE_APPWRITE_PROJECT_ID=your_project_id
    ```

5. **Run the development server:**

    ```bash
    npm run dev
    ```

6. **Open your browser** and navigate to `http://localhost:3000` to view the application.

## Usage

- **Home Page**: Displays a list of blog posts with links to individual posts.
- **Login**: Allows users to log in to their accounts.
- **Signup**: Enables users to create a new account.
- **All Posts**: Shows all available posts.
- **Add Post**: Provides a form to create new blog posts.
- **Edit Post**: Allows users to edit existing posts.
- **Post Detail**: Displays the full content of a single blog post.

## Deployment

The project is deployed on Vercel. You can view the live application [here]([https://your-deployed-app-url](https://mega-blog-eta-sepia.vercel.app/)).

## Contributing

To contribute to this project:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a Pull Request.

## Contact

For any questions or suggestions, feel free to open an issue or contact me at [vikash.sharma.ug21@nsut.ac.in](mailto:vikash.sharma.ug21@nsut.ac.in).
