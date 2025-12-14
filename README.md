# Full Stack Job Portal with React JS, Tailwind CSS, Supabase, Clerk, Shadcn UI 🔥🔥
# Job Portal Application

WEBSITE SCREENSHOTS-:
<img width="1894" height="1015" alt="Screenshot 2025-12-14 150309" src="https://github.com/user-attachments/assets/f1b53553-8c4f-4ab6-9947-0a0924e8dd30" />


<img width="1865" height="1011" alt="Screenshot 2025-12-14 150446" src="https://github.com/user-attachments/assets/e7e9394e-d743-4aa2-8588-605072b01737" />

<img width="1903" height="1009" alt="Screenshot 2025-12-14 150428" src="https://github.com/user-attachments/assets/436e33a5-aa44-4821-8d0a-629a1b4e276b" />

<img width="1877" height="946" alt="Screenshot 2025-12-14 150318" src="https://github.com/user-attachments/assets/bb57198a-b37f-43cb-a985-9c48ecddf290" />
<img width="1813" height="973" alt="Screenshot 2025-12-14 150415" src="https://github.com/user-attachments/assets/b5dc5918-3f65-43ef-9a1f-c902a41f0b1f" />


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

git clone [(https://github.com/siddharthcode-24/Full-stack-Job-Porta)]

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

[http://localhost:5173]

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

