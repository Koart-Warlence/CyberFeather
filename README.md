# CyberFeather

CyberFeather is a community-based software on GitHub, resembling StackOverFlow in its functionality.

https://cyber-feather-koart-warlences-projects.vercel.app/

## Installation

1. Install dependencies:

   ```
   npm install
   ```

2. Set up environment variables: Create a `.env.local` file in the project root and configure the following environment variables:

   ```
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=YOUR_PUBLIC_CLERK_PUBLISHABLE_KEY
    CLERK_SECRET_KEY=YOUR_CLERK_SECRET_KEY

    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
    NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
    NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

    NEXT_CLERK_WEBHOOK_SECRET=YOUR_WEBHOOK_SECRET

    NEXT_PUBLIC_TINY_EDITOR_API_KEY=YOUR_PUBLIC_TINY_EDITOR_API_KEY

    MONGODB_URL=YOUR_MONGODB_CONNECTION_STRING

    NEXT_PUBLIC_SERVER_URL=http://localhost:3000
    OPENAI_API_KEY=YOUR_OPENAI_API_KEY
   ```

Make sure to replace these values with the respective actual values.

3. Start the project:

   ```
   npm run dev
   ```

   The project will run at `http://localhost:3000`.

## Features

- **Day/Night/System Mode**:
  - Switch between different color schemes based on user preferences.
- **Third-party Authentication Support**:
  - Provides authentication through third-party platforms.
- **Special Functionality**:
  - Evaluates community engagement based on user participation, including question-asking, answering, and ratings received from others.
- **Comprehensive Search**:
  - Enables search across all pages, including tag questions and answers.
- **Markdown Code Blocks**:
  - Allows the creation of Markdown code blocks using an editor.
- **Save Favorite Threads**:
  - Users can bookmark discussions they like.
- **Custom Tag Categories**:
  - Offers various custom tag classifications.
- **Flexible Sorting Options**:
  - Newest / Recommended / Frequent / Unanswered.
  - _Recommended_ suggests relevant results based on the user's past exploration of similar questions.

## Technologies Used

- React
- Next.js
- Tailwind CSS
- Shadcn UI
- Clerk Auth
- MongoDB
- Vercel
