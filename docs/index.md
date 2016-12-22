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
- [CEP API](cep_api.md): allows analyzing data from your IoT device and triggering actions.
- [Management API](management_api.md): allows creating new services and users to provide a multi-tenant environment.

## Multitenancy

FIWARE IoT Stack multitenancy model is described [in this section](multitenancy.md).

## Data persistence

FIWARE IoT Data capabilities go far beyond querying the current context data or the short-term history. FIWARE IoT Stack provides means for storing hitorical data for the mid and long-term in third-party components; the following ones:

- [HDFS](http://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsUserGuide.html), the [Hadoop](http://hadoop.apache.org/) distributed file system.
- [MySQL](https://www.mysql.com/), the well-know relational database manager.
- [CKAN](http://ckan.org/), an Open Data platform.
- [MongoDB](https://www.mongodb.org/), the NoSQL document-oriented database.

## FIWARE Components

FIWARE IoT Stack is based on the following [FIWARE components](walkthrough.md) in order to provide its functionality:

- IoTAgents (IoTA)
- Context Broker (Orion)
- Short Term Historic (STH)
- Connector Framework (Cygnus)
- Security Components: Identity Management (IDM), Policy Enforcement Point (PEP) and Access Control (AC). The platform does not
  use the FIWARE GEri for these components, but alternative GEi conforming with the same GE specifications (see 
  [this clarification](https://ask.fiware.org/question/1/what-is-a-fiware-ge-and-a-gei/) about GE, GEi and GEri terms).

In addition, the platform includes the following additional components, which are not part of FIWARE (but still open source):

- Complex Event Processing (Perseo). It is not part of FIWARE, but integrates with the platform using FIWARE-based APIs (in particular, using NGSI).

## FIWARE Datamodels

A set of recommended data models to be used with FIWARE IoT Stack can be found [here](http://fiware-datamodels.readthedocs.io/en/latest/index.html).
