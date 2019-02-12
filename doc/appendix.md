## Assumptions for the Sample Questions

For this part it is assumed we can start with a docker-compose bringing up the necessary elements. It is assumed that we
can use the tutorial context-provider to act as a series of devices. The test here is how do you connect these things?
Can the candidate describe how to use any of the common FIWARE components? Can the candidate describe what they are
doing?

The sample list of questions is merely based on my current knowledge of active FIWARE components, and should be drawn up
and ratified by the standards committee. Questions can should be added, modified or removed as the FIWARE ecosystem
develops.

Every currently supported GE should be relevant to one or more questions, with the balance based on current usage (e.g
there should be more Core Context Questions than Data Monetization since this is a commoner procedure.

Depending on the time allocated to the examination, a candidate could be asked one or at most two questions on the
list - chosen at random. The point here is that although you don’t get tested on everything, you might be, and therefore
the candidate needs the background knowledge in all areas.

## Sample Questions

-   Given **Orion** and a sensor of your choice, demonstrate how to provision and connect the IoT Agent of your choice.

This is generic enough to be answered using IDAS, FastRTPS or OpenMTC

-   Given **Orion** and an unconnected IoT Sensor, demonstrate how to connect an **IoT Agent** over MQTT <br/><br/>
-   Given **Orion** and an unconnected IoT Sensor, demonstrate how to connect an **IoT Agent** over the Things network
    <br/><br/>
-   Given **Orion** and a connected **IoT Agent** demonstrate how to persist data to CKAN <br/><br/>
-   Given **Orion** and a connected **IoT Agent** demonstrate how to persist data to HDFS <br/><br/>
-   Given **Orion** and a connected **IoT Agent** demonstrate how to persist data to a PostGRESQL database <br/><br/>
-   Given **Keyrock**, **Orion** and a connected **IoT Agent**, how can you secure the NGSI transactions behind a PEP
    Proxy? <br/><br/>
-   Given **Orion** and an **IoT Agent**, how would you obtain a timeline graph of sampled data?

This could be answered using Quantum Leap or STH-Comet

-   Given **Orion** and a connected **IoT Agent** persisting data to the database of your choice, demonstrate how to
    display a mashup visualization using the components of your choice

This could be answered using Wirecloud or Knowage

-   Demonstrate how to create and sell a working Widget with **Wirecloud** <br/><br/>
-   Given FIWARE system persisting the location of multiple entities, add a visualization to display those locations on
    a map <br/><br/>
-   Given **Orion** and **Cygnus** regularly persisting to database for multiple sensors, demonstrate how to obtain a
    visualization of an average-of-averages for those sensors <br/><br/>
-   Given **Orion** and **Cygnus** regularly persisting to database for multiple sensors, demonstrate how to ignore
    outliers on a visualization for those sensors <br/><br/>
-   Given a working FIWARE system demonstrate how expose a chargeable dataset to CKAN <br/><br/>
-   Given **Orion** and **Cygnus** regularly persisting to database, demonstrate how to raise an email once a threshold
    is reached.

Multiple Complex Event Processing answers are possible
