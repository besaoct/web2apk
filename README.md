# website_to_Apk
Convert Your Website to Apk using Android Studio 

-------------------
INSTALLATION:
-------------------

A. Create and open a folder and then open it with terminal. 

B. Write this command and hit enter :

```
git clone https://github.com/blackipie/web2apk.git
```

![Screenshot (52)](https://user-images.githubusercontent.com/82350431/147269182-cf1c883c-a457-4c23-8ae6-a464cccdbaad.png)


C. Open your Android Studio and Click "Open an Existing Project"

![Screenshot (49)](https://user-images.githubusercontent.com/82350431/147267399-36de7366-90e4-4574-9421-3282a85097a5.png)

D. Select the folder you opened with terminal.

![Screenshot (50)](https://user-images.githubusercontent.com/82350431/147268957-34f53a84-c598-49a1-93a3-0e88ad44cafd.png)

-----------------------
ADD YOUR WEBSITE URL:
-----------------------

A. Goto " app > java > com.app.apk > MainActivity "

B. Find the line "mywebView.loadUrl("https://google.com");"

![Screenshot (48)](https://user-images.githubusercontent.com/82350431/147269740-cc37ffb0-4d6f-4b2b-ac09-6a8603cd939e.png)

C. Replace both the "https://google.com" with your website url.


----------------------------
CHANGE APP NAME :
----------------------------

A. Goto " app > res > values > strings.xml "

![Screenshot (44)](https://user-images.githubusercontent.com/82350431/147270409-45d841db-0679-42c4-91fb-92d7fc3a3a6e.png)

B. Change "Apk" to your App name

----------------------
CREATE YOUR APP LOGO:
----------------------

A. Goto " app > res > drawable "

B. Right click on "drawable" > new > Image Asset

C. Click on "Image Asset"

![Screenshot (45)](https://user-images.githubusercontent.com/82350431/147270823-b4c2b160-70db-43b2-b7b6-77c40fc15920.png)

D. Now You can change your app logo's foreground and background layer

![Screenshot (46)](https://user-images.githubusercontent.com/82350431/147271040-ce24d90c-ad24-4730-8a21-617a52971d18.png)

E. After that click on Next and Finish it.


_____________________________________

NOW RUN IT

_____________________________________


-------------------------------------------
HOW TO CREATE APK FILE OR RELEASE YOUR APP
-------------------------------------------

A. Do the same as shown in image below and Click on "Generate signed bundle/Apk.."

![Screenshot (53)](https://user-images.githubusercontent.com/82350431/147273663-042f2f6d-4498-4d0a-a781-16d5cddd38b2.png)

B. Select "Apk" and Click Next

![Screenshot (54)](https://user-images.githubusercontent.com/82350431/147273744-4f350ab3-d445-47f5-9d00-74b0ed2d7c93.png)

C. Click Create New

![Screenshot (55)](https://user-images.githubusercontent.com/82350431/147273928-6fcf8e93-2cb9-41c0-a312-9701c5cec17a.png)

D. Now Key Store Path: (the path where you cloned website_to_Apk )

E. Select "website_to_Apk" and Write Filename as "Apk" and then click "OK"

![Screenshot (56)](https://user-images.githubusercontent.com/82350431/147274762-e82b37f3-3fa1-4b36-b42f-ab0f2d98e35c.png)

D. Enter your own password and fill in the blanks and then Click "OK"

![Screenshot (57)](https://user-images.githubusercontent.com/82350431/147274885-6fbe8805-2c87-45ed-b1c2-ebebd9555bc8.png)

E. Click Next

![Screenshot (58)](https://user-images.githubusercontent.com/82350431/147275172-234320fa-d5a5-405a-9e03-d8a21779b5d0.png)

F. Select "release" , Check both the signature versions and then click "Finish"

![Screenshot (59)](https://user-images.githubusercontent.com/82350431/147275400-d1e389a8-e4fe-4eee-b168-ecb136e90f40.png)

G. Click on "locate" as shown in the image

![Screenshot (60)](https://user-images.githubusercontent.com/82350431/147275609-84b8bf1a-bb1d-4f07-b805-ffb08eda93a8.png)

H. Open "release folder"

![Screenshot (61)](https://user-images.githubusercontent.com/82350431/147275744-313b1773-a5fd-41aa-8056-938ec4fc39a8.png)

I. There is an Apk file named "app_release" 

![Screenshot (62)](https://user-images.githubusercontent.com/82350431/147275941-6f43d5ad-837f-4e8f-a2e5-b59b855baaeb.png)

_____________________________________

1. You have successfully generated Apk.

2. Send the Apk file named "app_release" to your device and install it.
_____________________________________

-------------------------------------
Done ! ☺ 
-------------------------------------


