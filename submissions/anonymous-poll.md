Here’s your Hacktoberfest Challenge submission template populated with the relevant details for your QuickBlox real-time anonymous polling system project:

---

# QuickBlox Hacktoberfest Challenge Submission: Real-time Anonymous Polling System

GitHub handle: **abhirajadhikary06**

## Project Overview

**Project Title**: Real-time Anonymous Polling System with QuickBlox and Flask

**Description**:  
This project is a real-time anonymous polling system where users can participate in anonymous polls via a chat interface. It leverages QuickBlox for real-time communication and Flask for the backend. Users can submit votes and see the results dynamically updated in the chat. It is a lightweight, user-friendly app designed to provide a seamless polling experience in real-time.

Key features include:
- Anonymous voting without revealing user identity.
- Real-time results displayed dynamically.
- Simple UI for easy interaction.
- QuickBlox integration for efficient communication between users.

## Technical Details

**Tech Stack**:  
- **Front-End**: HTML, CSS, JavaScript  
- **Back-End**: Python (Flask)  
- **Real-Time Communication**: QuickBlox JavaScript SDK  
- **Deployment**: (Optional: Netlify/Vercel/Local Server)

**QuickBlox Integration**:  
- QuickBlox is used to handle real-time communication between users in the chatroom.
- QuickBlox's JavaScript SDK is integrated to allow users to anonymously join chat rooms, cast their votes, and broadcast real-time results to all participants.
- The backend receives and processes user votes, then sends updated results back to all participants using QuickBlox messaging.

## Submission Links

**Project Repository**:  
[Real-time Anonymous Polling System GitHub Repository](https://github.com/abhirajadhikary06/polling-app.git)

**Project Deployment Link (Optional)**:  
(If deployed, you can add the link here)

**Demo Video/Images**:  
## Image
![image](https://github.com/user-attachments/assets/2658ea80-f361-4e8a-991f-0f5371f39af3)

## Video

https://github.com/user-attachments/assets/49882ba3-eb88-4470-bfa4-edda85b55c48

## Additional Information

**Challenges Faced**:  
- **CORS Issues**: Initially, while testing the application locally, I encountered Cross-Origin Resource Sharing (CORS) issues when connecting the front-end with the Flask backend. I overcame this by using the `Flask-CORS` library to allow for seamless communication.
- **Real-time Updates**: Handling real-time updates was tricky at first, but QuickBlox's JavaScript SDK made it simpler to manage the synchronization between votes being cast and updating the results in real-time.
- **UI Enhancements**: Creating a sleek and modern user interface took some effort, as I wanted the app to be visually appealing while keeping it simple to use. By utilizing more dynamic styles and ensuring responsive design, I achieved the desired look.

**Future Improvements**:  
- **User Authentication**: Adding optional user authentication to allow for tracking user participation without compromising anonymity.
- **Multiple Polls**: Enhancing the app to support multiple ongoing polls within the same chat room or across different chat rooms.
- **Poll Customization**: Allowing admins to customize the poll questions and options dynamically from the UI.

**Blog Post (Optional)**:  
[Building a Real-time Anonymous Polling System with QuickBlox and Flask](https://dev.to/abhirajadhikary06/building-a-real-time-anonymous-polling-system-with-quickblox-and-flask-7gj)
