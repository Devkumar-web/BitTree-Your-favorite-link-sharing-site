# BitTree-Your-favorite-link-sharing-site

[![Deployed on Vercel](https://vercel.com/button)](https://bit-tree-your-favorite-link-sharing-site.vercel.app/)

**SimpleLink is a straightforward web application that allows you to consolidate all your important links into one easily shareable page. Perfect for social media bios, resumes, or anywhere you need to provide multiple links in one place.**

## ✨ Key Features

* **Centralized Link Management:** Store all your social media profiles, websites, portfolios, and other important links in one convenient location.
* **Customizable Handle:** Choose a unique handle (e.g., `simplelink.vercel.app/yourhandle`) to share your link page.
* **Easy Link Addition and Management:** A simple interface to add, edit, and organize your links.
* **MongoDB Backend:** Utilizes MongoDB to securely store your handle and associated links.
* **Built with Next.js:** Leverages the power of React and Next.js for a fast and responsive user experience.
* **Deployed on Vercel:** Easily accessible online via the Vercel deployment.

## 🚀 Technologies Used

* **Frontend Framework:** [Next.js](https://nextjs.org/)
* **Backend & Database:** [MongoDB](https://www.mongodb.com/)
* **Deployment:** [Vercel](https://vercel.com/)

## ⚙️ Getting Started (for Development - Optional)

If you're interested in running this project locally for development or to understand the codebase:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Devkumar-web/BitTree-Your-favorite-link-sharing-site.git
    cd BitTree-Your-favorite-link-sharing-site
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```

3.  **Set up MongoDB:**
    * Ensure you have MongoDB installed and running or have access to a MongoDB Atlas cluster.
    * Create a `.env.local` file in the root directory and add your MongoDB connection URI:
        ```
        MONGODB_URI=your_mongodb_connection_string
        ```

4.  **Run the development server:**
    ```bash
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    ```

    Open your browser and navigate to `http://localhost:3000`.

## 💡 How It Works

1.  **Handle Creation:** Users can choose a unique handle. This handle will be part of their public link.
2.  **Link Association:** Once a handle is created, users can associate multiple links (e.g., Twitter, LinkedIn, Portfolio) with that handle.
3.  **Data Storage:** The handle and its corresponding links are stored in a MongoDB database.
4.  **Public Page:** When someone visits `simplelink.vercel.app/yourhandle`, the application fetches the links associated with that handle from the database and displays them on a clean and simple page.

## 🗺️ Future Enhancements

While this project was primarily for learning, here are some potential future features:

* **Customization Options:** Allow users to customize the appearance of their link page (themes, colors, fonts).
* **Analytics:** Track clicks on the links.
* **Link Prioritization:** Allow users to reorder their links.
* **More Link Types:** Add support for embedding media or other types of content.
* **User Authentication:** Implement user accounts for easier management of multiple link pages.

## 🙏 Acknowledgements

This project was created as a learning exercise to improve my understanding of Next.js and MongoDB.

## 🔗 Live Demo

You can see SimpleLink in action here: (https://bit-tree-your-favorite-link-sharing-site.vercel.app/)

---

Feel free to share your BitTree-Your-favorite-link-sharing-site page and connect with others!