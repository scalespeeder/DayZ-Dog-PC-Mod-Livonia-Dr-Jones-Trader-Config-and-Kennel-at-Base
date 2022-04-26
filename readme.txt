DayZ 1.17  DayZ Dog Kennel At Scalespeeder Livonia (Enoch) Trader & New "Pet Supplies" Category For Use With Dr Jones Trader

THESE FILES AND CODE SNIPPETS ARE ASSOCIATED WITH SCALESPEEDERS LIVONIA TRADER FOR DR JONES TRADER, SEE: https://github.com/scalespeeder/DayZ-Dr-Jones-Trader-Mod-Livonia-Trader-Objects-File-For-Base-SE-Of-Zapadlisko

Trader is at 8728.16 / 8076.48, South East of Zapidlisko.

THESE ARE THE TEXT SNIPPETS FOR THOSE THAT WOULD LIKE TO MODIFY THEIR OWN TRADER CONFIG FILES,
PROBABLY BEACAUSE YOU HAVE OTHER MODDED ITEMS ALREADY INCLUDED, OR DAYZ HAS MOVED BEYOND 1.7.

(HOWEVER, IF YOU ARE RUNNING A VANILLA 1.17 DR JONES TRADER MOD, SIMPLY UPLOAD THE TraderConfig.txt & TraderObjects.txt
FILES TO YOUR TRADER CONFIG / PROFILES FOLDER ON YOUR SERVER.)

MANY THANKS TO DR JONES!

YOU MUST HAVE DR JONES TRADER AND DAYZ DOG MODS INSTALLED AND WORKING FOR THESE EDITS TO WORK!

PLEASE NOTE THAT NOT ALL SURVIVORS CAN "CALL" A DOG FROM A KENNEL. IF STILL SO AFTER A RESTART THAT SURVIVOR WILL
PROBABLY ONLY BE ABLE TO "CALL" A DOG ON THEIR NEXT LIFE.

ADD THIS TO THE SECOND HALF OF TRADEROBJECTS.TXT, BELOW // Zapadlisko SE:

<Object> dog_shed_small_static
<ObjectPosition> 8704.6396484375,                289.0150146484375,                8085.81982421875
<ObjectOrientation> 108.03900146484375,                0.0,                0.0


save (and upload if necessary) to trader config folder on your server (inside the server profile / config / settings folder)

ADD THESE TO TraderConfig.txt BELOW THE LAST ENTRY IN <Category> Hardware Supplies:

<Category> Pet Supplies
		dog_shed_small_kit,		*,		20,		-1
		dog_shed_wooden_kit,	*,		50,		-1
		dog_shed_big_kit,		*,		100,	-1
		dog_bowl,				*,		10,		-1
		dog_bone_toy,			*,		10,		-1
		
save (and upload if necessary) to trader config folder on your server (inside the server profile / config / settings folder)

Please report any bugs to scalespeeder@gmail.com

Thanks and enjoy!