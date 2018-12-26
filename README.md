# Angular VirtualBox [DOWNLOAD](https://github.com/Virtual-Machines/Angular-VirtualBox/releases/download/latest/Angular.ova)

- Minimal Lubuntu 18.04.1 as a lightweight base (lubuntu-core package)
- VirtualBox Guest Additions (bidirectional clipboard between host and guest, shared folders capable, Seamless Mode...)
- Basic python http server included. Example: python3 -m http.server 4200
- StackBlitz, the online IDE, as webapp: https://stackblitz.com/fork/angular
- Chromium browser with Angular.io website and MyApp (localhost:4200) bookmarks
- Examples bookmark: https://github.com/Apress/pro-angular-6
- Chrome Debugger extension configured with Chromium browser (see launch.json)
- Visual Studio Code + Angular tutorial as bookmark: https://code.visualstudio.com/docs/nodejs/angular-tutorial
- npm (Nodejs included)
- Angular CLI globally installed (Angular 7): npm install -g @angular/cli
- Includes a sample project (my-app) created with: ng new my-app
- commands.txt: Useful general and Angular CLI commands
- NAT port forwarding configured on 4200 that allows web browser testing outside virtual machine executing this command:
ng serve --host 0.0.0.0
- Visual Studio Code with the sample project (my-app) opened
- Git
- Import OVA on VirtualBox using "File -> Import Appliance (or Control + I)"

![Desktop](https://github.com/Virtual-Machines/Angular-VirtualBox/blob/master/desktop.png)
![StackBlitz](https://github.com/Virtual-Machines/Angular-VirtualBox/blob/master/StackBlitz.png)
![Angular](https://github.com/Virtual-Machines/Angular-VirtualBox/blob/master/Angular.png)
![Visual Studio Code](https://github.com/Virtual-Machines/Angular-VirtualBox/blob/master/code.png)
![MyApp](https://github.com/Virtual-Machines/Angular-VirtualBox/blob/master/MyApp.png)
![Debugger](https://github.com/Virtual-Machines/Angular-VirtualBox/blob/master/debugger.png)
![LaunchJSON](https://github.com/Virtual-Machines/Angular-VirtualBox/blob/master/launchJSON.png)
