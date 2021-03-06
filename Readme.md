<!-- default file list -->
*Files to look at*:

* [CustomDashboardStorage.cs](./CS/CustomDashboardStorage.cs) (VB: [CustomDashboardStorage.vb](./VB/CustomDashboardStorage.vb))
* [DashboardStorageDataSet.cs](./CS/DashboardStorageDataSet.cs) (VB: [DashboardStorageDataSet.vb](./VB/DashboardStorageDataSet.vb))
* [WebForm1.aspx](./CS/WebForm1.aspx) (VB: [WebForm1.aspx](./VB/WebForm1.aspx))
* [WebForm1.aspx.cs](./CS/WebForm1.aspx.cs) (VB: [WebForm1.aspx.vb](./VB/WebForm1.aspx.vb))
<!-- default file list end -->
# ASPxDashboard - How to save dashboards created by end-users to a DataSet


<p>The following example shows how to create a custom dashboard storage for <a href="https://documentation.devexpress.com/#Dashboard/clsDevExpressDashboardWebASPxDashboardtopic">ASPxDashboard</a> by implementing the <a href="https://documentation.devexpress.com/#Dashboard/clsDevExpressDashboardWebIEditableDashboardStoragetopic">IEditableDashboardStorage</a> interface. In this example, a <a href="https://msdn.microsoft.com/en-us/library/system.data.dataset(v=vs.110).aspx">DataSet</a> is used as an in-memory storage of dashboards. This DataSet can be used later to save dashboards in the database using <a href="https://msdn.microsoft.com/en-us/library/system.data.common.dataadapter(v=vs.110).aspx">DataAdapter</a>.<br>See also: <a href="https://www.devexpress.com/Support/Center/Example/Details/T386418">ASPxDashboard - How to save dashboards to a database</a></p>

<br/>


