# lanbon-l8
Lanbon L8 smart switch backup

The Lanbon L8 series is a collection of smart home devices sold by Shenzhen Lanbon Hi-Tech Co. Ltd

They have several in their series:

Lanbon L8 - their newest series of products
            Their LCD touch screen devices use ESP32 for their detachable front-plate controller
            The LCD touch screen plates seem to have the same hardware with different firmware depending on the relays attached to the back.

The L8 series LCD touch screen products include four different SKUs (others are either end-of-life or basically different marketing names for the same devices):

Smart switch / 5 model in one
            SKU: L8-HS
            Rated power: 200W
            Features 3-gang light switch relays

Dimmer switch
            SKU: L8-HD
            Rated power: 100W
            Features a 1-gang light dimmer which varies the voltage
            
Boiler switch
            Features a 1-gang switch with a 16-A rating for high-load devices, such as water heaters

 Air Conditioner switch / Thermostat switch
            Marketed as a controller for air conditioners/condensers / floor heaters



https://www.lanbon.cn/
https://lanbon.en.alibaba.com/?spm=a2756.trade-list-buyer.0.0.27b076e9IVMelt&tracelog=from_orderlist_company

My particular interest in it came upon discovering the Open HA switchplate project by Fvanroie, which provides a great way to customize the hardware and integrate it into HomeAssistant.

I backed up the firmware of some of the Lanbon L8 am using by following BlakAdder's guide here:
https://blakadder.com/lanbon-L8-custom-firmware/

