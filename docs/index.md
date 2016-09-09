FIWARE IoT Stack allows you to connect devices and receive data, integrating all
device protocols and connectivity methods, understanding and interpreting relevant information.
It isolates data processing and application service layers from the device and network complexity,
in terms of access, security and network protocols.

These are the main benefits of solutions 'powered by the FIWARE IoT Stack':

- Simple sensor data integration
- Device-independent APIs for quick app development & lock-in prevention
- Modular
- Scalable. High available
- Open & standards based. FIWARE compliant

## APIs available

FIWARE IoT Stack provides the following APIs:

- [Authentication API](authentication_api.md): manages tokens for APIs usage.
- [Device API](device_api.md): allows managing devices, sending data from the device to the cloud and receiving commands.
- [Data API](data_api.md): allows querying and subscribing to data stored at the cloud.
- [Historical Data API](historicdata_api.md): allows querying historic data series and statistics stored at the cloud.
- [Data Processing API](dataprocessing_api.md): allows analyzing data stored at the cloud on real time and triggering actions.
- [Management API](management_api.md): allows creating new services and users to provide a multi-tenant environment.

## Management Portal

It is recommended to build an admin website for performing comfortably most of the FIWARE IoT Stack management operations available on APIs. Most relevant administration actions could be: 
- Creation of new services and subservices
- Creation of new users
- Creation of new devices
- Visualization of stored data
- Send commands to devices
- Set up simple notifications based on data

## FIWARE Components

FIWARE IoT Stack is based on the following [FIWARE components](walkthrough.md) in order to provide its functionality:

- Device Backend Gateway (IDAS)
- Context Broker (Orion)
- Short Term Historic (STH)
- Connector Framework (Cygnus)
- Identity Management (IDM)

In addition, the platform includes the following additional components. They are not part of FIWARE (although
they are still open source) but integrate with the platform using FIWARE-based APIs (in particular, using NGSI): 

- Complex Event Processing (Perseo)
