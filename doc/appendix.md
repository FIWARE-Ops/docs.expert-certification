There follows a list of sample questions which may be asked during the examintion. Questions will be asked randomly for
each section. Depending on the time allocated to the examination, a candidate could be asked one or more questions from
each section list - chosen at random. The point here is that although you don’t get tested on everything, you might be,
and therefore the candidate needs the background knowledge in all areas.

## 1) Body-of-Work

<span/>

-   Briefly describe your current background in FIWARE.
-   Imagine you are applying for a job as a FIWARE Expert, how would you justify your application for the role.
-   In your opinion what is FIWARE?

## 2) Questions on NGSI interfaces

-   Where would you find the **temporal data** within an NGSI request/response?
-   How should **geographic data** be held within a NGSI request?
-   What forms of **filtering** are available within NGSI?
-   What NSGI operations are available beyond standard CRUD?
-   How do you update data using NGSI? What if you want to update all/part of the response?
-   What are the main differences between the **batch update** operations and **single update** operations?
-   How can I ensure that an **upsert** occurs? How is this done using single or batch requests?
-   What mechanisms exist to ensure **data integrity** within NGSI entities?
-   How does **pagination** work with NGSI? Is it able to work with registered data?
-   What is the difference between a **subscription** and a **registration**?
-   What are **subscriptions** used for? Give a practical example.
-   Describe a scenario when would you use the FIWARE **header** and **service path**.
-   What is the point of the **metadata** element?
-   What is the relationship between **metadata** in an NGSI entity and **linked data**?
-   What makes a good/poor candidate for a data entity?
-   What sort of items should be stored as attributes?
-   Are there advantage or disadvantages in using `Objects` as attribute data?
-   What sort of data should **not** be held within the Context Broker? How should such data be accessed instead?
-   Justify an example of a **subscription filtering on metadata** as opposed to attributes.
-   What are **registrations** used for? Give a practical example.
-   How do **registrations** work? Will the value received always be current?
-   What NGSI operations would be required to enforce **geofencing**? (i.e. raising an alert whenever a sensor/thing is
    detected out-of-bounds) How should the entities of such sensor data be structured?
-   What is the purpose of the `id` attribute? Does the `id` of each entity have to be unique? What is the purpose of
    the `type` attribute? When is it required?
-   Imagine I have a data structure including an address. How do I structure an entity so that I know that the street,
    the town etc. are known to be all part of one address?
-   Can you give an example of a geoquery? Can you describe the parameters you need to provide when defining a geoquery?
-   How do you convey in NGSI that an entity is associated (linked) to another entity?
-   What is NGSI-LD?

## 3) Questions on the Current FIWARE Catalogue

The main and only mandatory component of any “Powered by FIWARE” platform or solution is an NSGI compatible context
broker such as Orion. Usage of other components is optional and candidates may be more familiar with other external
components which are not within the current catalogue, however candidates are supposed to be aware of the catalogue
components on offer and the role they (or alternatives) would play within a FIWARE-based smart solution.

<h3>Catalogue questions – Core</h3>

-   What options do you have when **persisting** context data to a Database?
-   How would you go about displaying the last 30 minutes of values onto a Dashboard? Justify which components you would
    use and why?
-   How can you deal with **removing anomalous values** and outliers within persisted data?
-   Why would you want to include **static attributes** within your data entities?
-   How should you structure your context data to associate two separate entities to each other? What bearing does this
    have on your persisted data?
-   Is data held within the context broker current? Justify your answer.
-   If I am attempting to persist the state of a sensor via an IoT Agent and a subscription to Cygnus, how can I tell
    which part of the chain of components is not working? In other words, how could I check that data is arriving at all
    of the following:
    -   The IoT sensor
    -   The IoT Agent
    -   The Context Broker
    -   Cygnus
    -   The Database
-   Which catalogue components are able to respond to **subscriptions**?
-   How can I write a custom component that can respond to a subscription?
-   How is the **payload** of a subscription structured?
-   If I have a sensor with a fast-changing attribute, how would I go about adding a smoothed value as a second
    attribute of the same entity (e.g. an average value over the last 5 minutes)
-   What is the role of the FIWARE **service headers** as regards data persistence?
-   Under what circumstances are the FIWARE **service headers** unnecessary?
-   What will be the difference between the context data updated by a polling process and context data augmented by a
    registration?
-   What is the main advantage of using registrations?
-   What sort of data should not be added as context data?
-   Sometimes information can be associated to a context entity which is not directly part of the context – (e.g.
    images, complex database queries) – how should this be presented programmatically?
-   What is the difference between Short-Term-Historic and Persisted data?

<h3>Catalogue questions – IoT Agents</h3>

-   What is the role of an IoT Agent within the FIWARE Architecture?
-   Is an IoT Agent always required for interactions with sensors? If not, why not?
-   Describe your architectural reasoning for using **direct** device-to-Context Broker communication. (e.g. NGSI calls
    direct from a device)
-   Describe your architectural reasoning for using **indirect** device-to-Context Broker communication. (e.g. An IoT
    Agent reading ultralight over MQTT)
-   Which protocols and transports are currently supported by IoT Agents? What are your options if your sensor is using
    an unsupported protocol?
-   When would you use Edge processing? Which component(s) would you use? How does Edge processing differ from an IoT
    Agent?
-   If I wanted to change a raw temperature reading (°C) into a percentage within the context broker, how would I go
    about it

<h3>Catalogue questions – Visualization</h3>

