Neptune Cash NPT Miner v1.9 for HIVEOS

SUPPORTED GRAPHIC CARDS  
L40S  
RTX 6000 ADA  
A40  
RTX 6000  
RTX A5000 @ 220W ~6.50 MH/s (Core Clock Offset 200)  
RTX 5090 @ 580W ~39 MH/s  
RTX 5090 @ 450W ~30 MH/s  
RTX 4090 @ 450W ~21 MH/s  
RTX 4090 @ 280W ~16 MH/s  
RTX 3090 @ 320W ~9 MH/s (Core Clock Offset 150, Lock Core Clock 1740)

Video Tutorial: will be updated soon...

*****

HIVEOS: WALLET CREATION  
![wallet](https://github.com/gokyuzugokturk/igotek-npt/blob/main/img/wallet.png)

Dont get wallet address from https://safetrade.com ! 
Get wallet address from https://github.com/VxBlocks/vxb_neptune_wallet/releases/tag/v2.1.1  
Windows Wallet: NeptuneWallet_2.1.1_x64-setup.exe  
Dont enter your wallet address here.  
Set wallet address at the flight sheet !

*****

HIVEOS: FLIGHT SHEET  
![flighsheet_01](https://github.com/gokyuzugokturk/igotek-npt/blob/main/img/flighsheet_01.png)

*****

HIVEOS: FLIGHT SHEET  
![flighsheet_02](https://github.com/gokyuzugokturk/igotek-npt/blob/main/img/flighsheet_02.png)

Wallet and worker template: %WAL%  

Installation URL: [https://github.com/gokyuzugokturk/igotek-xnt-miner/releases/download/v1.0/xnt-1.0.tar.gz  ](https://github.com/gokyuzugokturk/igotek-npt-miner/releases/download/v1.9/neptune-1.9.tar.gz)

Pool URL: stratum+ssl://eu.poolhub.io:4444

Extra config arguments: --neptunewallet YOUR-WALLET-ADDRESS

This miner is for Neptune Cash NPT !  
Use XTN wallet address. Neptune Privacy (XTN) 

This miner is not for Neptune Privacy XTN !  
Dont use NPT wallet address. Neptune Cash (NPT) 

*****

BENCHMARKS

You can set overclock settings depends on your graphic card.   
Just try this ones as start and find the proper settings for your graphic cards.

RTX3090 > 9.05MH/s @ 300W  
Core Offset 150, Core Clock 1710, Lock Memory Clock 5000  
![RTX3090](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/004.png)

*****

Error Reporting:

Just lower Lock Core Clock value to lower if you see this error.  
You must enter 15 value lower.  
Example: set 1695 instead of 1710  
Example: set 1680 instead of 1695
![error](https://github.com/gokyuzugokturk/igotek-xnt/blob/main/img/error.png)

Sometimes, you can see your rig uses too lower power than usual, but the hashrates are good. that is an error.
You must lower Lock Core Clock to lower and reboot the rig to fix that error.

*****

Dev + Pool Fee: %10

*****

GPU Selection at the extra config: --gpu 0,1,2,3,4,5

*****

I m not the owner of the poolhub.io + I m not the developer of OXZD-0.7.5 + All fees goes to its developer ! The idle-time is on my hands. But you can set idle-time for your own choice ! You can edit the files, no restrictions. Just dont use the miner if you dont like it. Use it your own risk.

*****
