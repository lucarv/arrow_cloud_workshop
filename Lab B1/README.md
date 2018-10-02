## Azure IoT Cloud Workshops# Lab A1
For this lab we will:
* use a raspberry pi to send measurements to an IoT Hub, 
* visualize the event flow on the iot device explorer, 
* save the messages to blob storage 
* visualize the time series event 
* create actions.
* create a custom dashboard

BY USING THE AZURE SDKs AND SAMPLES FOUND [HERE](https://github.com/Azure/azure-iot-sdks)

![](images/labb1.png)

## Advanced
Create a device twin property that will change the telemetry interval

## Path Multiplexing
Create a Stream Analytics Job to multiplex telemetry into cold and hot path (you can jump to lab A1 for step by step instructions or try your luck on the portal)

Route all the messaging contents to a blob container
Route messages where the humidity is greater than 50 to an azure function
Route all the telemetry messages to Power BI and create a dashboard of your liking
