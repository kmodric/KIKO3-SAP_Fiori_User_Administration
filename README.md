# KIKO3: SAP Fiori User Administration
SAP Fiori app for unlocking & locking users, changing password and setting validity date

![image](https://github.com/kmodric/KIKO3-SAP_Fiori_User_Administration/assets/6062110/600d02f2-eea9-4ac8-94b7-0d17a204e45e)


Please check video on youtube for more information about Fiori application:
<br/>
https://youtu.be/qH72wRDTuBw
<br/><br/>
UPDATE from:
<br/>
https://blogs.sap.com/2016/08/16/build-your-own-sap-fiori-app-in-the-cloud-2016-edition/
<br/><br/>
Short instruction for installation:
<br/>
Note: under /bin there is zip file:kiko3_tr.zip containing needed TR (Transport Requests)

1.	Import TR S4HK902314 (ZKIKO3 - Fiori app (user administration))
2.	Import TR S4HK902315 (ZKIKO3 - add system alias)
3.	/n/IWFND/MAINT_SERVICE -> ICF Node -> Activate for: 
     <p>ZKIKO111_SRV
     <p>ZTEST1_SRV
     <p>ZTEST2_SRV
     <p>ZTEST5_SRV
     <p>ZTEST61_SRV
     <p>ZTEST62_SRV
     <p>ZTEST7_SRV
<p>
  4.	SICF – need manual activation of sapui5 services: zkiko3, zkiko31, zunlockuser (Path: /default_host/sap/bc/ui5_ui5/sap/)
  <p>
  5.	Test application: zkiko3, zkiko31, zunlockuser
    <p>
  URL is in format: http(s)://&lt;hostname:port&gt;/sap/bc/ui5_ui5/sap/zkiko31/index.html?sap-client=&lt;xxx&gt;
<br/><br/>
<br/><br/>
  Installed app:
      <br/>
1.	ZUNLOCKUSER
<p>http(s)://&lt;hostname:port&gt;/sap/bc/ui5_ui5/sap/zunlockuser/index.html?sap-client=&lt;xxx&gt;
<p>Only for Unlocking user
 
![image](https://github.com/kmodric/KIKO3-SAP_Fiori_User_Administration/assets/6062110/23f4ab68-8c5d-485b-9668-4c3c24e1169d)

<br/>
2.	ZKIKO3
<p>http(s)://&lt;hostname:port&gt;/sap/bc/ui5_ui5/sap/zkiko3/index.html?sap-client=&lt;xxx&gt;
<p>For Unlocking user and changing password

![image](https://github.com/kmodric/KIKO3-SAP_Fiori_User_Administration/assets/6062110/f8f056f4-b8d2-4528-a4ac-a5aa1896f216)

<br/>
3.	ZKIKO31
<p>http(s)://&lt;hostname:port&gt;/sap/bc/ui5_ui5/sap/zkiko31/index.html?sap-client=&lt;xxx&gt;
<p>For unlocking & locking users, changing password and setting validity dates 

![image](https://github.com/kmodric/KIKO3-SAP_Fiori_User_Administration/assets/6062110/ac497568-14b7-4420-848c-8baf8f8c3d9b)






