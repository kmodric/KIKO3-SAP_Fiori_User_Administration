# KIKO3: SAP Fiori User Administration
SAP Fiori app for unlocking & locking users, changing password and setting validity dates 

https://youtu.be/qH72wRDTuBw

UPDATE from:
https://blogs.sap.com/2016/08/16/build-your-own-sap-fiori-app-in-the-cloud-2016-edition/

Short instruction for installation:
Note: under /bin there is zip file:kiko3_tr.zip containing needed TR (Transport Requests)

1.	Import TR S4HK902314 (ZKIKO3 - Fiori app (user administration))
2.	Import TR S4HK902315 (ZKIKO3 - add system alias)
3.	/n/IWFND/MAINT_SERVICE -> ICF Node -> Activate for: 
ZKIKO111_SRV
ZTEST1_SRV
ZTEST2_SRV
ZTEST5_SRV
ZTEST61_SRV
ZTEST62_SRV
ZTEST7_SRV
4.	SICF – need manual activation of sapui5 services: zkiko3, zkiko31, zunlockuser (Path: /default_host/sap/bc/ui5_ui5/sap/)
5.	Test application: zkiko3, zkiko31, zunlockuser
