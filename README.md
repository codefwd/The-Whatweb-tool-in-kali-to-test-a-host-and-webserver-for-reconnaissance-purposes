
# The whatweb tool in kali to test a host and webserver for reconnaissance purposes
Majority of targets to test will be webservers - Whatweb is a good tool for reconnaissance.
## Overview: We will use whatweb to gather information from my metasploitable VM and a public test server out on the internet.

First, I searched and chose whatweb

<img width="569" height="220" alt="1" src="https://github.com/user-attachments/assets/7247d0b7-298a-4c87-ba69-c7c2317bdfa9" />

You can see the many options whatweb offers and that's not all. Many more followed, but the screen shot doesn't show everything.

<img width="675" height="730" alt="2" src="https://github.com/user-attachments/assets/7d2b8f01-e389-4245-80a8-e4f3dd405a15" />

The first thing I want to look at is my metasploitable VM with the address 10.0.2.5:

<img width="179" height="43" alt="3" src="https://github.com/user-attachments/assets/412fc28e-e9a8-45e1-aeb9-a9aa6ee95d22" />

Some of the info given is that it's running on an Apache server [2.2.8] running PHP [5.2.4] and the title shows [metasploitable]

<img width="1600" height="48" alt="4" src="https://github.com/user-attachments/assets/35b3d1b0-c8a1-435a-bb71-edcdb9a9d7e6" />

We will now look at a public test server out on the internet to see what information it gives.


<img width="375" height="53" alt="5" src="https://github.com/user-attachments/assets/ec907912-be39-4fd8-88e5-6fb1e4d8f1e0" />


The information we get back shows an [Apache-Coyote/1.1], JQuery[1.8.2] and the title [Zero - Personal banking - loans - credit cards]

<img width="1625" height="70" alt="6" src="https://github.com/user-attachments/assets/def4ee82-e50a-4690-ba3c-993e008f221b" />



**In conclusion, the whatweb tool in Kali Linux is a valuable reconnaissance utility used to get information on hosts and/or web servers.**


