VehiclePoint Client
********************************************************************************
Description:
- Send command to Server (Device) and receive response
- Send request to Server to read location and receive response
- Display location of vehicles in real-time
********************************************************************************

VehiclePoint Server
********************************************************************************
Description:
- Receive request from Device to log location and respond on that request
- Receive request from Client to read location and respond on that request
- Receive VP command from Client and send it to Device
- Receive ALARM request from Device and inform Client
********************************************************************************

VehiclePoint Device
********************************************************************************
Description:
- Send location log request to Server (receive confirmations)
- Receive command from Client
- When confirmation is not transmited, Device breaks electric power of vehicle
********************************************************************************

