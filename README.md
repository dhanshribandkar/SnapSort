# SnapSort - Digital Time Capsule

SnapSort is a **web-based digital time capsule** that allows users to store their **images, audio, and video files** securely. Users can also **lock folders** and access them only when a **scheduled due date** is reached, making it perfect for preserving memories or important files for the future.

---

## Features

- Upload and store images, audio, and video files.
- Create multiple folders to organize content.
- Lock folders and unlock them only after a scheduled due date.
- Secure and private storage for personal data.
- Web-based interface, easy to use.

---

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Others:** body-parser, bcrypt, etc.

---

## Project Structure
```
SnapSort/
│
├── index.html
├── css.html
├── server.js
├── package.json
├── package-lock.json
├── pages/
│   ├── login.html
│   ├── signup.html
│   └── capsule.html
└── node_modules/ (ignored in GitHub)
```

---

## How to Run Locally

1. Clone the repository:

```bash
git clone <https://github.com/dhanshribandkar/SnapSort>
```

Install dependencies:
```
npm install
```

Start the server:
```
node server.js
```


Open your browser and go to:
```
http://localhost:5000
```

Make sure MongoDB is running and configured in your project.

## Future Plans

- Add user authentication and email verification.
- Add notifications for locked folders nearing their due date.
- Implement a more interactive UI for better user experience.

## License

This project is currently under development and not yet licensed.


