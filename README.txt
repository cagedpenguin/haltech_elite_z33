* DISCLAIMER
This is not meant to be a true daily map. It is meant to be a 
map you can use until you get it professionally tuned.
I take no responsibility if you play with this map and self tune
your car and it blows up.

* WHY
There is a Pro Platinum map for the Z33. 
I am copying as much of that as possible and converting it
for the haltech elite 2500.
It's sad there is no proper base map for the Z33 in the NSP software
so I'm trying to make one.

This is a base map that should work similar 
as the stock ECU, but, based on VE. 

Since the 03 and early 04 did not have a wideband, 
I wanted a self correcting ECU based on accurate wideband data.

* SETUP
1. Haltech WB2 kit installed in the bungs closest to the headers.
2. Boomslang Z33 PnP harness
3. Haltech elite 2500

* LINKS
https://support.haltech.com/portal/en/kb/articles/vq35de-engine?gad_source=1&gad_campaignid=20930836765&gclid=EAIaIQobChMIyeGM_53ljgMVdFJ_AB3d8ysqEAAYASAAEgJK0fD_BwE

* ISSUES - 20250804
1. slip light on
2. VDC switch doesn't work.

* BETA - 20250804
This map, after you train the throttle does let you drive to the tuners. Just keep it under 4k rpms.

* DEV - 20250804
This map is more of a clean up, This map is for a NA VQ35DE. This one is meant to replace the BETA map once
I get enough logs showing the stability of the changes. 
For example, 
The NSP base map makes 3D grids for atmospheric pressure between -29 and +29 and up to 10k rpms.
The VQ35DE doesn't need such huge grids for tuning, so cutting them down to up to 2.9 atmospheric and 8k rpms should be good enough.