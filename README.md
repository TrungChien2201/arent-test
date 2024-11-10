# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Version using in the project
- Nodejs: 16.13.1
- React: 18.3.1
- Npm: 6.14.5

## Setup and Installation

- Install environment and use the version same as above.
- Use Visual Studio Code or appropriate IDE for Reactjs, install extensions: ESLint, Prettier - Code formatter.
- Clone the repository: `git clone https://github.com/TrungChien2201/arent-test.git`
2. Change into the project directory: `cd arent-test`
3. Install dependencies: `npm install` or `yarn install`

## Usage

1. Run the app: `npm run dev` or `yarn dev`
2. Open your web browser and navigate to the link `http://localhost:3000` or `http://127.0.0.1:3000`
4. To preview the app in production mode: run `npm run build` or `yarn build` then run `npm run preview` or `yarn preview`
5. Open your web browser and navigate to the link `http://localhost:3000` or `http://127.0.0.1:3000` (it can be open with other port)
6. Enjoy the awesome features!

## Features

- Top Page 
- My Record
- Column

## Folder StructureHere’s an overview of the project’s structure: 
   
    └── assets/            # Static assets like images, icons
    ├── components
    │   ├── base               # Reusable components
    │   ├── module/            # Page components
    ├── layouts
    │   ├── mainLayout/        # Main layout
    ├── pages
    │   ├── home/              # Top page
    │   ├── column/            # Column page
    │   ├── record/            # Record page
    ├── routes                 # Defined routes
    |── style                  
    │   ├── column             # Column page style
    │   ├── home               # Home page style
    │   ├── layout             # Layout stle
    │   ├── record             # Record page style
    │   ├── _global            # Global css
    │   ├── _variables_        # Common variables css
    ├── utils
    │   ├── constants          # Common variables or constants
    │   ├── interface          # Common interface
    ├── wrappers
    │   ├── CustomRouter       # Custom router
    │   ├── Root               # Custom root element, layout for each page
    |── App.tsx                # Main app component
    │── index.css              # Root css file to reset CSS properties
    │── main.scss              # Main scss file
    │── main.tsx               # Entry point for React
    │── vite-env.d.ts          
    │── eslintrc.cjs           # Config Eslint rules...
    │── .gitignore             # Files and directories to ignore in Git
    │── .prettierrc            # Prettierrc config
    │── index.html             # Root html file
    ├── package.json           # Project metadata and dependencies
    ├── README.md              # This README file
    │── tsconfig.json          # Config file
    │── tsconfig.node.json
    │── vite.config.ts         # Vite config
    └── ...## ContributingContributions are always welcome! Here's how you can get involved:

## Git flow

1. Go to the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Run the command `npm run lint or yarn lint` and `npm run build or yarn build` before commit to GIT branch
4. Make your changes and commit them: `git commit -m 'Add some feature'`
5. Push your changes to the branch: `git push origin feature/your-feature`
6. Submit a pull request

## License

## Contact

If you have any questions or feedback, feel free to reach out to us at chienvu.neon@email.com.