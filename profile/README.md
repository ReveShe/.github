# ReveShe
ReveShe will be a reverse shell application for remote help.  
Person that needs help will download a preconfigured executable file - listener, that will connect to a ReveShe server.  
Person that provides help will either download a controller app, or use web-based controller on the ReveShe server.  
Listener executes commands comming from the server, pushed there by the controllers.  
Controller can request privilege escallation, which has to be allowed or declined by the user of listener.  

Planned platforms supported: Linux x64 (listener, controller, server), Windows x64 (listener)
