# How to Demo

To correctly run the application, you'll need to start both the **frontend** and the **backend**. Follow these steps:

1. Open **two terminals**.
2. Run the following commands (one per terminal):
   - Frontend: `npm run dev`
   - Backend: `npm run devStart`

Once both processes are running, check the frontend terminal. It will provide a link to the application at `http://localhost:5173/`. You can open it by **Ctrl + Left Clicking** on the link, which will launch the application's frontend in your browser.

### Using the Application

When you open the application, you'll see the home page. The following buttons are functional at the moment:
- **Stream Now**
- **Watch**

Both of these buttons will take you to the login page. Since you're likely not registered yet, click on the **Register** button to go to the registration page.

Alternatively, you can:
- Click the **Google icon** button or the **Google pop-up notification** to automatically register/login via Google.
- Click the **Home** or **StreamShare** logo buttons to return to the home page.

### Registration Process

On the **Register** page, fill in your credentials. Make sure all fields are complete; any missing fields will be highlighted for you to correct. Once everything is filled out, click the **Create Account** button to register your account.

You can also:
- Return to the home page by clicking the **Home** or **StreamShare** logo buttons.
- Go back to the login page by clicking the **Login** or **Watch** buttons.

### Login and Admin Dashboard

After logging in, you’ll be redirected to the **user dashboard**, which is still under development. However, the **admin dashboard** is functional, but you can't register for an admin account directly.

Instead, use these admin credentials to log in:
- **Email**: exampleadmin@gmail.com
- **Password**: adminadmin

Once logged in as an admin, you'll be redirected to the admin dashboard at `http://localhost:5173/admin-dashboard`. There, you'll see a list of uploaded videos.

#### Admin Actions:
- **Remove Videos**: Hover over any video thumbnail to reveal a **Remove** button. Click it to delete the selected video from the database and the webpage.
- **Upload Content**: Scroll down to find the **Upload Content** button. Click it to open a pop-up where you can:
  - Enter the **Title** of the video.
  - Upload a **file** from your computer.
  Once everything is filled out, click **Upload**. After some buffering (due to file transfer), the content list will update and the pop-up will close.

- **Logout**: Clicking the **Logout** button will log you out and return you to the login page.

Other buttons like **Watch**, **Home**, or **StreamShare** will redirect you to their respective pages.

### Error Handling

If any errors occur, a small explanation and the error code will be displayed. If there are multiple fields to fill out and some are incomplete, the missing fields will be visually indicated.
