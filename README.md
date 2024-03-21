# LearnHub Project

LearnHub is a web application that serves as a hub for educational videos. Users can browse, view, rate, and comment on various videos shared by the community. Authenticated users can also contribute by creating and sharing their own educational content.

## Tech Stack

- **React**: A popular JavaScript library for building user interfaces.
- **React Router**: A standard library for routing in React applications.
- **Axios**: A promise-based HTTP client for making API requests.
- **React Hot Toast**: A lightweight and customizable notification library.
- **Ant Design**: A design system and React UI library.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **Vite**: A fast and modern build tool for modern web applications.
- **TypeScript**: A statically typed superset of JavaScript that adds optional static typing to the language.

## Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/learnhub-app.git`
2. Navigate to the project directory: `cd learnhub`
3. Install dependencies: `npm install`
4. Start the development server: `npm run dev`
5. Open your browser and visit `http://localhost:3000` to view the application.

## Environment Variables

The project requires the following environment variables to be set:

- `API_HOST`: The base URL for the API endpoint.

You can create a `.env` file in the project root and define the required environment variables there.

## Project Structure

```shell
.
├── App.css
├── App.tsx
├── components
│   ├── Banner.tsx
│   ├── ContentCard.tsx
│   ├── ContentList.tsx
│   ├── Loading.tsx
│   └── Navbar.tsx
├── guards
│   └── GuardedRoute.tsx
├── hooks
│   ├── useContent.tsx
│   └── useContentList.tsx
├── index.css
├── main.tsx
├── pages
│   ├── Content.tsx
│   ├── Create.tsx
│   ├── Edit.tsx
│   ├── Home.tsx
│   ├── Login.tsx
│   └── Register.tsx
├── providers
│   └── AuthProvider.tsx
├── types
│   └── dto.ts
└── vite-env.d.ts
```

- `src/components`: Contains reusable React components.
- `src/guards`: Contains route guards for protecting certain routes.
- `src/hooks`: Contains custom React hooks for data fetching and state management.
- `src/pages`: Contains the different pages of the application.
- `src/providers`: Contains the authentication provider for managing user authentication.
- `src/types`: Contains TypeScript type definitions for data transfer objects (DTOs).

## Development Workflow

- `npm run dev`: Starts the development server and watches for code changes.
- `npm run build`: Builds the production-ready optimized bundle.
- `npm run lint`: Runs ESLint for code linting and quality checks.
- `npm run preview`: Serves the production build locally for testing.

## Features

- **User Authentication**: Users can register, log in, and log out of the application.
- **Content Browsing**: Users can browse and view educational videos shared by the community.
- **Content Rating and Commenting**: Users can rate and leave comments on educational videos.
- **Content Creation**: Authenticated users can create and share their own educational content by providing a video URL, comment, and rating.
- **Content Editing**: Authenticated users can edit the comment and rating of their own shared content.
- **Content Deletion**: Authenticated users can delete their own shared content.
- **Responsive Design**: The application is designed to be responsive and accessible on various devices and screen sizes.

## Code Style and Conventions

The project follows the Airbnb JavaScript Style Guide and uses Prettier for code formatting. ESLint is configured to enforce these coding standards and conventions.

## Known Issues and Limitations

- The application currently does not support video uploads directly from the client. Users can only share videos by providing a video URL.
- The application does not have a search functionality for finding specific videos or content.

## Future Enhancements

- Implement video upload functionality directly from the client.
- Add search and filtering capabilities for videos and content.
- Improve accessibility and usability for users with disabilities.
- Implement social sharing and integration with popular platforms.
- Add support for multiple languages and localization.

## Contributing

Contributions to the LearnHub project are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request on the project's GitHub repository.

## License

The LearnHub project is open-source and released under the [MIT License](https://opensource.org/licenses/MIT).
