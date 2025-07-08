#  AI-Based Biometric Voting System

An advanced and secure voting platform using biometric authentication (fingerprint + face recognition) to ensure transparency, speed, and efficiency in elections. Designed to eliminate fraud, reduce manual effort, and deliver real-time results.

TEAM NAME - QUANTUM SPARKS Checkpoint 1 – Tasks Completed:
Folder structure initialized:
client/ for frontend (React + Vite)
Project initialized using npm init -y
Basic config files added (vite.config.ts, tailwind.config.ts)
Installed frontend and backend dependencies
Created initial components (App.tsx)
Git repository initialized and first commit made

Checkpoint 2 – Tasks Completed:
Added essential project metadata and configuration:
package.json
package-lock.json
README.md
FREE_TECHNOLOGIES_INTEGRATED.md
Documented the list of integrated technologies
Described setup steps and project overview in README.md
Committed all above files as part of second milestone

Checkpoint 3 – Tasks Completed:
Completed and committed all key frontend components:
admin/ – components for admin login and dashboard
public/ – user-side components
ui/ – reusable UI elements
voting/ – core voting interface
Added logic components:
age-verification.tsx
language-provider.tsx and language-selector.tsx
recaptcha.tsx for bot prevention
Frontend logic is now modular, responsive, and ready to be integrated with backend and Ethereum logic

Checkpoint 4 – Tasks Completed:
Integrated essential custom React hooks:
use-admin-auth, use-citizens, use-language, use-mobile, and use-toast
Added reusable blockchain and client utilities in lib/:
blockchain.ts for Ethereum functions
supabaseClient.ts for database interaction
queryClient.ts for React Query setup
utils.ts for general helpers
Created all core frontend pages:
Admin Dashboard & Login
Public Portal & Voting Portal
Not Found / 404 fallback
Frontend now fully structured and logic-ready