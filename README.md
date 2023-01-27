
# Jenielva shepherd


             

















## Interface & Application Programming





Day 1.

10.2 Setup Dev Environment for ESP32 S2
Day 1 one was an online session. The teacher went over the slides and instructed the students to set up our  dev environment for the esp32 s2 using the instructions from slide 13.

![image53](https://user-images.githubusercontent.com/123673728/215067667-a3782b02-21c3-4e0c-95d7-d5542983cc9e.png)




After setting up the environment everyone had to test out the environment using the instruction in slide 17.

![image12](https://user-images.githubusercontent.com/123673728/215067888-dd4aeeea-fcf8-4693-adc7-d4865b577328.png)



Note; i was unsuccessful in setting up my esp32 s2 environment ,so i could not do the test on day 1 of week 1.


Day 2 In lab session

With the help of one of my classmates I was able to set up my environment and do the test.

The first test was to create a Web Server (with websockets) using esp32 s2 in arduino.

How:

Step 1 was to connect a led to pin 15 of the  esp32 s2. And create a folder to save the code for the webserver. In this folder create another folder named data (the html index will be saved here.

Step 2 Install spiffs(if you don’t have it already) and the needed libraries in the Arduino IDE.

Step 3 Open a new Arduino ide sketch and paste the code

   









The second test was to create a web server with multiple sliders to control LED brightness.

How:

Step 1 was to connect the leds to the  esp32 s2.

Step 2 Install spiffs(if you don’t have it already) and the needed libraries in the Arduino IDE.

Step 3 create a folder to organize your files
![image30](https://user-images.githubusercontent.com/123673728/215068142-da1ba903-8ce3-4fce-b7ba-2d2925ab1971.png)

          

Arduino sketch that handles the web server;

index.html: to define the content of the web page;

sytle.css: to style the web page;

script.js: to program the behavior of the web page—handle what happens when you move the slider, send, receive and interpret the messages received via WebSocket protocol.

Step 4 copy the codes from https://randomnerdtutorials.com/esp32-web-server-websocket-sliders/

Step 5 connect the esp32 s2 , upload the code and open the html file.

 


































In this session we were introduced to mqtt lens ( A chrome plugin). The class was instructed to download the Mqtt extension and then connect to the mqttwebserver test.mosquitto.org.

After the lesson i used the link provided in the slide and went on w3school.com to learn more about HTML, Css and javascript.(i haven't learned everything yet)

We were also instructed to create a mockup of the chataplication we wanted to create and to create an html file with div and wire up the js code.


![image50](https://user-images.githubusercontent.com/123673728/215068249-6ba4a740-093c-4fbe-9bba-7b1792fe0e0b.png)










Day 2 inlab session

In the lab session we were instructed to continue working on our web chat application. I managed to create a web interface but I could not connect to the mqtt server.

After some time everyone changed because test.mosquitto.org was giving problems.

I still was able to connect though and decided to skip that and work on the styling for my webchat.

This what the chat looked like:
![image117](https://user-images.githubusercontent.com/123673728/215068298-96089d74-82b3-4856-b5a5-fec79ca62631.png)




This was styled using the css tutorial on w3schools




In this session we went over how far we were with the webchat application and had to share our scenes. I still was able to connect to the mqtt server now but was not able to send message. I kept getting an error in line 1 of my html.


I tried putting the js code and my styling (css)in a different file but I still kept getting the same error

I finally discovered why I could not send messages. I made a few mistakes in the div class for the button.


                                                                                                                        

So after I finally got the code to work , I added more. I created another app.js file and added the new javascript there. With this javascript I was able to see who entered the chat and see the messages sent in the chat.


![image43](https://user-images.githubusercontent.com/123673728/215068471-b1971144-d387-4256-9b09-8bc300ae8f97.png)



I also set up my Node Js environment. I had to do this twice because I didn't wait for everything to download the first time and shut down my terminal window.

So not everything was installed
                                                                                                                        
                                                                                                                        
                                                                                                                        
                                                                                                                        
# 3D Printing
















![download](https://user-images.githubusercontent.com/123673728/215069029-c6f2eb93-a9e1-48e6-90b6-afb8ef973eee.png)



















## 7.1 What is 3d printing?
3D printing is the act of adding layers and layers of filament (thermoplastic feedstock for fused deposition modeling 3D printers) to create a solid object using a 3d printer. 3D printing is an additive process because you are adding layers to create an object.

## 7.2 type of filament?
Filament is the thermoplastic feedstock for deposition modeling 3d printers. There are many different types of filament but in the lab i will be working with the PLA (polylactic acid filament ) and the ABS( acrylonitrile butadiene styrene filament).

![image74](https://user-images.githubusercontent.com/123673728/215068609-d27939c4-c205-4be5-861b-6814d744ecfb.png)


Although both filaments are thermoplastic, The PLA is organic , stronger and stiffer than the ABS but the PLA has a big disadvantage because it does not have very good heat resistant properties because of this PLA is more of a hobbyist material. ABS on the other hand is weaker and less rigid than than the PLA  but it's also tougher and lighter than the PLA. That is why ABS is the preferred filament when making prototypes.

## 7.3 printers
There are two printers in the lab, the anycubic 4 max pro and the anycubic predator(deltabot).


The anycubic 4 max pro has an enclosed printing space with a large build volume to enhance printing quality. It is also out of box and there is no need to assemble. It is also safe for children because it has an optional auto power off feature. There is also a sensor that turns off the machine when it runs out of filament.

![image15](https://user-images.githubusercontent.com/123673728/215068647-07e74419-d1be-4d23-a0a6-6e20e615f8e7.png)

The anycubic predator is a bit more for advanced 3d printing. It uses delta bot ( 3 robotic hands attached to the printhead to deposit material. This is the printer that I will be using in this bootcamp.
![image38](https://user-images.githubusercontent.com/123673728/215068695-e516b189-30a0-4a71-bde8-0f8d2bcf805c.png)



## 7.4 printing software Cura 5.0.0.
For the boot camp i will be using Cura 5.0.0. I prefer to use this version because 1. It is the latest version and 2. Its is easier to use because of it has different profiles with preset parameters( this was not available in the older versions.)

I downloaded Cura from this link :https://www.windowsinside.com/software/ultimaker-cura/download this version can be used on a laptop with 32 bit and 64 bit.

![download](https://user-images.githubusercontent.com/123673728/215069029-c6f2eb93-a9e1-48e6-90b6-afb8ef973eee.png)



## 7.5 Basic PLA parameters
There are some basic parameters you should/ pay attention to when 3D printing. What you need to pay attention to is the : Quality, speed and temperature, filament, fill , support and machine.

Quality: there are 3 important things to pay attention to by quality. The layer height(the height that each printed layer will have), shell thickness(the thickens of the other shell of what you are printing) and enable retraction(retraction has to be enabled or else the filament will leak when the nozzle is moving from point a to point b)
Speed and temperature: the3 important things to pay attention here to are the: print speed mm/%(the speed at which the machine prints),printing temp(the temp at which the filament will become liquid), bed temperature( the bed that will be used to print also need to be hot(so the temp of the plate)).
Filament: here there are two things to pay attention too. 1. The diameter: this depends completely on the size of the filament you are using and nozzle size for example the PLA filament is 1.75 mm. So for the the diameter i will put 1.75 mm. 2.  The second thing to pay attention too is the flow:
Fill : Here you need to pay attention 1. the bottom/ top thickness: this like the shell thickness 2.full density:  this is to determine how solid you want your object to be. The higher the density the more solid your object will be .
Also the higher the density the longer it will take to print.

Support: here you pay attention to support type: this has to be enabled so your 3D print will be supported or else it will collapse. Platform adh type: this is so the machine print a parameter around your 3D before it start on your design so the filament can start running.
Machine: pay attention to the nozzle size.

Some basic diameters for PLA:(change to suit your needs)


![Screenshot (1)](https://user-images.githubusercontent.com/123673728/215069325-07bbfdb8-7082-47da-be4b-3ee12cabd5b1.png)


## 7.6 Setting up Cura and Using it.
After installing Cura I needed to set it up so I could use it. This was easy because as stated in 7.4 This version of cura already has a lot of presets.

First thing you need to do after installing cura is adding a printer. This is done by going to settings, the add printer ,then add a non network printer and then selecting the printer you will be using. I am using anycubic predator so i had to scroll down to anycubic and selected anycubic predator.

settings:
![image101](https://user-images.githubusercontent.com/123673728/215069429-31aebd63-9c59-4e46-b3bc-73defbb84ff9.png)

![image52](https://user-images.githubusercontent.com/123673728/215069444-ad3352a7-b47e-4f63-82a8-336e680ebdc8.png)


Printer:
![image81](https://user-images.githubusercontent.com/123673728/215069496-75843bf5-4f1c-4240-8c6a-77e7d6a025ff.png)




Press on add a non-networked printer:
![image78](https://user-images.githubusercontent.com/123673728/215069518-037d34b0-2f63-4ddf-8faa-c3bea4ffa67e.png)


Select printer you will be using:

![image65](https://user-images.githubusercontent.com/123673728/215069546-fb1966a6-e9b2-4941-adea-d0812f9737ae.png)



## 7.6.1 checking printers
After adding a printer you can go back to check and see if its has been added by going back to setting and hovering over  printer. The printer that you have added should show up there.

For example:
![image80](https://user-images.githubusercontent.com/123673728/215069743-501eb9dc-cc60-4c22-b297-df661a88ef56.png)



Since i only have anycubic added for now that is the only one that has shown up, but if you have more printers added they will show up.

##7.6.2 deleting printers
Now if you have a printer added but want to remove it. That is very simple to do.

Simply go back to setting then printers and select manage printers. In manage printer select the printer you want to delete and then click on the right options list and press remove.
![image80](https://user-images.githubusercontent.com/123673728/215069763-dc46025b-34f6-4168-a9db-e6f9765bceeb.png)

![image63](https://user-images.githubusercontent.com/123673728/215069813-4cb38fbf-3508-404c-82d1-22bf73cf8f78.png)


![image27](https://user-images.githubusercontent.com/123673728/215069834-952ad57d-affd-468b-9f95-1be645f2cb33.png)






## 7.6.3 checking the dimensions
After selecting the motor. If you want to check and see if the dimensions re right for your printer you go to manage printers , select the printer you want and then select mange settings. If the dimension are off then you can edit it to make it right.

![image27](https://user-images.githubusercontent.com/123673728/215069877-4874106e-f92b-4690-a1e8-66838ef76972.png)

![image107](https://user-images.githubusercontent.com/123673728/215069893-ece4ffd5-3032-4480-839d-918e96fa450e.png)




 It is important to know the size of your printer because if you put the wrong dimension in. when the machine will try to print the nozzle might come down too hard and brake dust ruining your machine.

## 7.6.4 checking parameters
In older versions of cura the parameters needed to be added manually but in the version i'm using there are profiles with preset parameters.

To see these parameters you have to click on the top right corner menu item and then you will see these parameters.
![image42](https://user-images.githubusercontent.com/123673728/215069941-0c9036fa-9b06-4a5c-a910-1dda5ee31aff.png)



Note : fill patern is the patern of the mesh stuff that is always ther when you print.

## 7.6.5 importing STL file to print.
To print you need and Stl file. An STL file is basically a file with you’re 3d design on it. The steps to adding an stl file to cura are 1.go to file on cura and click add file. 2 Select Stl file and click on open.



Note :when printing make sure your object always lays flat because if it doesnt lay flat, it will most likely collapse. Cura has an option in the side bar that lays the object flat for yoy when you select it.

Note 2:after tselctig lay flat in the side you will see a notification pop up on th botoom tight side of your screen showing you how much time your object will take to print


## 7.6.6 generating Gcode.
When you’re done adding an STL and setting up your parameters and dimensions, you need to save your object design. This is done by clicking save and saving the file with .gcode.

Gcode is…………..

After saving the file with .gcode you have to copy it to an sd card and then put that into the printer and your object will start printing.





# Freecad



![download](https://user-images.githubusercontent.com/123673728/215070095-e6e730fb-f642-4c37-a0da-715228dfc124.jpg)


























## What is freecad?
FreeCAD is a general-purpose parametric 3D computer-aided design modeler and a building information modeling software application with finite element method support.



## How to use freecad?
## 1.1 making objects with pockets.
The first thing to do is open freecad and select create  new.
![image22](https://user-images.githubusercontent.com/123673728/215070197-de7b3fa5-e8f8-4f8a-a8af-e348dceab6ce.png)



After selecting create  new this screen will appear.

![image24](https://user-images.githubusercontent.com/123673728/215070214-e70be6e6-49fa-44cc-9b5b-7c62808b28ed.png)



At the top of the screen you will start. Select on that an a whole list of options will appear.



You have to select part design. After selecting part design this screen will appear.

![image19](https://user-images.githubusercontent.com/123673728/215070316-58059390-08db-4160-8c16-452ce61d33fe.png)



When the screen appears you have to look for a sketch and select that.
![image19](https://user-images.githubusercontent.com/123673728/215070344-0f9ee5ee-ef59-4658-824f-e120b3b2cff6.png)



After selecting create sketch some things will appear in the combo view.

There you have to select the base planes you want to work on. (i always pick xy plane).


![image98](https://user-images.githubusercontent.com/123673728/215070402-e2155612-0e7e-40cd-befd-61fa92a75d93.png)


After selcting your base pane and selcting ok. This will appear.
![image109](https://user-images.githubusercontent.com/123673728/215070457-8d8c1bd1-8610-47d8-b048-e9712bbb7054.png)





You then have to select the shape you want to create.

![image88](https://user-images.githubusercontent.com/123673728/215070525-e9c603ee-43e5-41f2-a943-25c2d0f1fbbd.png)





After adding you shape you to combo view and select close.
![image10](https://user-images.githubusercontent.com/123673728/215070540-81494f6c-099e-4796-99f1-9d411d4d6236.png)




After doing that you have to pick pad and your shape will be created.
![image35](https://user-images.githubusercontent.com/123673728/215070578-a8a19ea2-7e20-44dd-82dd-0e5a753e3ada.png)




If you want to add shapes or holes or pockets to your object. You can select the top of your object and then go to create a sketch.

![image31](https://user-images.githubusercontent.com/123673728/215070649-f703ab5c-009e-49e7-bf86-0a3f3a773c8e.png)

![image44](https://user-images.githubusercontent.com/123673728/215070681-f60820ac-00ed-4c05-971e-9b1a478a4cbf.png)




The the selcted part of your object will appear.
![image13](https://user-images.githubusercontent.com/123673728/215070747-737a34c1-8d9b-4165-8e9a-fb61cd4f6e7b.png)



There you can add a shape on top and then select close.

![image108](https://user-images.githubusercontent.com/123673728/215070778-2089a9ff-8be9-4fca-9854-fb37d58514b9.png)


After selecting close , instead of clicking on pad you have to select on pocket or whole.
![image106](https://user-images.githubusercontent.com/123673728/215070831-bb9218e1-d238-431e-aefd-2f7932257b97.png)



This will be the end result.


##1.2 freecad for cnc
##1.2.1 making and object.
The first thing to do when using free cad for cnc is to make a 2D object.
![image20](https://user-images.githubusercontent.com/123673728/215070891-a882b786-0873-4212-803b-51ad3bf136c9.png)



After making the 2D object you have to change your units to metric small parts (this is mandatory when planning to use the cnc machine.

You do this by going to edit then preferences.
![image46](https://user-images.githubusercontent.com/123673728/215070950-9328a552-aa79-4a6e-b13b-40179d00cde0.png)



Then you select units.

![image57](https://user-images.githubusercontent.com/123673728/215070986-0b870829-1ad0-4e7b-825b-2b4097f5f5e9.png)


Then units system and change it to metric small parts.

![image71](https://user-images.githubusercontent.com/123673728/215071005-67722369-b8b9-4724-afa9-69bec4586bbf.png)


After doing that select pad to make your 2D object 3D.
![image61](https://user-images.githubusercontent.com/123673728/215071025-e3ab1003-e0fa-44ba-97b3-281a38ceb2a8.png)

when you make your object. Always remember to write down your debt because. It will important later on.


Object from another angel:
![image59](https://user-images.githubusercontent.com/123673728/215071068-34e382f3-ebe0-4ff6-a807-12ac5520a1e4.png)

Now if you want to add a pocket to your 3d design you can use the steps in 1.1 making objects with pockets.


Object with a pocket:
![image45](https://user-images.githubusercontent.com/123673728/215071134-cd4b7d7a-7645-4238-9ada-c23ff5660212.png)


## 1.2.2 making jobs
The next step to making an object to cnc is making a job. To that we have to select a new workspace called path.
![image103](https://user-images.githubusercontent.com/123673728/215071182-343dbf4c-3729-4720-b76b-13f957966f3f.png)

next you have to select job, so you will be able to make operations.
![image89](https://user-images.githubusercontent.com/123673728/215071210-81d84e88-53e7-48b8-a0e9-46dd294a3154.png)



After selecting job this will pop up.
![image70](https://user-images.githubusercontent.com/123673728/215071238-1b373f21-ca6a-4ae7-9647-5b20cef6280b.png)



When you see this , you have to make sure body is selecting and then click okay.


Once you do that. This promp will open up.
![image47](https://user-images.githubusercontent.com/123673728/215071310-4ba0d085-d480-46cc-99b9-f468f9a257db.png)



The x,y,z stand for the length, height and width of the stock you will be using to cut out your object. To make sure that the object is cut out right, the stick has to be somewhat bigger than the object.
![image60](https://user-images.githubusercontent.com/123673728/215071339-60a8bfd2-be5c-402e-8084-ee963334bf81.png)

As you can see I changed the x, y and z and the stock around my object got bigger.


Next thing to do is click on output.
![image36](https://user-images.githubusercontent.com/123673728/215071375-e72b2f25-ef09-424b-b838-3bb84f9d2488.png)


and this will popup:
![image64](https://user-images.githubusercontent.com/123673728/215071398-0e062359-4cdc-469a-bfec-5429d9e09f50.png)



Next you want to change the processor to ucnc.
![image68](https://user-images.githubusercontent.com/123673728/215071453-bc5460b1-9457-4f70-84b6-20a020b4405f.png)

then select this and save the file where you want.
![image111](https://user-images.githubusercontent.com/123673728/215071478-4f9b2e86-035f-4f12-a111-6eda6c535917.png)


Note that when saving you have to save it as, UCNC OR NC.

![image111](https://user-images.githubusercontent.com/123673728/215071519-db652a46-6cbd-434c-a1d4-37a0d5c1576c.png)


Next step is to  go back to  setup and change origin position. To that you have to zoom in on the point you want to start cnc on and select. Then in the promp scroll down and click set origin.

![image112](https://user-images.githubusercontent.com/123673728/215071548-41a3bec1-60c2-45cb-88cf-c783d599836c.png)







 This will be the result.
![image32](https://user-images.githubusercontent.com/123673728/215071564-c9d5e8f3-e989-4470-a9b1-b5016f0dfae2.png)



 Then now you can click on okay.


Next is to hide the body.
![image95](https://user-images.githubusercontent.com/123673728/215071609-eb067e6d-55a0-4e2e-a052-8fbbcf4eb243.png)



If you look here you can see that we have two bodies. The normal body and the model body.

You want to work with the model body and hide the normal body. To do that simply select the body and press space. You will see the body disappear and to show the model body simply select it and then spacebar and the model body will appear.





## 1.2.3 making tools
We need to make tools for our cnc machine. The first is to go to tool bit doc and select.
![image49](https://user-images.githubusercontent.com/123673728/215071812-b850785b-9693-4ec2-99da-25e5b4431d04.png)

this will pop up after selecting.
![image66](https://user-images.githubusercontent.com/123673728/215071823-e54e8c42-8912-467d-8a13-c18e4d52daf1.png)



And you will see the tools. initial y freecad does not have a 3 mm toot so you will have to create one.

To do that you have to select this:


![image72](https://user-images.githubusercontent.com/123673728/215071859-3e031940-bb46-4105-b327-6ecbae1947b3.png)

Then this will pop up.
![image79](https://user-images.githubusercontent.com/123673728/215071888-1dfe9457-8f96-4713-b707-b322da8f7d76.png)

then select on create toolbit.

This will pop up:

you have to select endmill in this  case.

Then this will pop up.
![image92](https://user-images.githubusercontent.com/123673728/215071919-473be871-144f-4e86-85ee-aa7b26ded58f.png)





Here you then save the mill as 3mm_Endmill.fctb

 Not that you have created your mill you go back to this.
![image79](https://user-images.githubusercontent.com/123673728/215072022-41edf90e-9ece-44ca-853c-e10c80f755b0.png)

and your tool will be shown.


If you dubbel click on your mill. The parameter will pop up. Depending on your measurements of your mill you can change the parameters.

For example:

This the default parameters i got for  my mill:
![image102](https://user-images.githubusercontent.com/123673728/215072059-0335daa8-2cc0-4e1b-902b-47c91c9d67a9.png)

but after getting the measurements for the mill i will be using in the lab i had the change the perameters to:

![image97](https://user-images.githubusercontent.com/123673728/215072089-84f1829a-3d0d-4e0f-9477-6efa82331bfb.png)


Then click okay and close it.

Next is adding the end mill to tools.

To do that you have to select tools.
![image17](https://user-images.githubusercontent.com/123673728/215072152-3f332afc-9ecd-479c-827a-2873d95da1ab.png)



And dubbel click on the endmill.

![image116](https://user-images.githubusercontent.com/123673728/215072215-dc81840e-2b67-45b3-9807-3eef19be384d.png)


And the mill will appear here.
![image113](https://user-images.githubusercontent.com/123673728/215072230-c4c9fed2-9951-4eae-a81d-26c8089ad238.png)



Then you can delete the default tool.

![image73](https://user-images.githubusercontent.com/123673728/215072245-f181fd2c-420c-4131-b9fd-73b9f06011fe.png)



Next is putting in some parameters for the 3mm endmill

You need the dubbel the endmill in tools. And this will pop up.
![image37](https://user-images.githubusercontent.com/123673728/215072297-30d5d622-0c99-4f42-91ea-c5960dda2bd2.png)





 Now to set these parameters you will need to fiddle around with the cnc machine.

But i was given the parameters so i did not have to do that.
![image118](https://user-images.githubusercontent.com/123673728/215072351-5ce77b82-5cac-43ad-a58e-57a78eb5f1b9.png)



I entered these parameters and then the mill was ready and setup.

## 1.2.4 Making operations to use the tools.(profiles)
The first is to click on job and then pocket shape ( to mil out the pocket).
![image40](https://user-images.githubusercontent.com/123673728/215072424-ff483a3f-c482-4c6c-b850-469280050474.png)



Then open base geometry. Is basically you select the pocket you want to work with.

To that you have selct the pocket rim you want o work with and then click add.

![image39](https://user-images.githubusercontent.com/123673728/215072472-c886f7b8-6463-4f74-8198-ef34e88e33a3.png)




When you this .
![image76](https://user-images.githubusercontent.com/123673728/215072499-6f6238a1-a445-42e4-a5bd-244f4385510d.png)



Then you know the pocket has been added successfully.

 Next go to operation.

Edit it to look like this.
![image23](https://user-images.githubusercontent.com/123673728/215072818-457cae06-0146-48d9-8434-b3f03906e814.png)



Next go depths. And edit it to look like this depending on your tools and machine.



This what your depths should look like if you are milling a whole. The final always need to more than your object thickness.

 Do the same for all the other pockets and wholes. With pockets the final depths depends on how deep you wan the pocket to be.

 If  you want to sumilate the cutout. Simply click on cam simulator.
![image83](https://user-images.githubusercontent.com/123673728/215072590-d0045f5f-941d-4924-804a-4a97eba1c089.png)



 next is to cut out base material ( so the whole thing)

First you need to make new profile and select the face and add in base geometry.
![image58](https://user-images.githubusercontent.com/123673728/215072619-5185d636-17c8-46f1-af2c-39aa4bcfae16.png)



Next the  depths and operation.

## 1.2.5 adding tabs
Tabs are added to prifle that are being cutout completely.

How select the profile, option and then selct the tabs you want to use.

![image18](https://user-images.githubusercontent.com/123673728/215072665-2068979c-e1b9-4c40-bb8c-70ee02238662.png)



![image54](https://user-images.githubusercontent.com/123673728/215072735-5de19246-1d18-495e-b31a-e36171325e91.png)

 
![image23](https://user-images.githubusercontent.com/123673728/215072764-096ca659-8cee-4da3-8fda-6a65a6dd8058.png)



 And then click apply.



 

# Laser










![image67](https://user-images.githubusercontent.com/123673728/215072853-fc74f9eb-31d8-4c58-a30f-9af820ea2a71.png)



















## What is a laser cutting?
Laser cutting is a technology that uses a laser to vaporize materials, resulting in a cut edge. While typically used for industrial manufacturing applications, it is now used by schools, small businesses, architecture, and hobbyists.

 ## Laser cutting using box maker.
The first is to go to https://www.makercase.com/#/basicbox nad create the box you want.
![image87](https://user-images.githubusercontent.com/123673728/215072941-b1821b1d-78c2-47f4-afab-38a736360257.png)
add the lengt thickness you want and go to dowload box plans.

![image48](https://user-images.githubusercontent.com/123673728/215072968-3417e1f4-01ec-4ac6-937c-ddd7d0efa36b.png)

go to kerf and change it to the kerf of your machine.

 Then download an svg or dxf

## Inkscape

.

Next step is to open in inkscape.

If you want to add an image simply import one.

![image96](https://user-images.githubusercontent.com/123673728/215073085-172041e8-378d-44d3-8d8e-534c0328ae45.png)


Then select trace bitmap. And selct apply.
![image69](https://user-images.githubusercontent.com/123673728/215073121-adc030c0-3674-453e-ad41-49820d71d7b3.png)

copy the bitmap trace and place wherever you want.
![image104](https://user-images.githubusercontent.com/123673728/215073150-2b130d12-0621-4a06-8d9f-4446ff9bb041.png)

save file and then open lightburn.
![image41](https://user-images.githubusercontent.com/123673728/215073171-a1c0d324-0443-43d4-b999-d0d46746c26d.png)

set the parameters there then print.


## Kicad and flatcam and candle

   
![image55](https://user-images.githubusercontent.com/123673728/215073200-9b8824f1-7aa1-4ec3-9849-646c18653ea2.png)

                  








































## What is kicad?



KiCad is a free software suite for electronic design automation. It facilitates the design and simulation of electronic hardware. It features an integrated environment for schematic capture, PCB layout, manufacturing file viewing, SPICE simulation, and engineering calculation.


## What is a pcb board?

A printed circuit board is a medium used in electrical and electronic engineering to connect electronic components to one another in a controlled manner.


![image91](https://user-images.githubusercontent.com/123673728/215073402-03b6b5f9-47ac-4378-b7ef-b37f7c786c19.png)


 ## How to use kicad?

The first thing i needed to do is download kicad for windows from this link:

https://drive.google.com/file/d/1AHXvjmytPDZ5c39XMc04v2o4xejCfdQQ/view?usp=sharing

 

Next  i downloaded the symbol libraries that was needed. Note: when kicad is installed you will onlyhave the default libraries but you can import libraries(like i did it) if it is neede for your project.


When you open kicad this is the first thing you will see.



Next you have to go to file and select create new project. After doing that you this will appear.

![image110](https://user-images.githubusercontent.com/123673728/215073497-48dcd0c7-105f-45c2-a6b7-eedefe1281fc.png)


You have to select kicad.sch.

This will pop up afet selecting that.




Nextstep is to add symbols. You do that by selecting this.


![image94](https://user-images.githubusercontent.com/123673728/215073656-ee8c6fcf-7226-4206-b6b8-7df95ee637d6.png)


And this will pop up:
![image84](https://user-images.githubusercontent.com/123673728/215073672-0cb8294a-df15-4d17-beb7-d5b3806c11b6.png)



 From this you can select all the parts you need for your pcb board.

After adding the parts , you can then connect them by adding wires.

This will be the result:
![image11](https://user-images.githubusercontent.com/123673728/215073760-8bd108d9-f637-4552-8228-ff29c500152d.png)



Next you need to go here and run footprint assignment tool:


when you go on this tool this will pop up.




![image93](https://user-images.githubusercontent.com/123673728/215073787-a32343ae-487d-43d0-94ed-b3436cad4be1.png)

Here is where you assign  the footprints to your symbol.

 After doing taht pres asve and ok.

 

Next is saving the file as a net list.

To do that you need to go to export and netlist. Give the file a name and just save.

![image114](https://user-images.githubusercontent.com/123673728/215073810-6ec5dd97-898e-4123-b948-18d42d7a1627.png)



 Now that your file is  saved as a netlist its time to open pcb editor and import the net list.


![image28](https://user-images.githubusercontent.com/123673728/215073894-b4447111-85ad-4dfe-9245-f53c044c6530.png)





Then you select this to route.
![image105](https://user-images.githubusercontent.com/123673728/215073911-ef67989d-ddbf-4fb1-8ec0-95768fdfb4c6.png)




 After routing ggo to place and select origin.

![image62](https://user-images.githubusercontent.com/123673728/215073929-e3a8ce2d-ed2a-4094-b722-5c1f7de930ce.png)












After doing that go to file then plot.





 And Set the parameters.



# Business model canvas





































# 3.1 What is a business model canvas?
A business model canvas(a one sheet business plan) is a visual representation of a business model, highlighting all key strategic factors. So a business model canvas basically gives you an overview of the company's workings, customers, revenue streams etc.

Business model canvases are most used by start-ups but it is also used to document existing company’s.

Alexander Oswalder was the first person to propose the use of a business model canvas.

Before making a business model canvas you have to have a business plan (Plan for successful operation of a business or startup that identifies Sources of Revenue and Target Customer Base combined with details of Financing), only then can you start making a canvas.

# 3.2 the building blocks
When making a Business model canvas you have 9 essential building blocks.

Those building blocks are :

Key partners: who will be your key partner/suppliers? Which key resources do they provide?
Key activities :what are the key processes and task we need to create our value proposition?
Key resources: what key resources do our key activities require?
Value proposition: Which of our customers problems are we helping to solve?Value proposition look like?
Customer relationships:what type of relationship do you want with customers?Which fits best with each segments?
Channels:To which channels do each of our segments want to be reached?Which ones are most cost efficient?
Customer segments :For whom are we creating value?Who are the most important customers.?
cost structure: I mean and elements of operational expense? (Floating variable cost,inventory ,WIP and capital assets).
Revenue streams: From which channels and segments? how much does each contribute to overall revenue?



# 3.3 Why use BMC?
A few resons to use a BMC are because it describe your business in page, it si costumer focused,its easy to present, Easy to benchmark peers/competitors etc.

# 3.4 my BMC
Before making my Bmc i had to research about my product, what is needed to make it , the development process, what kind of value it will bring to customers' lives and how I will finance building the product.

https://next.canvanizer.com/canvas/r0C4ZGpeowqQX







