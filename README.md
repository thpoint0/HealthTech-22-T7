# Mellowdy - Music with Intention

Research has shown that listening to music can benefit people of all ages in dealing with mental health issues. Mellowdy aims to combine self care routine with therapeutic music to provide relief in a consistent and sustainable manner.  

<img width="1920" alt="Cover" src="https://user-images.githubusercontent.com/65660274/173217156-313b98c9-98b4-4c17-9a8c-8a0a3f9edeef.png">

### How to run

Clone the repo and navigate to index.html, then start debugging (F5). 

**Recommendation**: Launch Google Chrome devtools and "Inspect element". View the app in iPhone 6/7/8 or iPhone 6/7/8 Plus for best results!

![image](https://user-images.githubusercontent.com/65660274/173230945-cabafce0-2616-40b0-a602-88e0e1a5215f.png)

### Proposed technical solution

**Phase 1** - React PWA with SQL database + Music API like Deezer API to fetch music belonging to specific genre. Login info and customization selection will be saved of the end users. 

**Phase 2** - Additional module for certified music therapist's to sign up and upload their work. NoSQL database will be implemented to save the audio details, like metadata and link to audio file. Audio file storage will be on the cloud. 

**Phase 3** - NoSQL database will capture further details, such as most popular tracks, when the app is used the most and least, etc.  

### Mock ups

![image](https://user-images.githubusercontent.com/65660274/173217457-a24eb07e-75cc-463a-95bf-48ec33ab0787.png)
![image](https://user-images.githubusercontent.com/65660274/173217474-af86c5b4-490b-4dcf-b269-93e6e35c9cca.png)
![image](https://user-images.githubusercontent.com/65660274/173217493-b918f0ae-332b-42fa-aade-db0fb8fd26bc.png)
![image](https://user-images.githubusercontent.com/65660274/173217504-e172f847-c844-4d23-a5df-39592a9df9ac.png)
![image](https://user-images.githubusercontent.com/65660274/173217515-99c811ad-7dee-4cc9-9344-680f3926be12.png)


### Protoype
This prototype is built as a Progressive Web app, which will allow users on all types of devices to access it easily. It uses basic HTML combined with Bootstrap 5 for CSS. To support the PWA, a service worker is registered along with a manifest.json file. 

*Lighthouse report on Google Chrome Devtools*
<br>
![Lighthousereport](https://user-images.githubusercontent.com/65660274/173217090-6503144a-2d9c-4941-98b0-f6f72b8d9308.JPG) 

*Prototype running locally*
![techdemolatest](https://user-images.githubusercontent.com/65660274/173217036-f2bc3de4-17c0-45ca-ac00-ec24525f282d.gif) 

