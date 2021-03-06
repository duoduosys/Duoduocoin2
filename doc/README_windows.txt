﻿duoduo 1.0.0 BETA
Copyright (c) 2016 duoduo Developers

## End-User License Agreement

This agreement is between you (either an individual or a single entity) and the Duoduo developers. By installing, copy, or otherwise using the Duoduo software ("Duoduo"), you agree to be bound by the terms of this EULA. If you do not agree to the terms of this EULA, do not install or use the product.

### PRODUCT LICENSE
Duoduo is being distributed as Freeware for personal, commercial use, non-profit organization, educational purpose. It may be distributed freely on any website or through any other distribution mechanism, as long as no part of it is changed in any way.

This EULA grants you the following rights: 

Installation and Use. You may install and use an unlimited Duoduomber of copies of Duoduo.

Reproduction and Distribution. You may reproduce and distribute an unlimited Duoduomber of copies of Duoduo; provided that each copy shall be a true and complete copy, including all copyright and trademark notices, and shall be accompanied by a copy of this EULA. Copies of Duoduo may be distributed as a standalone product or included with your own product as long as Duoduo is not modified in any way.

Limitations on Reverse Engineering, Decompilation, Disassembly and change (add,delete or modify) the resources in the compiled the assembly. You may not reverse engineer, decompile, or disassemble Duoduo, except and only to the extent that such activity is expressly permitted by applicable law notwithstanding this limitation.

### LIMITED WARRANTY

NO WARRANTIES. The Authors of this Software expressly disclaims any warranty for Duoduo. Duoduo and any related documentation is provided “as is” without warranty of any kind, either express or implied, including, without limitation, the implied warranties or merchantability, fitness for a particular purpose, or non-infringement. The entire risk arising out of use or performance of Duoduo remains with you.

NO LIABILITY FOR DAMAGES. In no event shall the authors of this Software be liable for any special, consequential, incidental or indirect damages whatsoever (including, without limitation, damages for loss of business profits, business interruption, loss of business information, or any other pecuniary loss) arising out of the use of or inability to use this product, even if the Authors of this Software is aware of the possibility of such damages and known defects.

-----

# Setup
-----
After completing windows setup then run Duoduo.
Alternatively you can run windows command line (cmd) in Duoduo program dir.
  cd daemon
  Duoduod
You would need to create a configuration file Duoduo.conf in the default
wallet directory. Grant access to Duoduod/Duoduo in anti-virus and firewall
applications if necessary.

The software automatically finds other nodes to connect to.  You can
enable Universal Plug and Play (UPnP) with your router/firewall
or forward port 7890 (TCP) to your computer so you can receive
incoming connections.  Duoduo works without incoming connections,
but allowing incoming connections helps the Duoduo network.


Upgrade
-------
All your existing coins/transactions should be intact with the upgrade.
To upgrade, first backup wallet:
  Duoduod backupwallet <destination_backup_file>
Then shutdown the daemon with:
  Duoduod stop
Remove files inside wallet directory other than wallet.dat and Duoduo.conf
Start up the new client. It would start re-download of block chain.


See the documentation/wiki at the Duoduo website:
  http://www.Duoduobits.com
for help and more information.
