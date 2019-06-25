# ed-aid
#### ed-Aid is a platform for learners to share experience, knowledge and documents among others and help them to improve skills and knowledge. With the help of Ed-Aid users can search for and have access to various academic and industrial materials for knowledge. 

-	Ed-Aid provides facility of sharing content with community
-	Users can post advertisement regarding their projects / documents.
-	If user find something related to their field and interesting they can mark it as favorite.
-	User can chat with author of the post / advertisement.
-	Users can report post as inappropriate.

### NOTE :
#### Required steps:
- Create new project on Firebase
- Enable Authentication -> Sign-In method -> Google
- Storage -> set rules to 
```
service firebase.storage {
  match /b/{bucket}/o {
    match /{allPaths=**} {
      allow read, write: if request.auth != null;
    }
  }
}

```

- Download `GoogleService-info.plist` file from project setting.
- Put file in `supported file` folder
- Build and Run the project

### Screen Shots:

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1YuuXMAjTk8ffh7eHuU-urd2LVR1NHicC" width="250">
  <img src="https://drive.google.com/uc?export=view&id=1Djb6I3IFydD0EWg_nRlwZJjZkgp2uf_W" width="250">
  <img src="https://drive.google.com/uc?export=view&id=1PaUQrOOW6yuZKNXyDZW8HWYhNyVO7kEa" width="250">
</p>
<br>
<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1y2pyjBqNQbHzo2E9NTLNQNAW1dcmJ9fy" width="250">
  <img src="https://drive.google.com/uc?export=view&id=1yjTWYwLgUvTqj9Bw875w8KOH7Sgo8Cek" width="250">
  <img src="https://drive.google.com/uc?export=view&id=1_LgWJkz_M8id7tJpSAEHAjhbuyE5gokl" width="250">
</p>
