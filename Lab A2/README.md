# Lab 2.2
For this lab we will implement the Azure IoT edge to our architecture and only send necessary data to Azure. In order to run Azure IoT Edge you need to run Docker and we will in this lab do that on an Ubuntu vm.

![](images/architecture2-2.png )

### Create Ubuntu vm
Add an **Ubuntu Server vm 16.04 LTS** to your Resource group

Ubuntu VM settings
* Give the vm a name
* Provide a user name
* Choose "Password" as the Authentication type
* Select your Resource Group
* Select North Europe as Location and click OK
* Select "B2ms" as your vm size
* On page 3 "Settings" leave everything as-is and click "OK"
* On page 4 click "Create"


### Install Putty and connect to Ubuntu vm
To connect to your new Ubuntu vm you can use Putty.

continue this tutorial [here] at the point wehere you install the runtime dependencies:  
(https://docs.microsoft.com/en-us/azure/iot-edge/quickstart-linux)

## Follow this tutorial but DON'T CLEAN THE RESOURCES !!!

Continue by following the stream analytics tutorial found [here](https://docs.microsoft.com/en-us/azure/iot-edge/tutorial-deploy-stream-analytics)


## VERY ADVANCED SAMPLE
Use the edge as a transparent gateway using the tutorial found [here](https://docs.microsoft.com/en-us/azure/iot-edge/how-to-create-transparent-gateway-linux)