
                      88                                                                                                 88                        
                      88                                   ,d                                                      ,d    ""   
                      88                                   88                                                      88 
,adPPYba, 88       88 88,dPPYba,  8b,dPPYba,   ,adPPYba, MM88MMM    8b,dPPYba,  8b,dPPYba, ,adPPYYba,  ,adPPYba, MM88MMM 88  ,adPPYba,  
I8[    "" 88       88 88P'    "8a 88P'   `"8a a8P_____88   88       88P'    "8a 88P'   "Y8 ""     `Y8 a8"     ""   88    88 a8"     "" 
 `"Y8ba,  88       88 88       d8 88       88 8PP"""""""   88       88       d8 88         ,adPPPPP88 8b           88    88 8b         
aa    ]8I "8a,   ,a88 88b,   ,a8" 88       88 "8b,   ,aa   88,      88b,   ,a8" 88         88,    ,88 "8a,   ,aa   88,   88 "8a,   ,aa 
`"YbbdP"'  `"YbbdP'Y8 8Y"Ybbd8"'  88       88  `"Ybbd8"'   "Y888    88`YbbdP"'  88         `"8bbdP"Y8  `"Ybbd8"'   "Y888 88  `"Ybbd8"'  
                                                                    88
                                                                    88
                                                                  

Subnet practice is a game i created learning python. I used tehmaze ipcalc rather than recreate the wheel.

ipcalc can be found here https://pypi.org/project/ipcalc/#files or at https://github.com/tehmaze/ipcalc.

Subnet Practice will attempt to install ipcalc with pip if not present on the local machine.

It will create a random ipv4 address and subnet mask and ask you for subnet mask, network class, network ID, First host in range and last and broadcast. It will ask you how many hosts in total and how many subnets.

Can add plenty more features and further subnetting rules for private 172.16.0.0/12 an apipa 169 and loopback 172.0.0.1 and more etc.

Currently only added logic to ensure that if you have a class B it does not give you a subnet mask below a /16. Same for class C to ensure not below a /24.

When i have the time i will add more features and quizes to it. Feel free to log incidents and contribute and better the code.
