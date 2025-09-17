# KiksLab

A full-stack MERN sneaker customization and e-commerce platform.

---

## Demo

[Here](https://youtu.be/ocie1_RSzZQ) 
*Watch a quick demo of KiksLab in action!*

---

**Live Site:** [Here](https://kikslab-frontend.vercel.app)
Try the full KiksLab sneaker customization and shopping experience online!*

---

## Getting Started

These instructions will help you set up the project locally for development and testing.

### Prerequisites

- Node.js (v14+ recommended)
- npm or yarn
- MongoDB Atlas or local MongoDB instance

---

### Environment Variables

**Server**  
Create a `.env` file in the `server/` directory with your own credentials:

```
BRAINTREE_MERCHANT_ID=your_id
BRAINTREE_PUBLIC_KEY=your_public_key
BRAINTREE_PRIVATE_KEY=your_private_key
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

**Client**  
If needed, create a `.env` in `client/` for frontend environment variables.

---

### Installation

Install dependencies for both client and server:

```sh
cd client && npm install
cd ../server && npm install
```

---

### Running Locally

Start the backend server:

```sh
cd server
npm run start:dev
```

Start the frontend client:

```sh
cd client
npm start
```

Visit [http://localhost:3000/](http://localhost:3000/) in your browser.

---

## Deployment

### Client (Vercel)

1. Push your code to GitHub.
2. Go to [Vercel](https://vercel.com/) and import your repo.
3. Set the project root to `client/`.
4. Add any required environment variables in the Vercel dashboard.
5. Deploy!

### Server (Railway)

1. Push your code to GitHub.
2. Go to [Railway](https://railway.app/) and create a new project.
3. Link your GitHub repo and set the project root to `server/`.
4. Add environment variables in the Railway dashboard.
5. Deploy!

### Shoe Customizer (GitHub Pages)

1. Push the `shoe-customizer/` folder to a separate branch (e.g., `gh-pages`) or a separate repo.
2. In your repo settings, set GitHub Pages source to the `shoe-customizer/` folder or the `gh-pages` branch.
3. Access your customizer at `https://yourusername.github.io/kikslab/shoe-customizer/`.

---

## Tech Stack

- **Frontend:** React, React Router, Bootstrap, Axios
- **Backend:** Node.js, Express, MongoDB (Mongoose), Braintree, JWT Auth
- **3D Customizer:** HTML/CSS/JS, Three.js

---

## License

This project is for educational purposes. Some assets and code in `shoe-customizer/` are © Codrops 2019.

---

## Credits

- 3D Customizer based on [Codrops](http://www.codrops.com) demo.
- Built with [Create React App](https://github.com/facebook/create-react-app).


