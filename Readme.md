# Notion Clone

This is a Notion clone, a collaborative workspace and note-taking application designed to help individuals and teams organize their tasks, projects, and ideas effectively.

## Features

- **Multi-Platform**: Accessible on web browsers and various devices.
- **Rich Content**: Support for various content types including text, images, videos, code snippets, and more.
- **Collaboration**: Invite team members to collaborate in real-time.
- **Customizable**: Customize your workspace with different templates, themes, and layouts.
- **Organization**: Easily organize your notes, documents, and tasks with nested pages, tags, and filters.
- **Sync**: Synchronize your data across all your devices seamlessly.
- **Offline Mode**: Access your content even when you're not connected to the internet.

## Getting Started

To get started with the Notion clone, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.
   ```
   git clone https://github.com/shresthacodes/Notion-Clone.git
   ```

2. **Install Dependencies**: Navigate into the cloned directory and install the necessary dependencies.
   ```
   cd notion-clone
   npm i
   ```

3. **Generate Keys**: 
***Using:***
- Clerk.com for CLERK_SECRET_KEY
- EdgeStore for EDGE_STORE_ACCESS_KEY
 
```js
  # Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```


1. **Run the Application**: Start the development server to run the application locally.
   ```
   npm run dev
   ```

2. **Access the Application**: Once the server is running, you can access the Notion clone by visiting `http://localhost:3000` in your web browser.

