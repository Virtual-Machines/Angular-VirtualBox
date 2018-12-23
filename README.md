# Angular VirtualBox [DOWNLOAD](https://github.com/Virtual-Machines/Angular-VirtualBox/releases/download/latest/Angular.ova)

- Minimal Lubuntu 18.04.1 as a lightweight base (lubuntu-core package)
- VirtualBox Guest Additions (bidirectional clipboard between host and guest, shared folders capable, Seamless Mode...)
- Basic python http server included. Example: python3 -m http.server 4200
- Chromium browser with Angular.io website bookmark
- npm (Nodejs included)
- Angular CLI globally installed (Angular 7): npm install -g @angular/cli
- NAT port forwarding configured on 4200 that allows web browser testing outside virtual machine executing this command:
ng serve --host 0.0.0.0
- Visual Studio Code
- Git
- Import OVA on VirtualBox using "File -> Import Appliance (or Control + I)"

![Angular CLI version](https://github.com/Virtual-Machines/Angular-VirtualBox/blob/master/AngularCLI.png)
![Angular](https://github.com/Virtual-Machines/Angular-VirtualBox/blob/master/Angular.png)
![Visual Studio Code](https://github.com/Virtual-Machines/Angular-VirtualBox/blob/master/code.png)
