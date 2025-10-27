In this project, I used Google Maps to enable location selection on the map. I saved the name and coordinates of the marked location to a local SQL Lite database using the Room library. Using RxJava, I separated the database save operations from the UIThread and made them asynchronous. This prevented the application from crashing during long-running operations.

<img width="361" height="760" alt="image" src="https://github.com/user-attachments/assets/61f286bd-c43c-464f-8cc0-0650767fd936" />
<img width="365" height="768" alt="image" src="https://github.com/user-attachments/assets/5fc7ddd5-62d1-40ff-91ad-cfac070a28ec" />

https://www.youtube.com/watch?v=AP8QDCqHLZw

In order for the application to work properly, you must add the API KEY you received from Google Cloud to the relevant place in the Android Manifest.

<img width="559" height="626" alt="image" src="https://github.com/user-attachments/assets/8228d4a3-61c0-42fc-bf7d-b2be6c114e9e" />



