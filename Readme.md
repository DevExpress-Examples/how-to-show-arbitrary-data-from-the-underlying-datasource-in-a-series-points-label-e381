<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
<!-- default file list end -->
# How to show arbitrary data from the underlying datasource in a series point's label


<p>This example demonstrates how to display custom data in a series point's label. To accomplish this task, it is necessary to handle the <strong>CustomDrawSeriesPoint</strong> event, then obtain any data field via the <strong>e.SeriesPoint.Tag</strong> property, and assign a custom string to the <strong>e.LabelText</strong> value.</p>

<br/>


