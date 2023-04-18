# BAO

A system of three mobile applications to make it easier for individuals to find reliable and qualified service providers.

## Description

 **1. Components**
 
The system consists of :
 - [ ] [<ins>Data</ins>](data) : a RestFull API to distribute information to the various other components and to collect their information.
 - [ ] [<ins>Mobile admin</ins>](mobile/admin) : a mobile application to allow administrators to manage and watch the whole system.
 - [ ] [<ins>Mobile customer</ins>](mobile/customer) : a mobile application to allow individuals to share thier needs and select technician among a list of application
 - [ ] [<ins>Mobile technician</ins>](mobile/technician) : a mobile application to allow services providers to consult the needs of individuals and apply
 
 **2. Conception**

 - [ ] [<ins>Data</ins>](data) : PHP application built with Laravel
 - [ ] [<ins>Mobile admin</ins>](mobile/admin) : built with Dart and Flutter with a custom library based on dart
 - [ ] [<ins>Mobile customer</ins>](mobile/customer) : built with Dart and Flutter with a custom library based on dart
 - [ ] [<ins>Mobile technician</ins>](mobile/technician) : built with Dart and Flutter with a custom library based on dart
 
 ## Get started
 
 **1. <ins>Setup `data` and database</ins>**
 
 Setup [<ins>data</ins>](data) and generate database using Laravel Eloquent ORM or using [<ins>db directory files</ins>](db)
 
 **2. <ins>Deploy `mobile`</ins>**
 
 Setup mobiles [<ins>admin</ins>](mobile/admin), [<ins>customer</ins>](mobile/customer), [<ins>technician</ins>](mobile/technician) application and set http links in config files to connect it with [<ins>data</ins>](data) ([<ins>admin config file</ins>](mobile/admin/lib/datas/request/endpoint.dart), [<ins>customer config file</ins>](mobile/customer/lib/datas/request/endpoint.dart) and [<ins>technician config file</ins>](mobile/technician/lib/datas/request/endpoint.dart)).
