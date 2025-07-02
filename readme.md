# 🚀 How to Run This Project


📁 Step 1: Download Required Files
Download and place the following folders and files in a single parent directory:
- client/
- server/
- Database/ (contains .json data files)
- package.json (main project-level)

  
💻 Step 2: Open in Visual Studio Code
Open the parent project folder in VS Code, then open an integrated terminal.


📦 Step 3: Install Dependencies
Run the following commands in the terminal to install dependencies:
cd client
npm install
cd ..

cd server
npm install
cd ..

npm install


 Step 4: Run the Application
Start the project using:
npm start
Note: At this stage, images and data may not display because the MongoDB database hasn't been populated yet.


🍃 Step 5: Import Data into MongoDB
- Open MongoDB Compass.
- Run the project once to automatically create the schema and database.
- Locate the foodDelivery database, which contains multiple collections.
- For each collection:
- Click "Add Data" → "Import JSON"
- Import the relevant .json files from your Database/ folder.
- Make sure the collection names match exactly.

- 
🔁 Step 6: Restart the Server
To reflect the newly added data:
# Stop the server
Ctrl + C

# Restart the server
npm start


🔐 Step 7: Login Credentials
You can log in as a restaurant using the following format:
- Email: restaurantFirstname@gmail.com
Example: foodie@gmail.com
- Password: same as the restaurant First name
Example: foodie
To use the Admin or User dashboard, register a new account and log in accordingly.






