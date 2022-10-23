# CMPG-323-Project-4-34875255
UIPath
Main folder project is CMPG-323-Project-4-34875255 Connected Office Web Application User Acceptance Testing
Project Consist of the following main Tasks/Flows

![image](https://user-images.githubusercontent.com/89706817/197419826-a1ae8fc0-55e8-436b-b316-235932cb74c4.png)

* Access Website

* Login - where if the login fails the process will then register an account and then login, if the website is already logged in then the bot will log out and login again to make sure it is the correct account.

* TestZone - this is where the bot will access the excel file and get the zone test data. whereafter it will enter the data, edit the data, and delete the data. if the processes are successful, it will report it in the result tab in the excel file.

![image](https://user-images.githubusercontent.com/89706817/197419841-9c03e111-f596-41a6-804d-cd4115be6f0e.png)

* Test Category -This is the same process as TestZone only with category information - create, edit and delete
* EnterData - this process enters all the test data into the website. So, in turn TestDevice can be executed.
* TestDevice - Bot open excel file and get device data then adds, edit and delete devices one by one, testing all endpoint.
* DeleteData - Bot removes all data from categories and zones leaving the database clean.

![image](https://user-images.githubusercontent.com/89706817/197419970-8bb55456-1db1-437d-b6d3-a4dbae5dad3e.png)

* Logout - the bot logs out of website and closes the Browser/Tab

# References
https://www.youtube.com/watch?v=wk2PBLU3mg0 - login to website <br />
https://www.youtube.com/watch?v=5etuXQR42f8 - open/write Excel file <br />
https://www.youtube.com/watch?v=boIOgO2-OBk - For Each Loops <br />
https://docs.uipath.com/activities/docs/read-write-and-append-data-in-excel <br />
https://docs.uipath.com/activities/docs/n-application-card <br />
https://forum.uipath.com/t/using-an-excel-application-scope-through-invoked-workflows/154556/3 <br />
https://www.uipath.com/learning/video-tutorials/project-organization <br />
https://forum.uipath.com/t/how-to-escape-from-inner-loop-to-outer/138720 <br />
https://www.youtube.com/watch?v=SXC9WYFQR2w - Breakpoints and debuging <br />
https://docs.uipath.com/activities/docs/read-from-excel-files <br />
https://forum.uipath.com/t/passing-variable-to-another-workflow/182411/7 <br />
https://forum.uipath.com/t/how-to-exit-for-each-loop/196664/6 <br />
https://forum.uipath.com/t/write-cell-for-every-row-while-looping-for-each-row/107964 <br />
https://forum.uipath.com/t/for-each-row-in-column-a-insert-some-value/385756 <br />
https://forum.uipath.com/t/read-and-write-to-excel-for-each-row/283906/4 <br />
https://forum.uipath.com/t/write-cell-for-every-row-while-looping-for-each-row/107964/12 <br />
https://docs.uipath.com/activities/docs/excel-for-each-row <br />
https://docs.uipath.com/activities/docs/n-for-each-ui-element <br />
https://forum.uipath.com/t/recognize-each-ui-element-in-chrome-and-click-on-it-one-after-the-other/420992/7 <br />
https://forum.uipath.com/t/signing-out-from-the-chrome/104520 <br />
https://forum.uipath.com/t/how-to-close-the-browser-in-reframework-using-modern-activities/402251 <br />
https://forum.uipath.com/t/visualbasicvalue-boolean-object-reference-not-setto-an-instance-of-an-object/293840/2 <br />
