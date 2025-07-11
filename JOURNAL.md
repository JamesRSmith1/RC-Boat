---
title: "RC Boat"
author: "James Smith"
description: "Custom 3D Printed RC Boat"
Started on: "2025-07-07"
---

**Day 1 - July 7th Inspiration and Research**
Total time - 2 Hours
After taking some inspiration from a friend creating their own RC Fan Boat, I wanted to dip my toes into the RC world through making my own. I figured that an RC Boat would be a relatively easier, yet still challenging, project to start working with RC and making my own things. In the future, I will hope to make a custom 5" FPV Drone as I enjoy flying my current TinyWhoop.

I used to have a fast RC Speedboat and would take it out to the lake to drive around whenever I could. I would like to try and bring this boat as I used to and try it out. 

After looking at my friends fan boat, I wanted to try and challenge myself with a water prop boat. I began by looking online at videos and forums of the design of a boat. I watched many videos of boat builds and design. [This](https://sites.google.com/cherrycreekschools.org/digitaldesign/project-examples/rc-boat) site of another creators build process helped me form an idea of the physics behind a good RC boat with CoM. It also helped me in deciding my hull shape to be a displacement/deep V single hull. I decided this hull shape as it would be easiest to design and because it is similar to the boat I used to have. 

To propel the boat, I decided I will integrate a water jet/boat intake into the hull. This allows for a more compact boat and allows the prop to be protected. I looked at various designs of water jets before picking one to design my boat around. With the general boat design in mind, I am ready to begin design.



**Day 2-3 - July 8-9 Picking Parts and Designing Hull**
Total Time - 8 Hours
Today, I began by choosing the components of my build.
[ELRS Reciever](https://www.amazon.com/BETAFPV-ExpressLRS-Compatible-Multirotors-Helicopters/dp/B09WHLJ2GN/ref=sr_1_2?crid=5175J2NAFMWD) - Could be used with my Radiomaster Pocket
[ESC](https://www.amazon.com/RC-Brushless-Electric-Controller-bullet/dp/B071GRSFBD/ref=asc_df_B071GRSFBD?mcid=f79a234e84eb3688957acc64e2d06233&hvocijid=6570016539828006300-B071GRSFBD-&hvexpln=73&tag=hyprod-20) - Good reviews, reccomended to me, has the specs I need
For me, the hardest part was picking the motor and battery. These 2 had to work together so picking them took some time. I wanted to minimize weight and maintain a slim boat. I decided a 3S lipo battery was unneccesary weight, so decided to use 2S. Runtime is not a huge factor for me, so I decided to pick a lower end mAh rating. I also wanted to keep the temperature low in the hull to prevent overheating. I spent a long time looking for light, low mAh 2S battery with an XT60 Connector to work with my ESC. I eventally managed to find [this battery](https://speedyfpv.com/products/turnigy-1000mah-2s-30c-lipo-battery-t1000-2s-30?variant=44984415813846). I also spent a long time looking for a small diameter motor that worked with my battery and ESC. I wanted to have a motor with low kV to keep the temperature as low as I could. After a long time searching, I eventually found this [2280kV 2040 Brushless Inrunner Motor](https://www.amazon.com/KingVal-Replacement-Waterproof-Brushless-Compatible/dp/B0B2NTLT6N/ref=sr_1_12?crid=16FK2QVT5FX4V). With this in mind, I created a basic layout of the components in the hull.

I struggled greatly trying to make the cap for the boat. Keeping water out is crucial. I started with trying to use an o ring seal.

<img width="57" height="100" alt="image" src="https://github.com/user-attachments/assets/5c3cdbb2-fb3f-491f-8ba0-39f64738f796" /> 

After finding out that I'd have to waste $12 on 10 feet seal and $7 on 2 inserts, I decided not to go for that. My next idea was to create a slide on cap.

<img width="200" height="34" alt="image" src="https://github.com/user-attachments/assets/6799f50b-30fc-4fb5-b08a-3a46169e3cc3" /> 

I did not really trust this and couldn't find a way to secure this. Finally I tried to go back to my orignial idea, instead using a TPU gasket a few layers tall going around the top. I then added screw holes into the plastic and added a tab in the front to keep the cap secured. <img width="200" height="100" alt="image" src="https://github.com/user-attachments/assets/5d01c780-f572-465e-b93d-00c03a0bf0e5" /><img width="200" height="100" alt="image" src="https://github.com/user-attachments/assets/463a2d3e-29f2-4381-b07b-04924925b7f7" />


I integrated the water jet with a hole on the bottom and back, and adding a place where I can add my motor and servo. 

<img width="110" height="280" alt="image" src="https://github.com/user-attachments/assets/1107f757-ab89-499d-85d8-f81eb7b11158" />

The servo will lay horizontal and attach to the jet outlet via a paperclip.
I made many mistakes and changes throughout the day, making the design process take a long time.



**Day 3-4 - July 10-11 Design Finishing Touches
Time Spent: 4 hours
Throughout these past couple days, I spent lots of time to finalize the layout for my components and modeled them on the CAD to try and get a favorable center of mass while keeping the wiring in mind. This image from the ESC page shows the wiring between each of the components:

<img width="437" height="123" alt="image" src="https://github.com/user-attachments/assets/d8b01e08-2439-47d0-accf-81dfbc42c682" />
<img width="200" height="270" alt="image" src="https://github.com/user-attachments/assets/b3d81625-1abd-4eb7-bd46-6368ca18e9b4" />

I modeled the servo mount off of the motor mount above the jet. To keep these components in place and allow for easier printing on my 3D Printer, I created small compartments with chamfers to remove the need for supports. I found some double sided VHB Tape to keep them in place. I decided to use a 3mm prop shaft and eventually found a coupling for the motor and prop shaft. 

<img width="302" height="753" alt="image" src="https://github.com/user-attachments/assets/48260f74-4479-4665-876b-6a5ff0b78e13" />


Finially, I found a set of screws on amazon that had each type that I needed and a JST Connector converter to charge my battery. I tidied my list of components/parts into a BOM on google sheets.
<img width="491" height="278" alt="image" src="https://github.com/user-attachments/assets/47c40af2-6959-47a4-acf5-f2c76b9d4b52" />

Now that the design of the boat is done, I will ship it to hackclub and hope for an approval to make it!
