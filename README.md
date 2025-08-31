#  Loop 

This is a full-stack, real-time collaborative application inspired by **  Loop**.  
The project replicates the core features of a modern collaborative workspace — synchronized document editing, personalized dashboards, and integrated AI capabilities.  
It serves as a showcase for building robust, real-time applications using a modern technology stack.

---

## 🌟 Features

- **Real-time Collaborative Editor**  
  Powered by **Liveblocks**, the editor allows multiple users to co-author documents seamlessly with instant updates on changes, cursor positions, and selections.

- **Dynamic Workspaces**  
  Personalized dashboards to manage, create, and organize documents and workspaces.

- **User Authentication**  
  Secure authentication using **Clerk Auth**, including social login options.

- **AI-Powered Content Generation**  
  Integrated with **Google Gemini API** for smart editor features like text generation and summarization.

- **Notification System**  
  Keeps users updated about mentions, document shares, and changes.

- **Public Document Sharing**  
  Generate public links to share documents with non-registered users.

---

## 🚀 Technology Stack

- **Frontend & Backend:** Next.js (App Router)  
- **Styling:** Tailwind CSS  
- **Real-time Collaboration:** Liveblocks  
- **Authentication:** Clerk Auth  
- **Database:** Firebase (Firestore)  
- **AI Integration:** Google Gemini API  
- **Deployment:** Vercel  

---

## 📁 Project Structure

```
 -loop-2.0/
├── app/          # Next.js routes (dashboard, documents, APIs)
├── components/   # Reusable UI components (dashboard, editor, ui, etc.)
├── lib/          # Core utilities (Liveblocks, Firebase setup, helpers)
├── public/       # Static assets (images, fonts)
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites
Make sure you have the following installed:
- **Node.js** (v18.x or higher)  
- **npm** or **yarn**  

### Installation
Clone the repository:
```bash
git clone https://github.com/singhhritik260604-a11y/ -loop-2.0.git
cd  -loop-2.0
```

Install dependencies:
```bash
npm install
# or
yarn install
```

### Configuration
Create a `.env.local` file in the root directory and add the following:

```bash
# Clerk Auth
CLERK_SECRET_KEY=your_clerk_secret_key

# Liveblocks
LIVEBLOCKS_SECRET_KEY=your_liveblocks_secret_key

# Firebase
NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_firebase_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_firebase_app_id
NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=your_firebase_measurement_id

# Google Gemini AI
GEMINI_API_KEY=your_google_gemini_api_key
```

### Running the Development Server
Start the dev server:
```bash
npm run dev
# or
yarn dev
```

Then open your browser and navigate to:  
👉 [http://localhost:3000](http://localhost:3000)

---

## 🤝 Contributing
Contributions are welcome!  
- Open an **issue** to suggest a feature or report a bug.  
- Submit a **pull request** with improvements.  

---

## 📝 License
This project is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for more details.

---

## Sample Images


<img width="2877" height="1489" alt="Screenshot 2025-08-31 184740" src="https://github.com/user-attachments/assets/ef1edae2-589e-41a7-b3b9-7721bb4da2ea" />
<img width="2860" height="1466" alt="Screenshot 2025-08-31 184924" src="https://github.com/user-attachments/assets/3825dfb1-e3aa-4f7f-afea-6a389adf86d6" />
