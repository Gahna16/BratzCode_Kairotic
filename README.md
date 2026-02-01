DownSideUp

Problem Statement- 5.	When the Party Falls Apart: Friend groups are the real superpower in Hawkins. But not every student finds their Party. Academic pressure, relocation, or social anxiety can slowly push someone into isolation. Participation drops. Messages go unanswered. Presence fades—quietly. These are not loud emergencies. They are disappearances. Help them out.

Solution- A user friendly social coordination platform that bridges the gap between digital interaction and real-world exploration. The platform enables users to form "Micro-Quests"—small, temporary groups formed with nearby strangers to complete specific social activities.
What makes this project stand out is the "Micro-Quest" Architecture. While platforms like Meetup are for large, planned events and Tinder is for one-on-one dating, your solution fills the "Third Space" of spontaneous, low-stakes group activity.

Key Features & Impact:
1. Safe Exploration: Encourages community discovery by facilitating group outings, making it safer and more comfortable for users to explore unfamiliar areas.

2. Interest-Based Matching: Uses a "Quest" system to connect individuals based on specific, niche interests, ranging from hobbyist exploration to simple social errands (e.g., a quick evening meal).

Hyper-Local Connectivity: Minimizes travel barriers by focusing on "nearby" connections, fostering a stronger sense of immediate neighborhood community (since its for campus level right now).

Demographic Security: Implements age-limit filters to ensure groups are formed within appropriate and comfortable social peer groups.

Low-Stakes Socializing: Lowers the barrier to entry for social interaction by focusing on short-term "quests" rather than long-term commitments.

How to Run
1. Prerequisites
Ensure you have the following installed on your local machine:

Node.js (v18.0 or higher)

npm (comes bundled with Node.js)

A web browser (Chrome or Edge recommended for testing)

2. Installation
Clone the repository:

Bash
git clone https://github.com/Gahna16/BratzCode_Kairotic.git
cd BratzCode_Kairotic
Install dependencies:

Bash
npm install
3. Firebase Configuration
This project requires a Firebase backend to handle worker registrations and QR data.

Create a project in the Firebase Console.

Enable Firestore Database and Google Authentication.

Create a file named .env in the root directory.

Add your Firebase credentials following this format:

Plaintext
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project_id.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project_id.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_id
VITE_FIREBASE_APP_ID=your_app_id
4. Running the Project
To start the development server:

Bash
npm run dev
