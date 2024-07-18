# NYTimesInterAssignment
Create a Utility package - where we create a base class and makes its abstarct that is been exyended by commonComponents class. In base class we initialize the Webdriver and others component, a method to Invoke different browsers, and use all TestNG annotation which describe what happens in beforeSuite or BeforeMethod.                  

In the same Utility package i have created common component class which will extend Base Class and created a method ByLocator that consist of different type of locators based on the use it will pick that type of locator and in this class we have created some generic method like capture screenshot, sendkeys, attachScreenshotToReport,clickOn etc.

In the same package - created a Common Utils class that consist of method to read the data from the excel file and create  method name as "getData()"

Also created a class for DataProviders call the method getData() and this methods pick the data from the excel file.
For the Reporting part I have used ExtentReports and implement ItestListner for reporting part , depending on test result outcome it will call that method 
