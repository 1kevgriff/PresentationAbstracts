#Scalable SignalR Applications

All great SignalR demos and presentations show you how easy it is to build an application
where server and client communication can happen in real-time.  What they never show you
is how to handle cases where your SignalR application is running across multiple servers.
In the cloud connected world, our servers can span across one or one million servers.  Out
of box, SignalR is not configured to handle this scenario.  Scaling an out of the box SignalR
application will result in lost messages and confused users.

In this presentation, Kevin Griffin will show you the issues with running SignalR in the cloud
and how to design an infrastrure that will support multiple SignalR instances.  We'll cover 
architectural considerations that need to be made outside of your application, and then how
with a couple lines of code your application will be "cloud-proof".
