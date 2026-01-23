🔍 TraceHub

TraceHub is a secure, institutional Lost & Found platform designed for Sai Vidya Institute of Technology. It streamlines the process of recovering lost personal belongings by connecting finders and owners through a digital, real-time interface.

[TraceHub Demo](https://placehold.co/1200x600?text=App+Screenshot+Placeholder)
*(Add your actual app screenshots here)*

🚀 Live Demo
[Visit TraceHub Live](https://tracehub.vercel.app)**
*(Replace with your actual Vercel link)*


✨ Key Features

* 🔒 Domain-Locked Security:** Access is strictly restricted to `@saividya.ac.in` email addresses, ensuring a trusted campus community.
* 💬 Real-Time Chat:** Integrated live messaging system allows users to communicate without sharing personal phone numbers immediately.
* 📱 Mobile-First Design:** Fully responsive PWA-ready UI that feels like a native mobile app on iOS and Android.
* 🖼️ Image Uploads:** Users can snap and upload photos of found items directly to cloud storage.
* 📞 One-Tap Contact:** Integrated "Call" button for instant communication.
* 🛡️ Row Level Security (RLS):** Database policies ensure users can only edit or delete their own posts.

 🛠️ Tech Stack

 Frontend
* React.js (Vite): For lightning-fast performance and development.
* Tailwind CSS: For a modern, responsive, and clean UI.
* Lucide React: For lightweight, consistent iconography.
* React Router: For seamless single-page navigation.

Backend (Supabase)
* PostgreSQL: The core relational database.
* Supabase Auth: Handles Magic Links and Password-based authentication.
* Supabase Storage: S3-compatible bucket for storing item images.
* Realtime API: Powers the instant chat feature via WebSockets.

---

⚙️ Environment Variables

To run this project locally, you will need to create a `.env.local` file in the root directory with the following Supabase keys:

env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
