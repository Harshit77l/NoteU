# NoteU




NoteU is a Notion-like application built with Next.js 14, React, Convex, Tailwind, Clerk, and EdgeStore. It is a real-time database and Notion-style editor that allows you to create, edit, and delete documents. It also allows you to publish your note to the web.

It uses Convex as the backend, which is a real-time database that allows for instant data updates. The application also uses Edgestore, a distributed key-value store, to manage the images and files uploaded by the users.The user authentication is handled by Clerk, a secure and scalable user authentication API.


<img width="1264" height="638" alt="Group 6 (1)" src="https://github.com/user-attachments/assets/36f0196d-d7d6-4b82-92da-90ec1c404330" />


## Live

NoteU - 

### Key Features

* **Real-time Database:** Changes sync instantly. No need to hit save.
  
* **Notion-Style Editor:** Build beautiful documents with a powerful, block-based editor.
  
* **Dynamic UI:** Toggle between light and dark modes, and use a fully collapsible sidebar.

* **Infinite Children:** Create endless nested documents to keep your work organized.

* **Smart Deletion:** Files go to a trash can first, so you can easily recover them.

* **File Management:** Upload, replace, and delete images, and add a custom cover for each document.

* **User Authentication:** Secure logins and private accounts.

* **Web Publishing:** Share any note with a public, unique URL.

* **Mobile-Friendly:** The entire app is fully responsive and looks great on any device.

## Technologies

![NextJS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Shadcn-ui](https://img.shields.io/badge/shadcn/ui-000000.svg?style=for-the-badge&logo=shadcn/ui&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=TypeScript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC.svg?style=for-the-badge&logo=Tailwind-CSS&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF.svg?style=for-the-badge&logo=Clerk&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-ee342f.svg?style=for-the-badge&logo=Convex&logoColor=white)
![Edgestore](https://img.shields.io/badge/Edgestore-a57fff.svg?style=for-the-badge&logo=Edgestore&logoColor=white)

## Installation

1. Clone the repository
2. Install the dependencies

```
npm install
```

3. Set up the environment variables

```
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

4. Run Convex

```
npx convex dev
```

5. Run the development server

```
npm run dev
```

