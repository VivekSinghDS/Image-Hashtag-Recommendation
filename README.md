# Image-Hashtag-Recommendation
Web-scraped Instagram for getting enough metadata, and then found relatable hashtags

Steps to follow : 
1. Clone this repo 
2. Install selenium 
3. Go to sample2.py
4. Enter your username and password in line 33 and 34 respectively 
5. Change the tag name from "architecture" to something you want in line 137 
6. Configure your chromedriver by changing appropriate paths
7. Refer to the file structure as shown in the screenshot file. 
8. Run the model_prepare file then

File Structure 

<img width="439" alt="Screenshot 2021-10-22 at 1 17 29 PM" src="https://user-images.githubusercontent.com/92970332/138421163-3145b341-9bad-4f86-aef7-188c9e38e78a.png">

Model Used : 
MobileNetV2

Output : 

![img1](https://user-images.githubusercontent.com/92970332/138421363-ee60640f-a74f-44ec-b01a-ddd0b9312fba.jpeg)
Recommended Hashtags : 
#nature, #autumn, #naturephotography, #travel, #naturelovers, #travelphotography, #landscape, #landscapephotography, #sky, #naturelover

![img6](https://user-images.githubusercontent.com/92970332/138421641-7e9d64ef-4672-46fd-819d-e35201dfbaff.jpeg)

Recommended Hashtags : 
#wedding, #like, #weddingphotography, #love, #weddingdress, #fashion, #beautiful, #bride, #summer, #likeforlikes

Drawback : 
Metadata is required to process new forms of images

References : https://github.com/AlecMorgan/Automatic-Image-Tagger
