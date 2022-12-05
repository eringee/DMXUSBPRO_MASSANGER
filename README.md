# DMXUSBPRO_MASSANGER

![ReferencePhoto](https://user-images.githubusercontent.com/13860084/205718430-94c1422c-9799-444c-9ab1-c34d60df27e6.jpg)

 For those of you mourning the death of the MaxMSP DMX Pro objects, I humbly offer this elegant patch as an alternative that functioned for me in Max 7. 
 
 This code is based off of <a href="https://youtu.be/dAaZb8M-fpw?t=798"/>this YouTube tutorial</a> by YouTube user <a href="https://www.youtube.com/@Programmingforpeople">Programming for People</a>, however I did have to modify his instructions because they didn't work for me right away.
 
 For added ease of use, I combined this code with Thomas Ouellet Frederick's MaxMSP Massanger object, modified so as to throttle the dataflow to an amount that the DMXUSBPro can normally handle.
 
 Once you have connected the DMXUSBPro to the computer via USB, you should be able to refresh the ports and see the device.  Select the device, choose your baudrate (I imagine it to be 9600), select 20ms data rate, then you are ready to start experimenting with your DMX channels.
 
 Add additional DMX channels to the patch by adding more zeros to the pak object.


