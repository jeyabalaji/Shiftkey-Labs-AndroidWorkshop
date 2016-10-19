Goto https://wordpress.com

Click on Create a website.

Select a category from the list of avaialable categories for your webpage.

Select a layout and choose a theme.

Select a domain name and selcet free plan.

Create your own account.

Configure the Wordpress template according to your taste. (Play with it ;-))

Get the site link from Wordpress. This necessarily need not be in wordpress. 

Android part:

1. Open android studio

2. Enter a application name and click next

3. Select the minimum target sdk in which you application should be supported. and click next.

4. Select Empty activity and click next.

5. Dont change the activity name and click next. (If you are planning to change the activity name the initial content provider should be changed in all appropriate places. 

6. Click finish. 
**********************************************************************************
7. Open the project explorer on the top right corner of the and navigate to res>>layout>>activity_main.xml

8. Drag the webview component from the palette and place it on the main screen. 

9. Assign an ID for the newly dragged webview using the properties tab on the right side. 

10. Goto app>>java>>packagename>>MainActivity.java and open the file.

11. Create an object of type WebView.( WebView nameOfWebview; )

12. Declare the URL of the webpage as type String. ( String url = "https://www.yoursite.wordpress.com" )

13. Associate teh webview object to the actual webview in Xml file using findViewById(). ( wv = (WebView)findViewById(R.id.id_name); )

14. Use the additional settings that are available in the MainActivity.java file of this repo if needed. 

15. Load the the url to the webview using <webviewname>.loadUrl(<URL stirng>); 

16. Goto app>>manifests>>AndroidManifest.xml and open the file.

17. Add the internet permission after the </application> .
<uses-permission android:name="android.permission.INTERNET"/>

************************************************************************************************
