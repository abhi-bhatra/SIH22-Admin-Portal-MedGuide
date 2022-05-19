# Admin Portal for MedGuide
<img width="943" alt="image" src="https://user-images.githubusercontent.com/63901956/169243365-5bcfe3bf-a448-4021-89ab-d211b4dfd818.png">

## About MedGuide 
MedGuide is an information portal to search for general availability of Beds, Oxygen Beds, ICUs in the hospital. Patients can gain better insights on availability in the hospitals before visiting one. 

## About Admin Portal
<img width="947" alt="image" src="https://user-images.githubusercontent.com/63901956/169243864-fe8486af-2a07-4246-bad9-156be1b723b6.png">

Admin Portal is designed for the hospitals. Hospital's admin can login into the portal and update the number of beds, oxygen beds, ICUs available at any point of time in the hospital.

## Internal Working of Admin Portal
- The data saved by Hospital Admin will be saved by Web Portal to the **firebase realtime database**. 
- This data then fetched from **firebase realtime database** for further processing.
- This data is provided to client app/web portal, where user can know about the availability.
