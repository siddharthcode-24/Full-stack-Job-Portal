# Full Stack Job Portal with React JS, Tailwind CSS, Supabase, Clerk, Shadcn UI Tutorial 🔥🔥
# Job Portal Application
Below is a **ready-to-copy `README.md`**.
Just **select all → copy → paste into your GitHub `README.md` file** 👇

---

```md
# Job Portal Application

A full-stack Job Portal web application where users can search and apply for jobs, and recruiters can post and manage job listings.

---

## Features

### Job Seekers
- User registration and login
- View all job listings
- Search and filter jobs
- Apply for jobs
- View applied jobs

### Recruiters
- Recruiter login
- Post new jobs
- Edit and delete job listings
- View applicants

### Authentication
- Secure authentication
- Role-based access (Job Seeker / Recruiter)
- Protected routes

---

## Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Shadcn UI
- Vite

### Backend & Database
- Supabase (PostgreSQL)

### Authentication
- Clerk Authentication

---

## Project Structure

```

job-portal/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── services/
│   ├── utils/
│   ├── App.jsx
│   └── main.jsx
│
├── public/
├── .env
├── package.json
└── README.md

```

---

## Environment Variables

Create a `.env` file in the root folder and add:

```

VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key

```

---

## Run Locally

1. Clone the repository
```

git clone [https://github.com/your-username/job-portal.git](https://github.com/your-username/job-portal.git)

```

2. Go to the project folder
```

cd job-portal

```

3. Install dependencies
```

npm install

```

4. Start the development server
```

npm run dev

```

5. Open in browser
```

[http://localhost:5173](http://localhost:5173)

```

---

## How Authentication Works

1. User logs in using Clerk
2. Clerk creates a secure session
3. Session token is used for protected routes
4. Supabase manages role-based access

---

## Future Enhancements
- Resume upload
- Email notifications
- Admin dashboard
- Job recommendations

---

## License
MIT License

---

## Author
SIDDHARTH BAJAJ  
B.Tech Computer Science Student  

---

⭐ Star this repository if you find it useful
```

