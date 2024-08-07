<br />

<p align="center">
  Twitter clone in Next.Js and Firebase
</p>

## Features ✨

- Authentication with Firebase Authentication
- Strongly typed React components with TypeScript
- Users can:
  - Add tweets
  - Like, retweet, and reply to tweets
  - Delete tweets
  - Add a tweet to bookmarks
  - Pin their tweet
  - Add images and GIFs to tweets
  - Follow and unfollow other users
  - See their and other followers and the following list
  - See all users and the trending list
  - Edit their profile
- Realtime updates for:
  - Likes
  - Retweets
  - User profile
  - Trending data from Twitter API
- Responsive design for mobile, tablet, and desktop
- Customizable site color scheme and background
- All image uploads are stored on Firebase Cloud Storage

## Tech 🛠

- [Next.js](https://nextjs.org)
- [TypeScript](https://www.typescriptlang.org)
- [Tailwind CSS](https://tailwindcss.com)
- [Firebase](https://firebase.google.com)
- [SWR](https://swr.vercel.app)
- [Headless UI](https://headlessui.com)
- [React Hot Toast](https://react-hot-toast.com)
- [Framer Motion](https://framer.com)

## Development 💻

Here are the steps to run the project locally:

1. **Clone the repository:**

2. **Install Depedencies**

   ```bash
   npm i
   ```

3. **Create a Firebase project and select the web app**

4. Add your Firebase config to .env.development
   - Note that "NEXT_PUBLIC_MEASUREMENT_ID" is optional.

5. **Enable the following Firebase services:**
   - Authentication: Enable the Google sign-in method.
   - Cloud Firestore: Create a database and set its location to your nearest region.
   - Cloud Storage: Create a storage bucket.

6. **Install Firebase CLI globally:**
   
   ```bash
   npm i -g firebase-tools
   ```

7. **Log in to Firebase:**

   ```bash
   firebase login
   ```

8. **Get your project ID:**

   ```bash
   firebase projects:list
   ```

9. **Select your project ID:**

   ```bash
   firebase use your-project-id
   ```

10. **Deploy Firestore rules, Firestore indexes, and Cloud Storage rules:**

   ```bash
   firebase deploy --except functions
   ```

11. **Run**

   ```bash
   npm run dev
   ```
