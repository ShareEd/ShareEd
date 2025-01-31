# ShareEd: Resource Sharing Platform

ShareEd is a web application designed to enable users to share and access educational resources. It supports user registration, file uploads and downloads, posting of doubts, and interactive discussions with the users or the AI chatbot. The platform is built with a focus on collaboration among learners.

![image](https://github.com/user-attachments/assets/2294195f-a6fc-4a8d-9cab-63b36e48c361)


## Features

- **User Authentication:** Secure user sign-up and login using Firebase Authentication.

![image](https://github.com/user-attachments/assets/6cd982bd-35eb-4d4c-aaa1-dfa6cd278ead)

- **Resource Sharing:** Upload and download educational resources.
- **Doubt Posting:** Users can post educational doubts and receive answers.
- **Interactive Discussion:** Users can participate in discussions by posting answers to doubts.
- **AI Chatbot**: An AI-powered chatbot for instant doubt clarification, built using Botpress.
![image](https://github.com/user-attachments/assets/2ba3b64e-9a61-4ff9-aa52-256e9f28e507)
- **Curriculum Guidelines**: Organize educational content by various subjects ensuring that users have easy access to subject-specific resources.
![image](https://github.com/user-attachments/assets/64444910-e0b1-486f-942c-a8cbf2fcc687)


- **Responsive Design:** Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Firebase Firestore (Database), Firebase Authentication, Firebase Storage
- **Firebase SDK:** Firestore, Auth, Storage
- **AI Integration**: Botpress for AI chatbot

## Getting Started

### Prerequisites

- Install a development environment (e.g., Visual Studio Code, Node.js, or any other suitable tool).
- Firebase account for project setup.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ShareEd.git
   cd ShareEd
   ```
2. Set up Firebase in your project by creating a Firebase project.
3. Add Firebase configuration details to your JavaScript files where `firebaseConfig` is defined.

## Project Structure

```
ShareEd_project/
├── static/
│   ├── css/
│   │   ├── login.css
│   │   └── styles.css
│   ├── images/
│   │   ├── gmail.png
│   │   ├── icon2.png
│   │   ├── linkedin.png
│   │   ├── s3.png
│   │   └── shared3.jpg
│   └── js/
│   │   ├── curriculum.js
│   │   ├── doubt.js
│   │   ├── firebaseauth.js
│   │   ├── homepage.js
│   │   ├── script.js
│   │   ├── upload.js
│   │   └── view.js
├── template/
│   ├── curriculum.html
│   ├── doubts.html
│   ├── home.html
│   ├── index.html
│   ├── upload.html
│   ├── user.html
│   └── view.html
└── README.md
```

## Key Functionalities

### User Authentication

- Secure sign-up and sign-in functionalities using Firebase Authentication.
- Password validation and user session handling.

### Resource Sharing

- Upload educational files to Firebase Storage.
- Save file metadata in Firestore.

### Doubt Posting and Discussion

- Post doubts with titles and descriptions.
- Display list of doubts with answers.
- Users can submit answers to posted doubts.

![image](https://github.com/user-attachments/assets/2a8b8132-18db-4e3b-8d15-17ff8937501e)

### AI Chatbot for Doubt Clarification

- Integrated AI-powered chatbot using Botpress.
- Provides instant responses to user queries for educational assistance.

### Curriculum Guidelines
- The platform organizes learning resources by subject areas such as Mathematics, Science, and Engineering.
- Admins have the ability to add, update, or remove links to subject-specific curriculum guidelines and materials, ensuring that users always have access to relevant study resources.

### Responsive UI

- Clean and user-friendly design for easy navigation.

## Firebase Setup

1. Go to [Firebase Console](https://console.firebase.google.com/).
2. Create a project and set up Firestore, Firebase Storage, and Authentication.
3. Replace the Firebase configuration object in your JavaScript files with your Firebase project credentials.

## Usage

1. Start the web application by opening `index.html` in your browser.
2. Register or sign in to your account.
3. Upload resources or post and answer doubts.
4. Use the AI chatbot for instant doubt clarification.
5. Explore and download available resources.

![image](https://github.com/user-attachments/assets/aee750ad-6480-4812-acd2-718c4cbb3949)
![image](https://github.com/user-attachments/assets/8c8cd483-a90a-4f5d-926a-7438c45b516b)


## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push to your fork and create a pull request.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions, suggestions, or feedback, feel free to reach out us at:

[Rishika Yadav](https://www.linkedin.com/in/rishika-yadav-8538872a0/)
and
[Prachi Singh](https://www.linkedin.com/in/prachi-singh-5a751428a/)
