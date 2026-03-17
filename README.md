# ⚡ payload-nextjs-starter - Simple CMS and Website Setup

[![Download payload-nextjs-starter](https://img.shields.io/badge/Download-payload--nextjs--starter-brightgreen)](https://github.com/ameurDev-ops/payload-nextjs-starter)

---

## 📋 What is payload-nextjs-starter?

This is a starter template that combines two tools: Payload CMS and Next.js. It helps set up a website and a content system quickly. The system uses PostgreSQL for storing data, Tailwind CSS for design, and TypeScript for solid code. You can manage content like text and images easily. This setup works well for simple websites or blogs with a professional look.

---

## 💻 System Requirements

Before you begin, make sure your computer meets these needs:

- Operating System: Windows 10 or newer  
- Storage: At least 2 GB free space  
- Internet connection: Required for downloads and updates  
- RAM: Minimum 4 GB recommended  
- Software installed:  
  - Node.js (version 14 or above)  
  - PostgreSQL database (version 12 or above)  
  - A web browser (Chrome, Edge, Firefox, or similar)

---

## 🚀 Getting Started

### Step 1: Download the files

Start by visiting the download page where you can get the full project. Use this big button:

[![Download payload-nextjs-starter](https://img.shields.io/badge/Download-payload--nextjs--starter-blue)](https://github.com/ameurDev-ops/payload-nextjs-starter)

Click the button or this link to open the GitHub page. From there, you will find the files you need.

### Step 2: Download and install Node.js

Node.js is software that lets your computer run parts of this project. To install it:  

- Go to https://nodejs.org/en/download/  
- Download the Windows Installer for the latest LTS version  
- Run the installer and follow the instructions on screen  
- Restart your computer if requested

### Step 3: Install PostgreSQL

PostgreSQL is the database. It stores content for your site. To install:  

- Visit https://www.postgresql.org/download/windows/  
- Download the Windows installer  
- Follow the steps and use default settings unless you know what you want to change  
- Take note of the username and password you set  

---

## 🛠️ Setting Up the Project

### Step 1: Extract the downloaded files

If you downloaded a ZIP file from GitHub:  

- Find the ZIP file on your computer (usually in the Downloads folder)  
- Right-click the ZIP file  
- Select "Extract All..."  
- Choose a folder where you want the project files  
- Click "Extract"

### Step 2: Open Command Prompt

You will use Command Prompt to run the setup:  

- Press Windows key + R  
- Type `cmd` and press Enter  
- A black window will open  

### Step 3: Navigate to the project folder

In the Command Prompt window:  

- Type `cd ` (include a space after cd)  
- Drag the folder where you extracted the project into the Command Prompt window to fill in the path  
- Press Enter  

Example:

```
cd C:\Users\YourName\Downloads\payload-nextjs-starter
```

### Step 4: Install Project Dependencies

Run this command to install all needed software pieces inside the project:

```
npm install
```

Wait for it to finish. This may take a few minutes.

### Step 5: Set up PostgreSQL database

- Open the PostgreSQL app or pgAdmin tool  
- Create a new database for the project (you can name it `payloaddb`)  
- Remember the database name, username, and password for the next step

### Step 6: Configure environment settings

Your project needs to know how to connect to the database. Find the file `.env.example` in the project folder. Copy it and rename the copy to `.env`. Open `.env` with Notepad and fill in these lines:

```
DATABASE_URL=postgres://yourusername:yourpassword@localhost:5432/payloaddb
PAYLOAD_SECRET=your-unique-secret
```

Replace `yourusername`, `yourpassword`, and `payloaddb` with your database details. For `PAYLOAD_SECRET`, you can enter any random text.

Save and close the file.

---

## ▶️ Running the Project

Back in your Command Prompt:

- Make sure you are still in the project folder  
- Run this command to start the application:  

```
npm run dev
```

You will see messages showing the app is starting.

---

## 🌐 Accessing the Website and Admin Panel

- Open your web browser  
- Go to http://localhost:3000/ to see your website  
- To manage content, go to http://localhost:3000/admin  

---

## ⚙️ Common Tasks

### Updating the project

To get new features or fixes:  

- Open Command Prompt  
- Navigate to the project folder  
- Run:

```
git pull
npm install
```

### Stopping the app

- In Command Prompt, press `Ctrl + C`  
- Confirm to stop the process

---

## 🧰 Useful Tips

- Keep Node.js and PostgreSQL updated to avoid issues  
- Always back up your database before major changes  
- Use the admin URL to add or change your content easily  
- For design changes, edit Tailwind CSS files in the project folder  

---

## 🔗 Download Again

If you need to download the project again, visit:

[https://github.com/ameurDev-ops/payload-nextjs-starter](https://github.com/ameurDev-ops/payload-nextjs-starter)