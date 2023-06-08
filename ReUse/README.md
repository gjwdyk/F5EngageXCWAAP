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

On the top of the page, click `Edit Configuration` to enable for modifications.

![XCWAAPManageLBHTTPManageEdit.png](XCWAAPManageLBHTTPManageEdit.png)

Scroll down to the ***Origins*** section.
On the row of ***Origin Pool***, click on the ***Pencil*** button.

![XCWAAPManageLBHTTPManageEditOrigins.png](XCWAAPManageLBHTTPManageEditOrigins.png)

On the ***Origin Pool with Weight and Priority*** section/page, click on the `Origin Pool` selection, and select `[namespace]/[namespace]-pool`.
Click on `Apply` on the bottom of the page.

![XCWAAPManageLBHTTPManageEditOriginPool.png](XCWAAPManageLBHTTPManageEditOriginPool.png)

After the above step, the ***Origin Pools*** should look similar to below.

![XCWAAPManageLBHTTPManageEditOriginPoolResult.png](XCWAAPManageLBHTTPManageEditOriginPoolResult.png)

Scroll to the bottom of the ***HTTP LB Configuration*** page and click `Save and Exit`.

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


