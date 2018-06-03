#Simple steps to get information form url and show it in HTML page

1. Create XHR object.
2. Call XHR.open() method to GET the URL.
3. Send the request.
4. When XHR Ready State change call a process funtion.
5. Ceate process function that do:
	5.1. Check if the XHR Ready state is DONE and XHR Status OK.
	5.2. Parse XHR reponseText.
	5.3. Call a function to show some information from reponseText in HTML page.
6. Create a function to show data in HTML page:
	6.1. Get body element.
	6.2. Create a new element.
	6.3. Append our new element to body element.
