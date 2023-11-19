# WebSphere Liberty : Auto Scaling

![Websphere Liberty Logo](websphere.jpeg)

## Introduction

In this tutorial, the main objective is to showcase the procedure from Downloading WebSphere liberty to enabling the auto scaling feature in liberty. WebSphere liberty Network Deployment 23.0.0.9 is used in this tutorials as Liberty core and Liberty base doesnt support the auto scaling feature. If any error occur, visit the official [IBM documentation](https://www.ibm.com/docs/en/was-liberty/nd) page to find out more.

## Part 1 : Liberty Download
download  wlp-all-nd.jar and wlp-license.jar file from the passport advantage, ibm fix central website(in this tutorial will be using fix central) jmeter and java

extract the file usin command line or powershell using administartive mode to the path wanted. then extract the license file to the same location.

create a server named controller to act as a collective controller.(configuration, admin center)

advance setting enablle the setting to automatic, some port 445, control panel (windows) 

join a member locally
join a member remotely

clustering 
dymanic routing
auto scaling 
