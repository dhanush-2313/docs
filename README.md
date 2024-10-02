## DocHub

DocHub is a powerful, real-time collaborative document editing platform, inspired by Google Docs. Built with Next.js for the user interface, Liveblocks for real-time collaboration, and styled with TailwindCSS, LiveDocs aims to showcase the developer's expertise in creating a seamless and interactive user experience in a real-time environment.


## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- Liveblocks
- Lexical Editor
- ShadCN
- Tailwind CSS

## <a name="features">Features</a>

 **Authentication**: User authentication using GitHub through NextAuth, ensuring secure sign-in/out and session management.

 **Collaborative Text Editor**: Multiple users can edit the same document simultaneously with real-time updates.

 **Documents Management**
   - **Create Documents**: Users can create new documents, which are automatically saved and listed.
   - **Delete Documents**: Users can delete documents they own.
   - **Share Documents**: Users can share documents via email or link with view/edit permissions.
   - **List Documents**: Display all documents owned or shared with the user, with search and sorting functionalities.

 **Comments**: Users can add inline and general comments, with threading for discussions.

 **Active Collaborators on Text Editor**: Show active collaborators with real-time presence indicators.

 **Notifications**: Notify users of document shares, new comments, and collaborator activities.

 **Responsive**: The application is responsive across all devices and many more, including code architecture and reusability 

## <a name="quick-start"> Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/dhanush-2313/docs.git
cd docs
```

**Installation**

Install the project dependencies using pnpm:

```bash
pnpm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

#Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```

Replace the placeholder values with your actual Clerk & LiveBlocks credentials. You can obtain these credentials by signing up on the [Clerk](https://clerk.com/) and [Liveblocks](liveblocks.io/) website.

**Running the Project**

```bash
pnpm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
