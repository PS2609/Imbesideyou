# Flow ChatApp 

![Flow ChatApp Cover](https://www.notion.so/DOCUMENTATION-102b31e92a79808a830bc39636d95024?pvs=4#7563d4fb4eaa4eb1a93d585afa41edc5)

Flow Chat is a full-stack chat application based on Next.js featuring real-time messaging and responsive design. It requires a low latency architecture so that the recipients may get the messages from the sender, instantly.
## Features

1. **Real-Time Messaging**  
   - Users can send and receive messages instantly within a chat room.
     
2. **Push Notifications**  
   - Notifications are delivered based on active sessions, ensuring users only receive notifications on active devices.

3. **Light and Dark Mode**  
   - Users can switch between light and dark themes to suit their visual preferences.
     
4. **Single & Group Chat feature** 
   - It allows you to interact with single and multiple users in real-time.
     
5. **User Authentication with Clerk**  
   - Secure authentication for users is managed through **Clerk**, allowing for easy login with email, Google, or other supported providers.

6. **Message Read Receipts**  
   - Users can see when their messages have been read by the recipient, improving communication transparency.

7. **Reactions**  
   - Quick emoji-based reactions (like thumbs up or heart) enable lightweight interaction with messages.
     
8. **Threaded Replies**  
   - Users can reply directly to specific messages within threads, creating structured sub-conversations. This is ideal for group chats where multiple discussions happen simultaneously.
     
9. **Media Sharing**  
    - Users can upload and share images, videos, or files directly within the chat, supporting more dynamic and interactive conversations.
      
10. **Chatbot**  
   - Chatbot to communicate with users via a chat interface.         



## How to Get Started

1. **Clone the Repository.**
   
2. **Install Dependencies:**
   ```bash
   npm install
   ```
## ⚙️ Configuration

1. **Set Up Environment Variables:**
    - Create a `.env.local` file in the project root.
      
    - Add your Clerk API keys:
    ```bash
    CLERK_PUBLISHABLE_KEY=<your-publishable-key>
    CLERK_SECRET_KEY=<your-secret-key>
    ```
    - Add your Stream Chat project credentials:
      
    ```bash
    STREAM_API_KEY=<your-stream-api-key>
    STREAM_APP_ID=<your-stream-app-id>
    STREAM_TOKEN_SECRET=<your-stream-token-secret>
    ```

## 🚀 Running the Project

1. **Start the Development Server:**

    In the terminal, run:
    ```bash
    npm run dev
    ```

2. **Access the Application:** 

    Open your browser and navigate to:
    ```bash
    http://localhost:3000
    ```

    Your development environment should now be up and running!

## 💻 Tech Stack I Used & Why?

### **Frontend:**
- **Next.js:** Provides a framework for server-rendered React applications, enhancing performance and SEO, with built-in routing and API routes.
- **React:** A popular JavaScript library for building dynamic and interactive user interfaces with a component-based architecture.
- **Tailwind CSS:** Speeds up styling with pre-defined CSS classes, eliminating the need for writing custom CSS.
- **TypeScript:** Improves code readability and reliability by catching errors during development, making the codebase maintainable.

### **Backend:**
- **Next.js API Routes:** Allows easy creation of server-side endpoints, improving performance and security by handling logic on the server.
- **Getstream SDK:** Provides a full-featured solution for building chat applications, saving time on implementing complex chat features.
- **Clerk:** Simplifies user authentication, reducing development time and ensuring secure sign-in functionality.

### **Chatbot:**
- **DialoGPT-medium:** A pre-trained language model used for generating human-like responses, making interactions more natural and engaging.



## Solution Architecture


## Demo

https://github.com/aritroCoder/Snaptos/assets/95216822/aef48482-29df-4ceb-9dd1-dfdb8b6608ea

## Authors
This project has been made for Imbesideyou by Priyanshi Sharma from IIT Patna. 

