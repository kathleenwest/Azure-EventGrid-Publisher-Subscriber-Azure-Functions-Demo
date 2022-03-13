# Azure Event Grid Demo: Publish (Postman) and Subscriber (Azure Function)
In this project, we will create an Event Grid Topic in Azure for a publish-subscribe demo. Our subscriber will be an Azure function that is triggered by an event published to the Event Grid Topic. We will create the Azure function app, subscribe to our Event Grid Topic, and then demo it in action. We will use Postman to set up a POST request to our Event Grid Topic public endpoint that has authentication, version parameter, and the correct JSON body format. After we send the request, we will take a look in the Azure portal to verify the activity and that our subscriber function received and processed the event. 

## Demo Video

[![Watch the demo video](/images/title.jpg)](https://www.youtube.com/watch?v=TvMtBOw5SCc "Video Demo - Azure Event Grid Demo: Publish (Postman) and Subscriber (Azure Function)")

