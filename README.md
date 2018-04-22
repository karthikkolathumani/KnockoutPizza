# KnockoutPizza
An automated Facebook messenger chatbot to order your favourite pizza!!

The project uses primarily Node and IBM watson to understand the intent of the users.
I have defined intents and entities over the IBM assistant workspace to process the request.
The code uses context and facebook user page id to preserve the context. The context is destroyed once watson identifies the 'EXIT' intent.
The facebook messenger API uses 'WEBHOOKS' to invoke a request to our service endpoint. Since it requires SSL, the project requires ngrok
or can be hosted over a cloud to run this application. I tried Ngrok and Cloud 9. It worked perfectly with both.

![ice_video_20180422-024455](https://user-images.githubusercontent.com/32400289/39093647-a9e5ae9c-45d7-11e8-934f-601fd0f307c5.gif)
