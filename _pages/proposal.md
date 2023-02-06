---
layout: page
title: Project Proposal
permalink: /proposal/
---

**Objective**
1. Build a low-cost (<$100) autonomous car for under-privileged classrooms to discover robotics
2. Create an accompanying guide for hardware construction
3. Author a small library of end-to-end deep learning models to pair with the physical construction of the robot
4. Have the autonomous car be able to travel around an oval racing course while switching lanes in order to avoid obstacles

**Why**: For students beginning a journey in robotics there are not many projects that allow for inclusive introduction into the hardware and software necessary for an end-to-end robotics project. In my robotics experience there was a very large gap between teaching kids about coding while also understanding the hardware components that implement the code written. This project intends to provide underprivileged classrooms with access to the full range of knowledge necessary to understand the beginning processes of robotics with equal focus on hardware and software.

**How:** I will be researching different constructions 1/24 RC cars to scope out the most efficient pieces of hardware that can run low level models and algorithms while still efficiently running.

## Hardware:
1. RC Car
    - [1:24 Bezgar Aston Martin](https://www.amazon.com/Remote-Control-Car-2-4Ghz-Vantage-Licensed/dp/B094MN9QMF/ref=sr_1_30?crid=1A69MB5L29DVM&keywords=1%3A24%2BRC%2Bcar&qid=1675107085&s=toys-and-games&sprefix=1%2B24%2Brc%2Bca%2Ctoys-and-games%2C143&sr=1-30&th=1) ($19.54)
    - [1:24 New Bright Ford Mustang](https://www.walmart.com/ip/Adventure-Force-1-24-Ford-Mustang-Mach-1-Battery-Radio-Control-Sports-Car-2423-13R/943187099?wmlspartner=wlpa&selectedSellerId=0&wl13=3159&adid=22222222227000000000&wl0=&wl1=g&wl2=c&wl3=42423897272&wl4=pla-51320962143&wl5=9004080&wl6=&wl7=&wl8=&wl9=pla&wl10=8175035&wl11=local&wl12=943187099&veh=sem&gclid=Cj0KCQiA8t2eBhDeARIsAAVEga3wZ1Y_MD6FX8UaEbEgBE2e1ES9es6IBGPtuYf73mdwPMLPCk0kMxAaAqEKEALw_wcB) ($10.97)
    - [1:24 New Bright Ford Truck](https://www.jcpenney.com/p/new-bright-124-scale-rc-ff-truck-ford-raptor-red/ppr5008038147?pTmplType=regular&country=US&currency=USD&selectedSKUId=90984850018&selectedLotId=9098485&fromBag=true&utm_medium=cse&utm_source=google&utm_campaign=Cars&utm_content=90984850018&cid=cse%7Cgoogle%7CBoys%7cCars_90984850018&kwid=productads-adType%5EPLA&gclid=Cj0KCQiA8t2eBhDeARIsAAVEga07l6WRafHY5fxzhD9Xl-KrvI2mriMtLtaKDTrUivQOj5FFp6Fcou0aAhgbEALw_wcB&gclsrc=aw.ds)($22.49)
    - [1:16 Banggood Truck Vehicle](https://usa.banggood.com/WPL-D12-MINI-1-or-16-2_4G-4WD-Full-Scale-On-Road-Electric-RC-Car-Truck-Vehicle-Models-With-LED-Light-p-1910692.html?imageAb=1&utm_design=18&utm_email=1648221928_2324&utm_source=emarsys&utm_medium=Shipoutinform190813&utm_campaign=trigger-logistics&utm_content=leander&sc_src=email_2671705&sc_eh=df193bbfc3bee8c21&sc_llid=34090035&sc_lid=104858042&sc_uid=UiMl0DkOH7&akmClientCountry=America&a=1675131304.6433&akmClientCountry=America&cur_warehouse=CN&ID=531930) ($34.99) 
        - Pretty large truck bed so it’d be easy to mount the battery
    - [1:28 4WD Drift car](https://www.banggood.com/Wltoys-284131-1-or-28-2_4G-4WD-Short-Course-Drift-RC-Car-Vehicle-Models-With-Light-p-1898593.html?utm_design=18&utm_email=1646706345_2324&utm_source=emarsys&utm_medium=Shipoutinform190813&utm_campaign=trigger-logistics&utm_content=leander&sc_src=email_2671705&sc_eh=df193bbfc3bee8c21&sc_llid=33910587&sc_lid=104858042&sc_uid=UiMl0DkOH7&cur_warehouse=CN) ($77.46) 
2. Board Computer
    - Raspberry Pi 3 Model B ($35) 
3. Camera
    - [Arducam Mini Module Camera](https://www.uctronics.com/arducam-mini-module-camera-shield-w-2-mp-ov2640-for-arduino-uno-mega2560-board.html) ($25.99)
    - [Arducam 5MP](https://www.amazon.com/Arducam-Megapixels-Sensor-OV5647-Raspberry/dp/B012V1HEP4/ref=sr_1_6?keywords=camera%2Bmodule&qid=1675130119&sr=8-6&th=1) ($14.99) 
    - [Smaller ArduCam](https://www.robotshop.com/products/arducam-640x480-03-mp-lens-ov7675-cmos-camera-module-w-adapter-board?gclid=Cj0KCQiA8t2eBhDeARIsAAVEga2un_-Uh_-5J5RY36AX3Q3GmSwyIB0yHvrZ1yDoI6S-GAp0gIcH63kaAnY2EALw_wcB) ($4.99)
4. Battery (Battery Capable of 2A 5V output w/ microUSB cable)
    - [Anker compact portable charger](https://www.amazon.com/Anker-Upgraded-Candy-Bar-High-Speed-Technology/dp/B071G7TL2C/ref=as_li_ss_tl?dchild=1&keywords=anker%2Bbattery%2B6700&qid=1590963034&sr=8-4&linkCode=sl1&tag=donkey05-20&linkId=1faf0b2273da6cd3157359d9a5a5bb61&language=en_US&th=1)
5. Motor Driver (Motion Control)
    - [Pololu DRV8835](https://www.pololu.com/product/2135) ($10)
    - [Pololu TB6612FNG](https://www.pololu.com/product/713) Dual Motor Driver Carrier ($9.95) 
    - [L293D](https://www.ti.com/product/L293D#order-quality) ($ - TI hides prices tags lol)
        - This is just the actual motor driver chip. Implementation would require soldering and open wire configurations.
6. MicroSD Card

**Referenced Resources:**
- [DeepPicar: A Low-cost Deep Neural Network-based Autonomous Car](https://ieeexplore.ieee.org/abstract/document/8607229)
    - The architecture of the DeepPicar is  <$100 and runs computationally complex models on a Raspberry Pi 3.
- [Donkey Car Library - High level self driving library](https://github.com/autorope/donkeycar)
- [Donkey Car Docs](http://docs.donkeycar.com/)
 
**Outside Explanations/Materials:**
- [Autonomous Car Levels](https://www.carmagazine.co.uk/car-news/tech/autonomous-car-levels-different-driverless-technology-levels-explained/#:~:text=Level%205%20driverless%20cars%3A%20fully,called%20'operational%20design%20domain)
- [What is an ROS node?](https://roboticsbackend.com/what-is-a-ros-node/#:~:text=A%20ROS%20node%2C%20according%20to,%2C%20services%2C%20actions%2C%20etc)



