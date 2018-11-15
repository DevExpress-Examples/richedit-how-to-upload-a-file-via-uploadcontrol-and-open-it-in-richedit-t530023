<!-- default file list -->
*Files to look at*:

* [HomeController.cs](./CS/T530023/Controllers/HomeController.cs)
* [UploadControlValidationSettings.cs](./CS/T530023/Models/UploadControlValidationSettings.cs)
* [_CallbackPanelPartial.cshtml](./CS/T530023/Views/Home/_CallbackPanelPartial.cshtml)
* [_RichEditPartial.cshtml](./CS/T530023/Views/Home/_RichEditPartial.cshtml)
* **[Index.cshtml](./CS/T530023/Views/Home/Index.cshtml)**
<!-- default file list end -->
# RichEdit - How to upload a file via UploadControl and open it in RichEdit


This example demonstrates how to upload a document by using our UploadControl and show this file content in RichEdit once it's uploaded.<br><br>To accomplish such a task, put the RichEdit extension in the <a href="https://documentation.devexpress.com/#AspNet/CustomDocument9000">CallbackPanel</a> container and use its callbacks to open the uploaded file by using the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebMvcRichEditExtension_Opentopic">RichEditExtension.Open</a> method.

<br/>


