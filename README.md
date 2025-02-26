# YouTubeScriptDownloader App

In this multi-screen application, we integrate our existing Python code with a Kivy mobile application. We then modify the Kivy app to include the implementation of user interface (UI) that allows users to input the YouTube video ID and trigger the script download. The users must log in or register before they can access the YouTube transcript downloader. 

# Integrating Our Python Code with Kivy, We:

1. Create Input Fields: Let the user input the YouTube video ID.
2. Add Button: Add a button that will trigger the download of the transcript.
3. Display Output: Show success or error messages in the app.
  
  
  # Key Components
    
  # 1. User Authentification:
    Users need to log in if they already have an account. Otherwise, Users have to register using the Sign Up button in order to access the app.
  
  <img width="1127" alt="image" src="https://github.com/user-attachments/assets/dfd4fbb4-05ab-4fc1-9dcc-16ed0cf79b77" />
      
  <img width="1125" alt="image" src="https://github.com/user-attachments/assets/eb395e82-d610-4876-9625-a24be1ed21b2" />

    
    
  # 2. Input for YouTube Video ID: 
    Users can enter the video ID, which is necessary to download the transcript. If the link or the video ID is not correct, Users will receive an error message directing them how to correct the link.
<img width="1127" alt="image" src="https://github.com/user-attachments/assets/9028d5b8-a942-4874-bda5-86db8953dfd7" />

# Opps, an Error Occurred!
<img width="1127" alt="image" src="https://github.com/user-attachments/assets/493921f2-6c61-4d7a-92c6-a7d081a702f8" />


    
  # 3. Download Button: 
    After correcting the link or video ID and clicking this button triggers the appropriate function, which fetches and cleans the transcript.

  <img width="1127" alt="image" src="https://github.com/user-attachments/assets/23df4f4d-e307-404f-a4e7-b440cd9672f8" />
  
    
  # 4. Result Label: 
    Displays whether the download was successful or if an error occurred.
  
  <img width="1127" alt="image" src="https://github.com/user-attachments/assets/2adb8ca3-70b3-4c37-bb6c-526ec03c46a7" />
