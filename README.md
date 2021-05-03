# Flask_Rock_Paper_Scissor_classification_model

This homework is done as a part of deep learning course at CSUSM.
a)Flask webserver accept http request from client. It is a server-side Python framework that we can create web applications. 
We can deploy our ML models in our flask server so clients from anywhere in the world can connect to that server send request to classify an image based on the model 
that is stored on the flask server. Frameworks like Flask come with a library of modules and functions with which you can create backend systems for your own web applications. 
I run flask locally on my computer but it can be run on the web and remote server.
 To run this server we should run this python code in the server side , simply by running this command on server: python server.py
And in the client side , To classify rock1.image clients should send the request containing image name that want to be classified. For example the send : client rock1.png
Be hind the scene this http request send to the server by curl command from the client side. 
I create a batch file for this curl command. We should specify an image name in the client side to send  to the server by curl command in the client.
After sending request to the server to classify that specific image, the server classify that image based on the model that is store on the flask server and return the class of that specific  image  and also the time of system to the client. To return more than 2 variable we should use f string such that this f string contains the format and other extra text that is going to be shown in the client side.
b)To test  server and client like following print screens, we should run server in the server side and client in the client side .
If the server processing the client request successfully it will print proper message number in the server side without any error here its message number is 200 and also proper
output will be shown in the client side that shows the time of the system and correct classification for the input image in this assignment. These 2 messages in the server and 
client are synched together.


 
