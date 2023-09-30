## Without [[JavaScript]]
1.  GET /form.php  (browser to Webserver)
2. Requested page is returned
3. User selects country, then clicks update button
4. GET /form.php?country=canada
5. Requested page (with updated form) is returned
6. User continues with form.....
![[Pasted image 20230920210303.png|400]]

## With JavaScript
1. Request
2. Response
3. After bowser receives a response to its HTTP request, it blanks the window, and
4. renders the  just-received HTML in the browser window
5. Request
6. Response
7. Another new Response has been received so the browser window is blanked and
8. renders the just-received HTML in the browser window
![[Pasted image 20230920210329.png|500]]
## [[Asynchronous Data Requests]]
![[Asynchronous Data Requests]]