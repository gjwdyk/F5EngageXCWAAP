# F5 Engage XC WAAP

<br><br><br>

## Re-Use Existing Objects for Class 2

Class 2: [F5 Distributed Cloud - WAF/WAAP Deeper Dive](https://clouddocs.f5.com/training/community/f5xc/html/class2/class2.html) uses the same HTTP Load Balancer, Origin Pool, and App Firewall objects as in Class 1, with some minor changes in the detailed configurations.



### Change the Origin Pool of the HTTP Load Balancer

Ensure you are on the `Web App & API Protection` service.
Click on the `Manage`, `Load Balancers` and `HTTP Load Balancers`.

![XCWAAPManageLBHTTP.png](XCWAAPManageLBHTTP.png)

On the row of `[namespace]-lb`, click on the `...` button and the click on the `Manage Configuration`.

![XCWAAPManageLBHTTPManage.png](XCWAAPManageLBHTTPManage.png)

On the top of the page, click `Edit Configuration` to enable us for modifications.

![XCWAAPManageLBHTTPManageEdit.png](XCWAAPManageLBHTTPManageEdit.png)

Scroll down to the ***Origin Pool with Weight and Priority***.
On the `Origin Pool` selection,

![XCWAAPManageLBHTTPManageEditOrigins.png](XCWAAPManageLBHTTPManageEditOrigins.png)

![XCWAAPManageLBHTTPManageEditOriginPool.png](XCWAAPManageLBHTTPManageEditOriginPool.png)

![XCWAAPManageLBHTTPManageEditOriginPoolResult.png](XCWAAPManageLBHTTPManageEditOriginPoolResult.png)

![XCWAAPManageLBHTTPManageEditSave.png](XCWAAPManageLBHTTPManageEditSave.png)



### Change the Application Firewall Configuration

![XCWAAPManageAppFW.png](XCWAAPManageAppFW.png)

![XCWAAPManageAppFWManage.png](XCWAAPManageAppFWManage.png)

![XCWAAPManageAppFWManageEdit.png](XCWAAPManageAppFWManageEdit.png)

![XCWAAPManageAppFWManageEditPolicy.png](XCWAAPManageAppFWManageEditPolicy.png)

![XCWAAPManageAppFWManageEditPolicyHML.png](XCWAAPManageAppFWManageEditPolicyHML.png)

![XCWAAPManageAppFWManageEditPolicyHMLSave.png](XCWAAPManageAppFWManageEditPolicyHMLSave.png)










<br><br><br>

***

<br><br><br>
```
╔═╦═════════════════╦═╗
╠═╬═════════════════╬═╣
║ ║ End of Document ║ ║
╠═╬═════════════════╬═╣
╚═╩═════════════════╩═╝
```
<br><br><br>


