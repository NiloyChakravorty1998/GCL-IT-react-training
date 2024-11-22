# GCL-IT-react-training
- Codebase for React training for Dev team in 2024.
# How to run the project ?
Prerequisites :
- node v16.20.2
- npm v8.19.4

Once installed, check versions using:
- run `node -v` on cmd/bash.
- run `npm -v` on cmd/bash.

Also run:
- `npm install -g npx` to install npx globally.

## Run the backend Json Server:
- `cd GCL-IT-react-training/ReactJs-Ecommerce-app/Ecommerce-ReactJS-frontend/backend` to move inside the `backend` folder.
- `json-server db.json -p 5000` to run the backend server in `PORT 5000`.


## Run the backend Express JS project:
### This Project has database connectivity. If you dont have a database setup locally, you can use the other project.
- `cd GCL-IT-react-training/ReactJs-Ecommerce-app/auth-service-nodejs` to move inside the `auth-service-nodejs` folder.
- `npm install` to download the packages and generate node_modules.
- `npm start` to start the project locally on `PORT 8000`.

### Run without database connectivity:
- `cd GCL-IT-react-training/ReactJs-Ecommerce-app/auth-app` to move inside the `auth-app` folder.
- `npm install` to download the packages and generate node_modules.
- `npm start` to start the project locally on `PORT 8000`.

## Run the frontend react project:
- `cd GCL-IT-react-training/ReactJs-Ecommerce-app/Ecommerce-ReactJS-frontend` to move inside the client folder.
- `npm install` to download the packages and generate node_modules.
- `npm start` to start the project locally on `PORT 3000`.