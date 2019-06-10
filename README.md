# Angular VirtualBox [DOWNLOAD](https://github.com/Virtual-Machines/Angular-VirtualBox/releases/download/latest/Angular.ova) - [VIDEO](https://www.youtube.com/watch?v=aUdBecaOeno)

Last update: 2019-06-10

![Desktop](https://raw.githubusercontent.com/Virtual-Machines/Angular-VirtualBox/master/desktop.png)
![StackBlitz](https://raw.githubusercontent.com/Virtual-Machines/Angular-VirtualBox/master/StackBlitz.png)
![Angular](https://raw.githubusercontent.com/Virtual-Machines/Angular-VirtualBox/master/Angular.png)
![Visual Studio Code](https://raw.githubusercontent.com/Virtual-Machines/Angular-VirtualBox/master/code.png)
![MyApp](https://raw.githubusercontent.com/Virtual-Machines/Angular-VirtualBox/master/MyApp.png)
![Debugger](https://raw.githubusercontent.com/Virtual-Machines/Angular-VirtualBox/master/debugger.png)
![LaunchJSON](https://raw.githubusercontent.com/Virtual-Machines/Angular-VirtualBox/master/launchJSON.png)
![TSLint](https://raw.githubusercontent.com/Virtual-Machines/Angular-VirtualBox/master/TSLint.png)

- Minimal Lubuntu 18.04.2 as a lightweight base (lubuntu-core package)
- Linux Kernel 4.18 HWE (Hardware Enablement)
- VirtualBox Guest Additions (bidirectional clipboard between host and guest, shared folders capable, Seamless Mode...)
- Basic python http server included. Example: python3 -m http.server 4200
- ⚡StackBlitz, the online IDE, as webapp: [https://stackblitz.com/fork/angular](https://stackblitz.com/fork/angular)
- Chromium browser with Angular.io website and MyApp (localhost:4200) bookmarks
- Examples bookmark: [https://github.com/Apress/pro-angular-6](https://github.com/Apress/pro-angular-6)
- Visual Studio Code + Angular tutorial as bookmark: [https://code.visualstudio.com/docs/nodejs/angular-tutorial](https://code.visualstudio.com/docs/nodejs/angular-tutorial)
- npm (Nodejs included)
- Angular CLI globally installed (Angular 8.0.2): npm install -g @angular/cli
- Includes a sample project (my-app) created with: ng new my-app
- commands.txt: Useful general and Angular CLI commands
- NAT port forwarding configured on 4200 that allows web browser testing outside virtual machine executing this command:
ng serve --host 0.0.0.0
- Visual Studio Code with the sample project (my-app) opened
- Chrome Debugger [https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) Extension configured with Chromium browser (see launch.json)
- TSLint code analyser: [https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin)
- Git (command line)
- User and pass of system is the same: **lubuntu**
- Import OVA on VirtualBox using "File -> Import Appliance (or Control + I)"

[**OPINION**](https://github.com/Virtual-Machines/Angular-VirtualBox/issues/1)
