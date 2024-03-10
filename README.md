# Hotel Management System

 Created to improve my skills in NextJs

## Features

- **Hotel Room Management**: CRUD operations for managing hotel rooms using Sanity.io.
- **Hotel Room Review**: Allow users to leave reviews for hotel rooms.
- **Room Booking**: Implement room booking functionality.
- **Checkout with Stripe**: Seamless payment processing using Stripe.
- **Stripe Webhook**: Handle Stripe events using webhooks.
- **Light / Dark Mode**: Provide a visually appealing user experience with light and dark mode using React Context.
- **Search Functionality**: Allow users to search for rooms based on type and name.
- **Authentication**: Secure user authentication implemented with Auth.JS.
- **Typescript**: Codebase written in TypeScript for enhanced static typing.
- **useSWR Hook**: Utilize the useSWR hook for data fetching and caching.
- **Deployment to Vercel**: Easily deploy your application to Vercel for a scalable hosting solution.

## Getting Started

### Prerequisites

- Node.js installed
- Sanity.io account for managing content
- Stripe account for payment processing

### Installation

1. Clone the repository:

```bash
git clone https://github.com/danutbradescu/hotel-project.git
cd hotel-management

2. Install dependencies:
    npm install

3. Configure your environment variables(this is the principal env):
   - NEXT_PUBLIC_SANITY_PROJECT_ID=***
   - NEXT_PUBLIC_STRIPE_PUBLIC_KEY=***
   - GITHUB_CLIENT_ID=**********
   - GITHUB_CLIENT_SECRET=***
   - GOOGLE_CLIENT_ID= ***
   - GOOGLE_CLIENT_SECRET= *****
   - NEXTAUTH_SECRET = secret
   - SANITY_STUDIO_TOKEN = *****
   - STRIPE_SECRET_KEY= ****
   - NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY = ****
    #Where is ****, you need to add your own key for env.

   ### Usage 

   - npm run dev in terminal
   Open your browser and navigate to http://localhost:3000.
