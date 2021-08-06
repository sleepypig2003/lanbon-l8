# lanbon-l8
## Lanbon L8 smart switch backup

The Lanbon L8 series is a collection of smart home devices sold by Shenzhen Lanbon Hi-Tech Co. Ltd

They have several in their series:

Lanbon L8 - their newest series of products
            Their LCD touch screen devices use ESP32 for their detachable front-plate controller
            The LCD touch screen plates seem to have the same hardware with different firmware depending on the relays attached to the back.

The L8 series LCD touch screen products include four different SKUs that I know of
(it's hard to tell what is there or what they do, and the confusion is exacerbated since the packaging doesn't explain or differentiate the technical features, firmware differences, and some others still marketed on-line can already be end-of-life or basically different marketing names for the same devices)

Firmware variations: without homekit, with homekit
There may be firmware variations on whether you need it to be compatible with Apple homekit or without, but AFAIK the hardware is the same (I'm guessing a reflash to any of the firmware can change the functionality accordingly)

Plate size variations: US, UK/EU
Variants also include the plate size (the US plate size is different than the UK/EU plate sizes (86mm x 86mm))

When in doubt, chat directly to a salesperson for the Lanbon store in Alibaba to see if it is fit for your purpose


Smart switch / 5 model in one
            SKU: L8-HS
            Rated power: 200W
            Connections: N L L1 L2 L3
            Features 3-gang light switch relays

Variants:
- Smart switch
          - L8-HS (1/2/3GANG light switch)
            Rated Load: 200W/GANG(single switch)
            Load type: incandescent lamp, energy saving lamp, fluorescent
            
          - L8-HS (scene switch)
            MAX scene: 3
            
          - L8-HS (curtain switch)
            Rated Load :200W
            Loat type: horizontal curtain motor/vertical
            
          - L8-HS (LCD 1gang switch)
            Rated load: 16A

- Dimmer switch
            SKU: L8-HD
            Rated power: 100W
            Connections: N L L1
            Features a 1-gang light dimmer which varies the voltage
            
- Boiler switch
            SKU: L8-HB
            Rated load: 16A
            Load type: various brand water heater
            Features a 1-gang switch with a 16-A rating for high-load devices, such as water heaters

 - Air Conditioner switch / Thermostat switch
            SKU: L8-HT24
            Voltage: 24V  ( Yes, 24V! ) 
            Connections: C R G Y W  ( See: https://findanyanswer.com/how-does-a-24-volt-thermostat-work )
            Controller for HVAC/air conditioners/heaters


https://www.lanbon.cn/
https://lanbon.en.alibaba.com/?spm=a2756.trade-list-buyer.0.0.27b076e9IVMelt&tracelog=from_orderlist_company

My particular interest in it came upon discovering the Open HA switchplate project by Fvanroie, which provides a great way to customize the hardware and integrate it into HomeAssistant.

I backed up the firmware of some of the Lanbon L8 am using by following BlakAdder's guide here:
https://blakadder.com/lanbon-L8-custom-firmware/

