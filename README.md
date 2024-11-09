# SocialAi

**An AI Powered Social media manager website to reduce dependency on managers by 50%.**

**Project Status**: active

**Last Updated**: Nov 2024

## Overview

The SocialAi is a web application powered by artificial intelligence, designed to supercharge your social media management. It offers several features to make your social media management tasks easier and more efficient.

### Features

- **Personalized Social Media Chatbot**: Dedicated to streamlining your social media management tasks.
- **Image Generation**: Create images from prompts and save them to your dashboard.
- **Seamless Posting to Twitter**: Easily post generated images to your Twitter account.
- **Caption Crafting**: AI-powered caption generation for images.
- **Paragraph Composition**: Create entire paragraphs of text for your social media posts.
- **TrendSetter**: Curates the latest trends and provides AI-generated captions and images tailored to your preferences.

## Installation

Follow these steps to set up and run the SocialAi locally:

1. Install the dependencies:

   ```bash
   npm install
   ```
2. Run the server:   
    ```
   cd server
   npm start
    ```
3. Run the python backend server
    ```
    cd server/flask-app
    python app.py
    ```

4. Start the app
    ```
     cd client
     npm run dev
    ```

please make sure to add .env files in both client and server directory
in client directory
.env file should have 
  ```
   VITE_SECRET=OpenAI Key
   VITE_POST='AryShare Key
```



.env file in server directory should have  

    
        OPENAI_API_KEY=OpenAPI KEY
        MONGODB_URL=MongoDB URL
        GOOGLE_SEARCH_API=google search api
        CLOUDINARY_CLOUD_NAME=CLOUDINARY_CLOUD_NAME
        CLOUDINARY_API_KEY=CLOUDINARY_API_KEY
        CLOUDINARY_API_SECRET=CLOUDINARY_API_SECRET









![Screenshot 2024-11-09 205301](https://github.com/user-attachments/assets/3a691475-af75-41f7-bedc-95387847651e)
![Screenshot 2024-11-09 205348](https://github.com/user-attachments/assets/796ae3a9-d939-40a2-b380-60821b989f0b)
![Screenshot 2024-11-09 205407](https://github.com/user-attachments/assets/8f291268-dbe1-40f0-96a2-9e350adebedb)
![Screenshot 2024-11-09 205439](https://github.com/user-attachments/assets/793c8b55-d9b1-4d4d-acf2-985d50ab69cf)
![Screenshot 2024-11-09 205529](https://github.com/user-attachments/assets/3360c4c2-1cf9-4036-bc28-0c4677703b9c)
![Screenshot 2024-11-09 205610](https://github.com/user-attachments/assets/be585034-aaaa-425a-af0b-581414853099)

