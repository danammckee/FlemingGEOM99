# **Fleming College: [GEOM99 Web GIS Development](https://danammckee.github.io/FlemingGEOM99/home.html)**

## **[Week 1 Tasks](https://danammckee.github.io/FlemingGEOM99/Week1/index.html)**

## **Task 1: Review of Google Maps Platform Blogs**

* Google Maps data and how to use it to keep up to date [LINK](https://cloud.google.com/blog/products/maps-platform/9-things-know-about-googles-maps-data-beyond-map)
* Resources avaliable to get the most out of the Google Maps platform [LINK](https://cloud.google.com/blog/products/maps-platform/how-get-started-google-maps-platform-get-support-and-have-your-questions-answered)
* GeoJSON and how to use it to display on the Google Maps Platform [LINK](https://cloud.google.com/blog/products/maps-platform/quick-map-layer-visualizations-geojson-and-georss)

## **Task 2: Google MyMaps**

* Visualize data and create a custom map using Google MyMaps.
* [Shark Spotters Google MyMaps](https://danammckee.github.io/FlemingGEOM99/Week1/MyMaps/sharkspotting.html)

## **Task 3: Google Maps As a Development Platform**

Showcase the three pillars of Google Maps as a platform: Maps, Routes and Places. 

### **JavaScript API (HTML Interactive Map)**

* Create the Overview (hello world) example. 
* Location set to Drumheller, AB
* Check out the location [HERE](https://danammckee.github.io/FlemingGEOM99/Week1/googlemapsjson/hellodrumheller.html)
  * https://danammckee.github.io/FlemingGEOM99/Week1/googlemapsjson/hellodrumheller.htmll 

### **Directions API (JSON Return)**

* Follow instructions for directions and form a URL to provide route directions in JSON
* Directions from Royal Tyrrell Museum to Hoodoos Trail 
* Get Directions: [HERE](https://danammckee.github.io/FlemingGEOM99/Week1/googlemapsjson/directionsAPI.html)
  * https://maps.googleapis.com/maps/api/directions/json?origin=Royal+Tyrrell+Museum&destination=Hoodoos+Trail&key=AIzaSyBLd0Hl7PVa0PnyZVIlLrAUipqZ6npRSYA


### **Places API (JSON Return)**

* Get a Places details URL working to return a JSON response
* Royal Tyrrell Museum 
* Check out information about Royal Tyrrell Museum [HERE](https://danammckee.github.io/FlemingGEOM99/Week1/googlemapsjson/placesAPI.html)
  * https://maps.googleapis.com/maps/api/place/details/json?place_id=ChIJy38C1IcSc1MR1Bh0FOdJtRI&fields=name,address_component,formatted_address,rating,formatted_phone_number,opening_hours,website,photo,reviews&key=AIzaSyBLd0Hl7PVa0PnyZVIlLrAUipqZ6npRSYA 

```{
   "html_attributions" : [],
   "result" : {
      "address_components" : [
         {
            "long_name" : "1500",
            "short_name" : "1500",
            "types" : [ "street_number" ]
         },
         {
            "long_name" : "North Dinosaur Trail",
            "short_name" : "N Dinosaur Trail",
            "types" : [ "route" ]
         },
         {
            "long_name" : "Drumheller",
            "short_name" : "Drumheller",
            "types" : [ "locality", "political" ]
         },
         {
            "long_name" : "Division No. 5",
            "short_name" : "Division No. 5",
            "types" : [ "administrative_area_level_2", "political" ]
         },
         {
            "long_name" : "Alberta",
            "short_name" : "AB",
            "types" : [ "administrative_area_level_1", "political" ]
         },
         {
            "long_name" : "Canada",
            "short_name" : "CA",
            "types" : [ "country", "political" ]
         },
         {
            "long_name" : "T0J 0Y0",
            "short_name" : "T0J 0Y0",
            "types" : [ "postal_code" ]
         }
      ],
      "formatted_address" : "1500 N Dinosaur Trail, Drumheller, AB T0J 0Y0, Canada",
      "formatted_phone_number" : "(403) 823-7707",
      "name" : "Royal Tyrrell Museum",
      "photos" : [
         {
            "height" : 4016,
            "html_attributions" : [
               "\u003ca href=\"https://maps.google.com/maps/contrib/108802277305302044660\"\u003eCedo Kucinar\u003c/a\u003e"
            ],
            "photo_reference" : "ATtYBwLwS_bTRqxSFGsr1Cpy693XMkuX8ZJ_AhiEE6_ugxj0xlbepmUWflh-rx3bxJOSDAi8_fuFTGsuzrKpoA9fgshdP-zCJKgzSm7l6cHqeLorU5RUUK2a1BO2ZmdAsksZJ6ElcMgcONwFFgYbyxRbI0YGVdjMn9BOSvjUODMWM1f4DGH8",
            "width" : 6016
         },
         {
            "height" : 3024,
            "html_attributions" : [
               "\u003ca href=\"https://maps.google.com/maps/contrib/115888296183994785938\"\u003ejasmine kaur\u003c/a\u003e"
            ],
            "photo_reference" : "ATtYBwKA0YKIB556v0IxCMOWrQnKddsbALAhcddrMUouxkjE8ozcmIKVZ_Jo4r3PiixeElhsfM0_3wfhjdPd93vyibkXgIBvtUyHQ8LEck2kJ9C_QuJ-_GBdoaDbpwH5LgHM1g3lBmlCIOCtixSVSTTuAq4QVq2ouyNqZ1oD2ckEDiZDN7Sy",
            "width" : 4032
         },
         {
            "height" : 3024,
            "html_attributions" : [
               "\u003ca href=\"https://maps.google.com/maps/contrib/115656375746643120905\"\u003eRyan Pan\u003c/a\u003e"
            ],
            "photo_reference" : "ATtYBwLQWC8eNv1emu7lXutEMbQvNYkjjP0D0_pDml-Iso9RX7wWWpBX8WMBPNlvMZO1G62aEj6NGm0THR0JytejE5SyrxHySTMbQxmOaEXq4kgsCM77jwN7UHM-QCeqGUrY0hSXQpOzu3uEAwLSe8oeNHGxv6bE8M-jUELNfO6VG1nX5hCg",
            "width" : 4032
         },
         {
            "height" : 3036,
            "html_attributions" : [
               "\u003ca href=\"https://maps.google.com/maps/contrib/105861164264264882505\"\u003eThis is the way\u003c/a\u003e"
            ],
            "photo_reference" : "ATtYBwI1_POPc_G1gF16RvQsanVY7nW0y6psNO5Rwq4JQLmnyTpxY_7TF0XkMlsWN5XoYyD2JrrfVuMP-JkLGfDnDXyjtz5pYpjM8hVwJOqePHgA_l6sFntk_JzFJGtcGiqDWSrAHMNuV_b96Ipzl6DzJIXYfGNrK2cY2agYskY8WRX1HNTz",
            "width" : 4048
         },
         {
            "height" : 3024,
            "html_attributions" : [
               "\u003ca href=\"https://maps.google.com/maps/contrib/106625713036576420552\"\u003eDawn Marie Ferron\u003c/a\u003e"
            ],
            "photo_reference" : "ATtYBwKm5hdR1717tiL23dBSFrPxSTja72lvE2eEwoB8uAZhgi0IbTHx_z6SaMTMEfV1ULM6LgINzZ4lZcAIUq5fJBm5v-_ONvrbhJCmalhd1aC1iic3-qtBKJVxDFJL-687NmDr5NwOetjr2W8kNwl-Jx15UjiIYUlsxs5OA9HwiRPg9zkO",
            "width" : 4032
         },
         {
            "height" : 2704,
            "html_attributions" : [
               "\u003ca href=\"https://maps.google.com/maps/contrib/113653562621481803047\"\u003eMichael Buse\u003c/a\u003e"
            ],
            "photo_reference" : "ATtYBwIzhoj1CWNhwEKWCcbZkZ0pCD09vSRJ8Op2FhyThP0N3PpPN-x6vfWxtt9DbhnJTxC4NWLxdRff-NOMyzdCDGFozp6vdenOh6Em_18k-WQ0Lyj92kx5PU8OCTFtfKF65OGhPFchRDqEWflM59aIOeEj3t7ytyqDNLGRZTP_bdz_Wnzt",
            "width" : 4056
         },
         {
            "height" : 3024,
            "html_attributions" : [
               "\u003ca href=\"https://maps.google.com/maps/contrib/106985536188676913768\"\u003eEdgar Tolentino\u003c/a\u003e"
            ],
            "photo_reference" : "ATtYBwLOhDtdxl48SRS6ZMhSDzhtPO5Lksez_WXzCdRKVxvjyUGdlDhWmuJjal0zapxVU2HS8kg8HR75SzfXGHf28gcBkrwGguQ4XrmHoh2qBs1kFet_q8fcxgryd4oGxUzH05OoL1lMt3jL5DYCXrQKPNqQW4JzOv2B2-X0is7_mMq9SSKt",
            "width" : 4032
         },
         {
            "height" : 2736,
            "html_attributions" : [
               "\u003ca href=\"https://maps.google.com/maps/contrib/108557583571127584602\"\u003eKevin Luo\u003c/a\u003e"
            ],
            "photo_reference" : "ATtYBwI8JY0ro3xRPQRlgHScO1fLrMiBb6DAc8Ylw66QwVBkBZymMlmmPTgoRk5r5pz_GlDBEIluz6kW_bsQFAxwmj0z52wXCJMLu7vvKdPpIbLvXofjYYqkg6iwQPogCEmWI2IX7pjVyAGjB9h_VWB1X4uIQr9D80ZxqnBpPpj29NV9PE38",
            "width" : 3648
         },
         {
            "height" : 3024,
            "html_attributions" : [
               "\u003ca href=\"https://maps.google.com/maps/contrib/117007487627079671931\"\u003eJaspreet Saini\u003c/a\u003e"
            ],
            "photo_reference" : "ATtYBwKpklvazVCMGsPXvy5nTcBizZyYCB7RTEbCJht-r-oFVTM9nDEYCqc32uB8isdm8VYyw0ZUcmuLBvgn4TEJ3uxAdPmCk0CjHNFvqh4hHjn1DobWvtoVPpNVJqvS1vcaMcI_VnmF7kc60hmz7WYYlRdOI2vLcVIeVwYUI_Mm2LuDNjAy",
            "width" : 4032
         },
         {
            "height" : 3024,
            "html_attributions" : [
               "\u003ca href=\"https://maps.google.com/maps/contrib/102864017938487972953\"\u003eImran Muhammad\u003c/a\u003e"
            ],
            "photo_reference" : "ATtYBwJlG4HyAGc8T3GdduMY1awtPndiSGGNwOpN5fZwkzcPUK_SfiaPwrO2L2V8q8kqTl6JjIbOK9jz5SkrsKGmSsCyYj9EdNVLG94dpG4ECQBhxwHCTY-rxP_fnoLnChtBhqP-F0i36KpyKBzOxJXbf28VZtjlqGd9o1w5GxFPymxzxVl1",
            "width" : 4032
         }
      ],
      "rating" : 4.7,
      "reviews" : [
         {
            "author_name" : "The Lego Show",
            "author_url" : "https://www.google.com/maps/contrib/113393170918335497735/reviews",
            "language" : "en",
            "profile_photo_url" : "https://lh3.googleusercontent.com/a-/AOh14GhN9pK5gtK907A_P9GIL-FTA508Kkj9lBwC8Jgw=s128-c0x00000000-cc-rp-mo-ba2",
            "rating" : 5,
            "relative_time_description" : "2 months ago",
            "text" : "It was awesome! For a dinosaur lover like me it felt like Jurassic Park coming to life. The displays went in the timeline through the eras ending with the dinosaur era. The skeletons looked very realistic and correct and helped me learn a lot! I loved and it was a very great experience, it is in Canada and I live in Colorado so I had to take a big road trip but it was so worth it for a trip to this amazing museum, I put some pictures below of some of the dinosaur skeletons. The trip took 7 days and was pretty fun for me and will probably be very fun for you!",
            "time" : 1606088421
         },
         {
            "author_name" : "Kevin Dare",
            "author_url" : "https://www.google.com/maps/contrib/109478256298591545250/reviews",
            "language" : "en",
            "profile_photo_url" : "https://lh4.googleusercontent.com/-tjIlkJBB6Mo/AAAAAAAAAAI/AAAAAAAAAAA/AMZuucnA_F2gbLF8rsKQchHR9EnwEa-iWw/s128-c0x00000000-cc-rp-mo/photo.jpg",
            "rating" : 5,
            "relative_time_description" : "4 months ago",
            "text" : "This museum leaves no stone unturned, literally....so many exhibits to look at...plus the walking trail beside the museum...it has it all. After you are done, they have a cafeteria where you can relax and grab a bite to eat. Well worth the trip out there.👍👍👍",
            "time" : 1602008227
         },
         {
            "author_name" : "Noha Salem",
            "author_url" : "https://www.google.com/maps/contrib/113665713994146605954/reviews",
            "language" : "en",
            "profile_photo_url" : "https://lh3.googleusercontent.com/a-/AOh14GhjyHTIQUOp5xgOgvr-nd3v9-5SQlU7eyuakEfJvg=s128-c0x00000000-cc-rp-mo-ba3",
            "rating" : 1,
            "relative_time_description" : "5 months ago",
            "text" : "You have to book online in advance or you won't get in. They don't sell tickets there any more because of COVID",
            "time" : 1598571071
         },
         {
            "author_name" : "Gabby Rivera (Gabtron27)",
            "author_url" : "https://www.google.com/maps/contrib/108374563903794935771/reviews",
            "language" : "en",
            "profile_photo_url" : "https://lh3.googleusercontent.com/a-/AOh14GgwELA_pu7MXkYjGFYk3pypHzGTcw9K7C5CK5Le=s128-c0x00000000-cc-rp-mo",
            "rating" : 5,
            "relative_time_description" : "3 months ago",
            "text" : "Went into town for a trip and just had to go here! It was so amazing! Would definitely recommend. My friend and I got the last tickets at 3:30 and had pretty much the whole museum to ourselves! I can't wait to go back!",
            "time" : 1605580365
         },
         {
            "author_name" : "Susan Shaw",
            "author_url" : "https://www.google.com/maps/contrib/105208304177698685395/reviews",
            "language" : "en",
            "profile_photo_url" : "https://lh5.googleusercontent.com/-gOuFD3An5BU/AAAAAAAAAAI/AAAAAAAAAAA/AMZuucmuZUPsc7qRjgmOlBWsp9v_UWcs1Q/s128-c0x00000000-cc-rp-mo-ba3/photo.jpg",
            "rating" : 5,
            "relative_time_description" : "3 months ago",
            "text" : "Absolutely love the Royal Tyrrell. It was a free entry day and they had staggered entry, which was dealt with fabulously. The museum is packed to the rafters ( literally) with dinosaur bones. Separated into eras with information on the type of animals living in that era, it is breathtaking to look at and factual for those who want to know more.\nI also really like the section where you can watch the staff at work removing new found bones from the rock.\nOutside, you are slap bang in the middle of Hoodoo country. Go and explore, look for unique rocks - but remember, no taking samples home.",
            "time" : 1604937953
         }
      ],
      "website" : "http://www.tyrrellmuseum.com/"
   },
   "status" : "OK"
}
```

## **[Week 2 Tasks](https://danammckee.github.io/FlemingGEOM99/Week2/index.html)**

## **Task 1: Google Javascript API**

### **Tutorial 1 - Adding a Google Map**

* Add a simple Google map with a marker to a webpage
* [Royal Tyrrell Museum](https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/tutorial1.html)
  * https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/tutorial1.html

### **Tutorial 2 - Marker Clustering**

* Use marker clusters to diaplay a large number of markers on a map
* [Ontario Provincial Parks](https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/tutorial12.html)
  * https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/tutorial2.html

### **Tutorial 3 - Earthquakes: Basic Markers, Sized Circles, Heatmap**

* Visualize data on Google maps using various techniques. 
* Earthquakes
  * [Basic Markers](https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/tutorial3a.html)
    * https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/tutorial3a.html
  * [Sized Circles](https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/tutorial3b.html)
    * https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/tutorial3b.html
  * [Heatmap](https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/tutorial3c.html)
    * https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/tutorial3c.html

## **Task 2 - Create a Single HTML5 Page Using Google Map Technology**

* [Ski Hills of Brtish Columbia](https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/bcskihills.html)
  * https://danammckee.github.io/FlemingGEOM99/Week2/GMaps/bcskihills.html
  
## **[Week 3 Tasks](https://danammckee.github.io/FlemingGEOM99/Week3/index.html)**

## **Task 1: ArcGIS Courses**

### **Course 1 - ArcGIS Online Basics**

* Complete the [ArcGIS Online Basics course](https://www.esri.com/training/catalog/5d816c0255cf937306d2d3ef/arcgis-online-basics/)

![Certificate](https://danammckee.github.io/FlemingGEOM99/images/Cert1.JPG)

* [Certificate Link](https://www.esri.com/training/TrainingRecord/Certificate/damcke@flemingcollege.ca_Fleming/601b94051d7e0c1f497095a3/300)

### **Course 2 - Creating and Sharing GIS Content Using ArcGIS Online**

* Complete the [Creating and Sharing GIS Content Using ArcGIS Online course](https://www.esri.com/training/catalog/5d816c0255cf937306d2d3ef/arcgis-online-basics/)

![Certificate](https://danammckee.github.io/FlemingGEOM99/images/Cert2.JPG)
* [Certificate Link](https://www.esri.com/training/TrainingRecord/Certificate/damcke@flemingcollege.ca_Fleming/601f0b4581d6fb19c1d300b9/300)

## **Task 2: Map Viewer**
  
 * Map Viewer Beta [LINK](https://www.esri.com/arcgis-blog/products/arcgis-online/mapping/web-maps-and-map-viewer-beta/)
 * Map Viewer Beta May 2020 Update [LINK](https://www.esri.com/arcgis-blog/products/arcgis-online/mapping/try-out-the-new-map-viewer-beta/)
  * Map Viewer Beta Latest Update [LINK](https://www.esri.com/arcgis-blog/products/arcgis-online/mapping/whats-new-in-map-viewer-beta-october-2020/)

## **Task 3: What's New in ArcGIS Online**

 * ArcGIS Online News [LINK](https://doc.arcgis.com/en/arcgis-online/reference/whats-new.htm)

## **Task 4: JSON and Importing Data into Webmaps**

 * [Stave Lake - ArcGIS Online WebMap](https://fleming.maps.arcgis.com/home/item.html?id=027a8446c84345fa99746d7971578ced)
 * [Stave Lake Legacy GeoJSON](https://danammckee.github.io/FlemingGEOM99/Week3/stavelake.html)
   
## **[Week 4 Tasks](https://danammckee.github.io/FlemingGEOM99/Week4/index.html)**

## **Task 1: ArcGIS Online Developers Website**

* [ArcGIS Developers Website]( https://developers.arcgis.com/)

## **Task 2 - Generate a Layer on the ArcGIS Online Developers Website**

* [Tree Collection WebMap](https://da9vbapdo7iu6xkf.maps.arcgis.com/home/item.html?id=1c793f0785a24ba89ad2e4d8bc69558b)
* [Tree Collection Feature Layer Item ID URL](https://da9vbapdo7iu6xkf.maps.arcgis.com/home/item.html?id=d919060f9acb484095eb1a048ef2d62c)
* [Tree Collection REST URL](https://services3.arcgis.com/sXzWIJPFn9VCHK8j/arcgis/rest/services/tree_collection/FeatureServer)

## **Task 3 - Introduction to ArcGIS Online REST and Token Security**
* Tokens and Rest URLS

## **Task 4 - JavaScript API Tutorials**

### **Tutorial 1 - Display a Map**
 * [Display a Map](https://danammckee.github.io/FlemingGEOM99/Week4/ArcGIS/APIandJavaScript/DisplayMap2.html)
 
### **Tutorial 2 - Display your Location**
 * [Display your Location](https://danammckee.github.io/FlemingGEOM99/Week4/ArcGIS/APIandJavaScript/DisplayLocation.html)
 
### **Tutorial 3 - Add a Feature**
 * [Add a Feature](https://danammckee.github.io/FlemingGEOM99/Week4/ArcGIS/APIandJavaScript/AddFeature.html)
 
### **Tutorial 4 - Exaggerated Earth**
 * [Exaggerated Earth](https://danammckee.github.io/FlemingGEOM99/Week4/ArcGIS/APIandJavaScript/ExaggeratedEarth.html)
 
### **Tutorial 5 - Valentine's Day**
   * [Love Around the World](https://danammckee.github.io/FlemingGEOM99/Week4/ArcGIS/APIandJavaScript/vday.html)
  * [Love - Saskatchewan, Canada](https://danammckee.github.io/FlemingGEOM99/Week4/ArcGIS/APIandJavaScript/valentinesday.html)





