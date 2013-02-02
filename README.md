PersianDatePicker_ASP.NET_MVC
=============================

Persian Date Picker Template for ASP.NET MVC projects

This project helps you to integrate Persian Date Picker with ASP.NET MVC projects. By using it you can 
have your field in DateTime format in database, then show and edit it in Persian Date format. 

How to use:

1. Copy required js files to script directory:

    jquery.ui.datepicker-cc.all.min.js 

    modernizr-2.0.6-development-only.js

    jquery-1.8.3.min.js

2. Copy "PersianDatePicker.css" and "images" folder to the Content folder.

3. Use PersianDateExtension Class.

3. Copy EditorTemplates and DisplayTemplates folders to the "Shared" folder in "Views".

4. Add [UIHint("PersianDate")] above of your DateTime field.

5. Use @Html.EditorFor for your DateTime field to use the DatePicker.
