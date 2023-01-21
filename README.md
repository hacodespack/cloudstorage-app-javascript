# Cloudstorage App Javascript

**Update:** Upload any type of file

**No folder structure required**

**Storage Ruls**
```
rules_version = '2';
service firebase.storage {
 match /b/{bucket}/o {
     match /{allPaths=**} {
     		allow write;
    		allow read;
    }
   }
  }
  ```
