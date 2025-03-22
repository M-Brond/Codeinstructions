✅ Web App Security Checklist

🔐 Authentication
	•	☐ Use a trusted auth library (e.g., Clerk)
	•	☐ Enable multi-factor authentication (MFA)
	•	☐ Handle password reset & session management via Clerk
	•	☐ Authenticate every API request with Clerk SDK

🧸 Middleware Protection
	•	☐ Add middleware to protect sensitive routes
	•	☐ Validate user identity and permissions before processing any request

🧑‍⚖️ Role-Based Access Control (RBAC)
	•	☐ Define user roles (admin, user, guest, etc.)
	•	☐ Restrict access to features and endpoints based on roles

⚠️ Sensitive Data Handling
	•	☐ Store secrets (API keys, DB credentials) in .env files
	•	☐ NEVER expose secrets to client-side code
	•	☐ Add .env and other sensitive files to .gitignore

⚠️ Error Handling
	•	☐ Show user-friendly and generic error messages on the client
	•	☐ Log detailed error messages only on the server

💬 Input Validation
	•	☐ Sanitize and validate all user input (including search fields)
	•	☐ Prevent SQL injection, XSS, and other input-based attacks

🧰 Database Security
	•	☐ Use a trusted ORM or platform like Supabase
	•	☐ Set up Row-Level Security (RLS) in Supabase
	•	☐ Avoid writing raw queries directly

🖥️ Hosting
	•	☐ Host on secure, managed platforms like Vercel, AWS, or GCP
	•	☐ Ensure firewall, DDoS protection, and auto updates are enabled
