## Tasks Accomplished

- [x] **Task 1:** Functional and Simple UI and UX using react.
- [x] **Task 2:** Added Importing CSV functionality.
- [x] **Task 3:** Basic backend setup using Nodejs and MongoDB.
- [x] **Task 4:** Real Time sheet updating functionality.

## Technology Stack

Collab Sheet leverages the following technologies:

- **[React Js](https://react.dev):** We chose React.js for its component-based architecture and efficient rendering, making it ideal for building dynamic and scalable user interfaces.
- **[Node Js](https://nodejs.org/en):** We chose Node.js for its ability to handle asynchronous operations and build fast, scalable server-side applications using JavaScript.
- **[MongoDB](https://www.mongodb.com):** MongoDB’s versatility in supporting multiple programming languages makes it a strong choice for a wide range of applications. It allows for seamless integration with different tech stacks, which is likely why your team opted for it.
- **Libraries:** Handsontable, math.js

## Key Features

- **External Integration:** The users have the feature of uploading an CSV file to the software which will be converted to spread sheet. There are other features like sorting and filtering to reduce the work time and give users a enhanced experience of this.
- **Simple State Management:** React’s useState hook simplifies the management of the grid’s state. You can easily track changes to each cell and update the grid dynamically as users interact with it.

## Local Setup Instructions 
Follow these steps to run the project locally

### MacOS/Windows

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Sunny-pro22/Collab-Sheet.git 
   cd Collab-Sheet 
   ```
2. **Install all the dependency**
   ```bash
   cd server
   npm i
   cd ../vite-project
   npm i
   ```
3. Create a `.env` file in the `server` directory with the following content: 
   ```bash
   ATLAS_URL=your_mongodb_atlas_url 
   SECRET=your_secret_key
   ```
4. **Run Server**
   ```bash
   cd server # change directory to server
   node app.js
   ```
5. **Run Frontend**
   ```bash
   # In another terminal/command promt
   cd vite-project
   npm run dev
   ```
