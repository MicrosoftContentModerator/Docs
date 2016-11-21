# Using Postman to run the Review API #

Click this button to run Review API using Postman:
 
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/0fec61b7259fdee26c6c#?env%5BReview%20API%5D=W3sia2V5IjoiQUROYW1lc3BhY2UiLCJ2YWx1ZSI6ImNvbnRlbnRtb2RlcmF0b3Jwcm9kIiwidHlwZSI6InRleHQiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IkFEUmVzb3VyY2UiLCJ2YWx1ZSI6Imh0dHBzOi8vYXBpLmNvbnRlbnRtb2RlcmF0b3IuY29nbml0aXZlLm1pY3Jvc29mdC5jb20vcmV2aWV3IiwidHlwZSI6InRleHQiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IkFEQ2xpZW50SWQiLCJ2YWx1ZSI6IjxZb3VyIENsaWVudCBJZD4iLCJ0eXBlIjoidGV4dCIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiQURDbGllbnRTZWNyZXQiLCJ2YWx1ZSI6IjxZb3VyIENsaWVudCBTZWNyZXQ+IiwidHlwZSI6InRleHQiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6Ik9jcC1BcGltLVN1YnNjcmlwdGlvbi1LZXkiLCJ2YWx1ZSI6IjxZb3VyIE1vZGVyYXRvciBTdWJzY3JpcHRpb24gS2V5PiIsInR5cGUiOiJ0ZXh0IiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJSZXZpZXdUZWFtIiwidmFsdWUiOiI8WW91ciBUZWFtIE5hbWU+IiwidHlwZSI6InRleHQiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IkFQSUJhc2VVcmwiLCJ2YWx1ZSI6Imh0dHBzOi8vd2VzdHVzLmFwaS5jb2duaXRpdmUubWljcm9zb2Z0LmNvbS9jb250ZW50bW9kZXJhdG9yIiwidHlwZSI6InRleHQiLCJlbmFibGVkIjp0cnVlfV0=)

Once imported you will see all  the Review APIs listed like in the screenshot below:
![](http://i.imgur.com/M3bdMTf.png)


## Updating Environment Variables ##
You now need to update the environment variables to set your Team credentials.

1. Click on the eye icon you reveal the environment settings
   ![](http://i.imgur.com/bLoSHdn.png)

2. Click on Edit
   ![Updating Environment Variable](http://i.imgur.com/7Lg2eR6.png)
3. We need to replace the highlighted values with values for your team. You will get these values on the Settings > API section.
	1. Navigate to https://contentmoderator.cognitive.microsoft.com
	2. Click on Settings
	3. Click on API
	4. Copy the Client Id ![Copy Client Id](http://i.imgur.com/szjhev8.png)
	5. If you don't already have a Client Secret, then create one by clicking on the **Create Credentials** button
	6. Copy the value of the Client Secret that you just created.
	7. Now, scroll down the page and click on the Edit button for the Moderator API connector. ![Moderator Subscription Key](http://i.imgur.com/cBYqISL.png)
	8. Copy the subscriptionkey

You are now ready to use Postman for making calls to the Review API.


## Let me walk you through creating a Review ##
The Review that we create using the API will show up in the Review tab for the reviewers.

1. Select the **Generate AD Token** method![Get Ad Key](http://i.imgur.com/ojLzWbF.png)
2. Once you get a successful response creating the AD token, now select the **Create Review** method and hit send. ![Create Review method selected](http://i.imgur.com/ubpz2JZ.png)

If you get a successful response, then your Review was successfully created!!

You can now navigate to the Review Tool to view the Review that you just created.







