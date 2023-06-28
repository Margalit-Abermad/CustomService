# CustomService
create custom windows service

1. first- open a new windows service (.net framework) project 👇
   
![C# services](https://github.com/Margalit-Abermad/CustomService/assets/100418442/992c6705-eb56-4b5b-8c3a-47738a3048d2)

3. then write the code in the service1.cs file
4. save the project file and open the CMD in administrator
5. in the cmd navigate to 👉 cd C:\Windows\Microsoft.NET\Framework\v4.0.30319 
6. put this command but change it to youre parameters-
  ### Syntax

### InstallUtil.exe + Your copied path + \your service name + .exe

 by example, my command was- InstallUtil.exe C:\Users\user\Music\WindowsService\WindowsService\bin\Debug\WindowsService.exe

 6. run the command in the CMD
 7. that what you will get after the running 👇 :
    
    ![cmd Service](https://github.com/Margalit-Abermad/CustomService/assets/100418442/dd7d13f0-28a4-47b6-bb60-da6ccb3b4f4c)
    
9. open your all services in Windows+R :
   
   ![windows+r](https://github.com/Margalit-Abermad/CustomService/assets/100418442/9181cddc-911e-464f-96be-45ea7138420b)
10. find youre custom service
11. you also uninstall service-

If you want to uninstall your service, fire the below command.

Syntax InstallUtil.exe -u + Your copied path + \your service name + .exe
Our path InstallUtil.exe -u C:\Users\Faisal-Pathan\source\repos\MyFirstService\MyFirstService\bin\Debug\MyFirstService.exe


more details- https://www.c-sharpcorner.com/article/create-windows-services-in-c-sharp/
