# Set Up Datastreams

## **Add Datastream**

For the goal of this tutorial skip the Metadata Tab and go directly to Datastreams tab.

Datastreams are channels that are used to send data between the device and Blynk.Cloud. We will be using this Datastream to send random values from your device.

Click on **Add Datastream** button. Choose **Virtual Pin** in the dropdown menu:

![](https://user-images.githubusercontent.com/72824404/120767457-e1567900-c523-11eb-9a1e-f7922e5461c7.png)

Set up the Datastream like this:

![](https://user-images.githubusercontent.com/72824404/119647256-b899f980-be28-11eb-83af-09c1ebe7cc94.png)

* **Name:** Random Value Send
* **Virtual Pin:** V0
* **Data Type:** Integer
* **Min/Max:** 0/100

Skip all the other settings. When done, press Create and the new Datastream will be created.

These settings mean that all the devices that inherit this Template will process `integers` in the range of `0 to 100` through a `Virtual Pin V0`

## **Add a Second Datastream**

Click on **Add Datastream** button again. Choose **Enumerable** type in the dropdown menu and set up the Datastream. We will be using this Datastream to send a value from mobile and web dashboards to the device.

![](https://user-images.githubusercontent.com/72824404/119654605-51347780-be31-11eb-9a12-a3aa255a0b30.png)

* **Name:** Button
* **Virtual Pin:** V1
* Add **Row1:** 0, OFF
* Add **Row2:** 1, ON

Skip all the other settings and press **Create**

These settings mean that all devices that inherit this Template will process values `integers` in the range of `0 to 1` through a `Virtual Pin V1`and Blynk will interpret `0` as `OFF` and `1` as `ON` strings.

