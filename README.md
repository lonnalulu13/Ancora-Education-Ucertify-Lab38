# Ancora-Education-Ucertify-Lab38
Configuring Inbound Rules for a Firewall

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=4]

## Objective of the Lab
In this lab, you will learn to configure inbound rules for a firewall. The Windows firewall offers four types of rules: Program, Port, Predefined, or Custom. Inbound rules allow any program that listens on a specified TCP or UDP port to receive network traffic sent to that port.
## Instruction
### STEP 1
On the taskbar, in the Search text box, type windows firewall, and click Windows Defender Firewall. 
### STEP 2 
In the Windows Defender Firewall window, click Advanced settings. 
### STEP 3 
In the Windows Defender Firewall with Advanced Security window, in the left pane, select Inbound Rules. 
### STEP 4 
In the right pane, under Inbound Rules, select New Rule. 
### STEP 5 
In the New Inbound Rule Wizard window, perform the following steps: 

a.At the Rule Type step, select Port and click Next. 

b.At the Protocol and Ports step, in the Specific local ports text box, type 81 and click Next.

c.At the Action step, verify that Allow the connection is selected and click Next. 

d.At the Profile step, verify Domain, Private, and Public are checked and click Next.

e.At the Name step, in the Name text box, type Open Port 81 and click Finish.

## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
