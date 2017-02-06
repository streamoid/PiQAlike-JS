
**PiQAlike-JS**
===============

Using ***PiQAlike-JS*** sdk fashion websites can add visual search feature seamlessly into their website
 
   **What is Visual search in fashion:**
 
Any fashion apparel/accessory that inspires an end-user, for example, that perfect summer dress he/she saw in a magazine or those shoes that the woman was wearing at the coffee shop, User can just take a photo and find products visually similar to those in your 'fashion website' using PiQAlike-JS sdk

  **Integration**
  

 1) Adding script in **head** tag


    (function(i,s,o,g,r,t,k,a,m){
     i['PiqitObject']=r;i['PiqitGa']=t;i['PiqitToken'] = k;i[r]=i[r]||function() {
     (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
     m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
     })(window, document, 'script', 'LOADER-URL', 'PQT', 'GOOGLEANALYTICS-ID', 'CLIENT TOKEN');

  **Important Note** : If you are already using some other Streamoid's JS sdk in your website, you need not add the above script in **head ** tag twice

 2) Add the below line of code(div) in your html source code wherever you want to see the visual search button. A search button will be automatically added in your website. 
    
     <div class="streamoid_sdk streamoid-camera-button" data-token="CLIENT TOKEN" data-service="camera" data-function="initialize"></div>

Please contact streamoid.support@streamoid.com to get your LOADER-URL, CLIENT TOKEN, GA TRACKER-ID

**User Flow**

The below screenshots depicts user flow for Visual search feature
 

 - visual search button

![Visual Search button](https://d30wzon9g8gc0d.cloudfront.net/ef1c3dbe-ec41-11e6-ba31-0649f9b7563d.jpg)
     
 - Uploading an image
 
![Uploading an image](https://d30wzon9g8gc0d.cloudfront.net/f9aa4910-ec41-11e6-9da8-0649f9b7563d.jpg)

 - Selecting a region of interest
 
 ![Selecting a region of interest](https://d30wzon9g8gc0d.cloudfront.net/1e40a170-ec42-11e6-ba31-0649f9b7563d.jpg)

 - Results screen
 
 ![Results screen](https://d30wzon9g8gc0d.cloudfront.net/317635fc-ec42-11e6-ba31-0649f9b7563d.jpg)