-   What Visualization tools are available within the FIWARE Catalogue?
-   Under what circumstances would you prefer to use **Wirecloud** over **Knowage** (or vice-versa) – what are the
    perceived advantages of each?
-   What options are available if you wish to show the last 30 minutes of the geographical locations of GPS sensors?
-   How can I display a heatmap of sensor data? What sort of dataset is this useful for?
-   If I wish to create a dashboard to monitor short-term-historic data, do I need to use a catalogue visualization
    component? If yes, which would you recommend and why? If no, why not and what would you recommend instead?

<h3>Catalogue questions – Processing</h3>

-   How can you go about interpolating missing data using Big Data analysis?
-   What sort of context data can be obtained from image processing? Give an example of the components you could use.

<h3>Catalogue questions - Complex Event Processing</h3>

-   Which Complex Event processing components have you used and under which circumstances?
-   How would you split CEP business logic between a context broker subscription, CEP rules and a code within a bespoke
    component?
-   Given that you can already create subscriptions using Orion, why would a component need to subscribe via a CEP?
-   What is the role of a CEP? What does a CEP component do? What alternatives do you have?

<h3>Catalogue questions – Data Publication</h3>

-   How do you go about making your FIWARE data accessible to the public?
-   How can you ensure payment before exposing data?

<h3>Catalogue questions - Security</h3>

-   Describe the difference between **authorization** and **authentication** – which components are involved and why?
-   What is a **PDP** (Policy Decision Point) and how does it differ from a **PEP** (Policy Execution Point)?
-   What additional security scenarios are covered with the addition of a PDP (Policy Decision Point) such as
    Authzforce.
-   Which components are required for an **authentication**-based application?
-   Is it necessary to hold user identities within your own system if you are authenticating via OAuth2?
-   What is the role of a **PEP Proxy** such as Wilma? What does a PEP Proxy do?
-   Describe a situation where you may want to customize your PEP Proxy. How would you amend the existing catalogue
    component to do it?
-   What is **XACML**?
-   How do you secure data passing into the Context Broker?
-   How can you protect the integrity of data coming from sensors? In other words, ensuring is not being spoofed or data
    coming from one set of sensors is not polluted by data coming from another customer?

## 4) Questions on FIWARE Ready Devices

-   What testing needs to be done to certify a device as FIWARE Ready?
-   Are all devices using protocols which are supported by an IoT Agent FIWARE Ready?
-   If your device does not use a supported protocol what options do you have?

## 5) Architecture Scenarios

In the chosen scenario below, indicate which **catalogue components** you would use and justify their inclusion.
Describe the **data entities** you envisage within the system. What extensions could you think of which may add value:

1.  I run a cycling company where I have attached GPS devices to my bicycles which I rent out to tourists. I also offer
    a companion app on a mobile phone. My smart application should track the location of the bicycles and send a warning
    to the app if they go too far off the specified track. I can also calculate and offer statistics to be displayed
    such as route taken, calories burnt, distance travelled and so on. My smart solution will also receive weather
    information from a meteorological webservice. When it is going to rain, I want to send a message to the companion
    app to direct the tourists to a local bar or attraction to shelter. I have a negotiated a series of special offers
    with local businesses which are only available at certain times. Eventually I would also like to sell my crowd data
    back to the local tourist authority <br/><br/>
2.  I run a smart agriculture solution where I have a series of soil sensors which periodically check if the soil is too
    dry. Below a certain moisture threshold, a series of sprinklers are activated. I also check the local weather
    forecast web-service so that I won’t overwater the plants if it is going to rain later. Since I am successful at
    selling to many local farms, I also need to ensure that data from adjacent farmers fields is not accessible to each
    other when the farmer monitors their own fields on screen. My premium service needs to analyze (anonymized) data
    from all my monitored locations to simulate pesticide pollution run off into the local ecosystem. <br/><br/>
3.  My smart factory creates widgets and uses robots to help move the unfinished product from one processing machine to
    the next part of the production line. I have sensors reporting on the state of each processing machine. Some of the
    processing machines are manned, some are fully automatic. I wish to track the state and location of each robot and
    the availability of each processing machine to maximize throughput of my product. How can I analyze this data and
    work out efficiencies and implement preventive maintenance? How could I hook up the system to an existing stock
    management system? <br/><br/>
4.  My application determines the routes and maintenance schedule of garbage trucks throughout a city. The garbage
    trucks have GPS and capacity sensors. The city parks contain “smart bins” which indicate when they are full. I also
    monitor social media so citizens can tell the local authority when rubbish is piling up. My application needs to
    obtain data from all of these sources and schedule and monitor drivers so they can go to the appropriate locations.
    <br/><br/>
5.  I am running a regulated business where access is restricted to the various parts of the building using smart card
    readers. No business can be transacted after 8 p.m. and access to all areas must be denied after 9 p.m. (except for
    the security staff who can swipe in and out to patrol at night). How can I set up this system with various grades of
    user and also receive email alerts if an unauthorized user attempts to use their swipe card out of hours? I need to
    track and log the use of each card and hold the data in the long term and be able to track each user on screen as
    they pass through the building. I also wish to integrate the images from security cameras into my system. <br/><br/>
6.  I am running a fully automated unmanned parking business. Drivers sign-up to my service and drive up to the gate
    where a camera reads the number plate and raises the barrier to let the authorized driver in. On exit the user is
    automatically charged for the number of hours parked. I wish to incentivize use using variable pricing, so I need to
    track current space capacity.
