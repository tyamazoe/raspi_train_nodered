# raspi_train_nodered
RasPi IoT Railway model train controller. node-red flows.

## controller/flows.json
Provide web GUI to control train.
Speed Up, Speed Down, Stop and Change Direction button send speed as PWM signal to RasPi GPIO.
Gauge indicates current speed.
Status shows current direction Forward/Reverse.

![2019-08-14 (2)](https://user-images.githubusercontent.com/11979965/63134482-8aa54580-c004-11e9-8b83-8488b613e967.png)
![2019-07-19 (2)](https://user-images.githubusercontent.com/11979965/63134497-a4468d00-c004-11e9-9974-8a17180b19f7.png)


## controlleri_vith_view/flows.json
Added video streaming view to controller GUI from the same RasPi mjpeg-streamer.

![2019-08-14](https://user-images.githubusercontent.com/11979965/63134508-af99b880-c004-11e9-95c2-7ee26fbf1200.png)
![2019-08-14 (1)](https://user-images.githubusercontent.com/11979965/63134513-b58f9980-c004-11e9-8c08-5293ba1d51e6.png)

## Requirements
- Need to install node-red-dashboard.
- Run on RaspBerry Pi.
