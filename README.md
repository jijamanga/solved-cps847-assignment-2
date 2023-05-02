Download Link: https://assignmentchef.com/product/solved-cps847-assignment-2
<br>



<ol>

 <li>Make your GitHub repo <strong>public</strong>. If you are creating a new repo for this assignment, then please add  cps847-chang, tonymisic and kazi-rys-21 to GitHub account</li>

 <li>Create a Travis CI YAML file that executes a unit test of your sample code [25%] and creates a code coverage report  to be uploaded to codecov.io. Choose a unit test and code coverage framework that is appropriate for the language that you are using.</li>

 <li>Create a Dockerfile to generate a container for your web application [10%]</li>

 <li>Generate index.html page containing “Hello World” text and deploy the code to AWS ElasticBeanstalk (Container) using Travis CI</li>

 <li>Install Ubuntu VM on your laptop using VirtualBox player and Ubuntu ISO (<a href="https://www.ubuntu.com/download/desktop">https://www.ubuntu.com/download/desktop</a>). Put a folder with the name of your group on the Ubuntu desktop.</li>

 <li> Create AWS Lambda function that reads in JSON</li>

</ol>




{

“first_name”: “Jane”,

“last_name”: “Doe”

}

and returns

{

“statusCode”: 200,

“output”: “Jane Doe”

}




You can implement this Lambda function in any language. You do not need to externalize the API.




<strong><u>Deliverables</u></strong>




<ol>

 <li>To submit to D2L

  <ol>

   <li>A snapshot of TravisCI log building and testing your code</li>

   <li>Provide the logs which was generated when containerizing your application</li>

   <li>A snapshot of Codecov.io report of your code</li>

   <li>Provide a screenshot of the your index.html on AWS EB along with the URL box of the browser.</li>

   <li>A snapshot (screen capture) of the Ubuntu desktop within your host machine</li>

   <li>Write a report on how the lambda function works.</li>

  </ol></li>

</ol>