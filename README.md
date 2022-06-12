# CapstoneProject-C22-PS211
ACREG

<b>Steps: </b>
1. Download zip file (image classification.zip)
2. Extract it
3. Open the extracted file in Android Studio
4. Change firebase connectivity to your personal firebase account (check steps below before go to step 5)
5. To change model, you can easily change the .tflite model in ML folder, also change the labels.txt in assets folder.
6. Enjoy.




<b>To change firebase account:  </b>
1. Open your firebase account and create project
2. Insert your SHA-1 and project package to SHA-1 certificate fingerprint (you can check it in your android studio terminal by running command 'gradlew signigreport'
3. Create the authentication
4. Download google-service.json in firebase account settings
5. Then replace the existing google-service.json file with your downloaded json file.
