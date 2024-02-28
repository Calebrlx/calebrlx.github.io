# Personal notes/brainstorming session for another project
might be hard to follow cause its not orginized very well 
you have been warned






Framework: 

/src/app/api/users/route.ts -> https://localhost:3000/api/users
/src/app/(base)/page.tsx -> https://localhost:3000
/src/app/auth/login/page.tsx -> https://localhost:3000/auth/login
/src/app/

## File structure for:

### page.tsx:
- Declarations/Definitions/configurations
    - 'use client'; or 'use server'; (default is server)
    - import X from 'X';
    - import { Y, Z } from '~/components/Y';
    - import A from '~/lib/A';
    - import { type Metadata } from 'next';
- Metadata
    - export const metadata = {
        title: 'Page Title',
        description: 'Page Description',
        keywords: ['keyword1', 'keyword2'],
    }
- Page Component
    - export default function <Page>() {
        return (
            <>
                <A />
                <B></B>
                <p>Page Content</p> {/* Inline comment */}
            </>
        );
    }
- Comments
    - // example
    - /* example */


### <componentName>.tsx
- Declarations/Definitions/configurations
    - 'use client'; or 'use server'; (default is server)
    - import X from 'X';
    - import { Y, Z } from '~/components/Y';
    - import A from '~/lib/A';


### layout.tsx:



### route.ts:







**`/public`**:
   - This directory is used to serve static files like images, fonts, and other assets. Files placed under `/public` can be accessed directly via the browser under the same path. For example, `/public/images/logo.png` can be accessed via `http://localhost:3000/images/logo.png`.

**`/src`**:
   - The `/src` directory is used to keep the source files neatly organized. It's not a special directory in Next.js by default.
   - Inside `/src`, you will find:
     - **`/app`** (App Routing): Contains the application's pages, components, and logic related to routing. It's the heart of the app routing feature in Next.js.
        - **`/api`** (API Routes): Contains the API routes for the application. API routes are used to create a custom API endpoint that can be used to fetch data from the server.
            - **`/<route>/`** (e.g., `/users/`): Contains the API route handlers for a specific route.
                - **`route.ts`**: The API route handler for the specific route. 
        - **`layout.tsx`**: A layout component that wraps the entire application and provides a consistent look and feel across all pages (root).
        - **`global.css`**: Global styles that are applied to the entire application.
        - **`(<directory>)`**: Defines a folder that does not effect route structure.
            - **`layout.tsx`**: A layout component that wraps the entire application and provides a consistent look and feel across all pages (sub-directory).
            - **`page.tsx`**: 
        - SEO:
            - sitemap.ts
            - robots.ts
            - not-found.tsx

     - **`/components`**: For reusable UI components.
     - **`/styles`**: For global stylesheets or module-specific styles.
     - **`/lib`**: For shared libraries or utilities.
     - **`/hooks`**: For custom React hooks.
     - **`/types`**: For TypeScript type definitions.
     - **`middleware.ts`**: For middleware functions.


**`next.config.js`**: Main configuration file for Next.js, where you can customize various aspects of how Next.js works.
**`tsconfig.json`**: Configuration file for TypeScript.
**`postcss.config.js`**, **`tailwind.config.js`**: Configuration files for PostCSS and Tailwind CSS, if the project uses them for styling.
**`package.json`**: Contains metadata about the project and lists the project's dependencies. It also defines scripts for running, building, and testing the application.


# Optional:

**`/prisma`** (if using Prisma):
   - This directory contains Prisma schema files and migrations for applications using Prisma as an ORM for handling database operations.




## Things to consider:
- Is this file typescript complient? 
- 

dir 

- /src
- /public





## config
- config.json 
[
    "package.json": {
        "name": "demo",
        "version": "0.1.0",
        "private": true,
        "scripts": {
            "dev": "next dev",
            "build": "next build",
            "start": "next start",
            "lint": "next lint"
        },
        "dependencies": {
            "react": "^18",
            "react-dom": "^18",
            "next": "14.1.0"
        },
        "devDependencies": {
            "typescript": "^5",
            "@types/node": "^20",
            "@types/react": "^18",
            "@types/react-dom": "^18",
            "autoprefixer": "^10.0.1",
            "postcss": "^8",
            "tailwindcss": "^3.3.0",
            "eslint": "^8",
            "eslint-config-next": "14.1.0"
        }
    },
    "tsconfig.json": {
        "compilerOptions": {
            "lib": ["dom", "dom.iterable", "esnext"],
            "allowJs": true,
            "skipLibCheck": true,
            "strict": true,
            "noEmit": true,
            "esModuleInterop": true,
            "module": "esnext",
            "moduleResolution": "bundler",
            "resolveJsonModule": true,
            "isolatedModules": true,
            "jsx": "preserve",
            "incremental": true,
            "plugins": [
            {
                "name": "next"
            }
            ],
            "paths": {
            "@/*": ["./src/*"]
            }
        },
        "include": ["next-env.d.ts", "**/*.ts", "**/*.tsx", ".next/types/**/*.ts"],
        "exclude": ["node_modules"]
    },    
]


tsconfig:
    compilerOptions:
    lib:
    - dom
    - dom.iterable
    - esnext
    allowJs: true
    skipLibCheck: true
    strict: true
    noEmit: true
    esModuleInterop: true
    module: esnext
    moduleResolution: bundler
    resolveJsonModule: true
    isolatedModules: true
    jsx: preserve
    incremental: true
    plugins:
    - name: next
    paths:
        "@/*":
        - "./src/*"
    include:
    - next-env.d.ts
    - "**/*.ts"
    - "**/*.tsx"
    - ".next/types/**/*.ts"
    exclude:
    - node_modules


    "src": {
        "app": {
            "page.tsx": {
                "title": "Home",
                "description": "This is the home page"
            }
        },
        "components": {
            "header.tsx": {
                "links": ""
            },
            "footer.tsx": {
                "links": ""
            }
        }
    },