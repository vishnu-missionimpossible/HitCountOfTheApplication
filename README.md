# HitCountOfTheApplication

JSP-01
Using application object scope, count the number of users hitting the application.
1. In the index.jsp file, firstly we set the attribute("hitcount",count) using application object and then we will get that attribute and check if it is null means we will make it to 1 otherwise we will increment.
2. This code will be written in the scriplet tag. After translation, it will sit in the _jspService(;;;) method.
3. The count variable here is local to this method and then after executing it will be pushed to context object.
4. since application or context object is available for all the files. we will get the value using experssion tag.
