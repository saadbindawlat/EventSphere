# EventSphere 🎟️

**EventSphere** is a full-stack event management platform that allows users to create, manage, and attend events. It features secure authentication, dynamic event handling, and a responsive UI for both event organizers and attendees.

## 🛠️ Tech Stack

- **Frontend:** React, Next.js, Tailwind CSS, Clerk (for authentication)
- **Backend:** Node.js, Express
- **Database:** MongoDB (Mongoose)
- **Deployment:** Vercel (Frontend), Render (Backend)



## 🚀 Getting Started

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/EventSphere.git
cd EventSphere
```

### Step 2: Set Up and Run the Backend

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend/` directory with the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
CLERK_SECRET_KEY=your_clerk_secret_key
```

Then run the backend server:

```bash
npm start
```

The backend should now be running at:  
**http://localhost:5000**

### Step 3: Set Up and Run the Frontend

Open a new terminal window:

```bash
cd frontend
npm install
```

Create a `.env.local` file inside the `frontend/` directory with the following:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_frontend_api
NEXT_PUBLIC_API_BASE_URL=http://localhost:5000
```

Then run the frontend dev server:

```bash
npm run dev
```

