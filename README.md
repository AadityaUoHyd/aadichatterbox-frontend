# AadiChatterBox (fullstack project) Spring boot 3, Angular 18, Bootstrap, PostgreSQL, Keycloak (2024) (Frontend)

Angular frontend of the aadichatterbox

[Spring boot Backend](https://github.com/AadityaUoHyd/aadichatterbox-backend)

### Key Features:
- 💬 Real-time messaging
- 👥 Conversations management
- 📁 File sharing (images, videos, documents)
- 🔐 Authentication and Authorization (Role management) with Keycloak (OAuth2)


## Usage
### Prerequisites
- [NodeJS 20.11 LTS](https://nodejs.org/dist/v20.11.1/node-v20.11.1.pkg)
- [Angular CLI v18](https://www.npmjs.com/package/@angular/cli)
- IDE ([VSCode](https://code.visualstudio.com/download), [IntelliJ](https://www.jetbrains.com/idea/download/))

### Fetch dependencies
``npm install``

### Launch dev server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### Build
Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

# Production
During deployment, don't forget to change environment file variables. e.g. keycloak.url, API_URL, FRONTEND_URL.
Also change value of target. i.e. 'BACKEND_URL', which reside in "proxy.conf.json" file.
