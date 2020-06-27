# Weather-Chat-Bot
 <h1>
        In this, project we are building a chat bot in Amazon AWS that tells the weather details of any location across the globe.
    </h1>
    <h2>Requirements</h2>
    <ol>
        <li>Node.js</li>
        <li>AWS Account</li>
        <li>Serverless</li>
    </ol>
    <h1>This project is based on three tasks</h1>
    <h3>
        Task 1
    </h3>
    <p>
        Firstly, you need to have an amazon AWS account. <br>
        After that, go to the amazon AWS console management. <a href="https://aws.amazon.com/console/">Click here</a>
      <p>
        You need to build a chat-bot in AWS.
        In the search bar, select Amazon lex.  
        <br>
        <h3>Now create a bot</h3>
        <i>Select custom bot</i> <br>
       </p>
    </p>
    <h3>Now create an intent</h3>
        Fill the details as per the picture
        Save the Intent and build it.
    <h4>Task 1 is completed</h4>
    <hr>
    <h3>
        Task 2
    </h3>
    <p>Make sure you have node.js in your system, if you don't have click on this 
        <a href="https://nodejs.org/en/">link</a> <br>
        Download it and Install it in your computer.
    </p>
    <li>To make sure it is working, open command prompt, run these commands</li>  <br>
    <code>npm --version </code> <br>
    <code>node -v</code> <br>
    <li> Now go to any directoty, run <br></li><br>
    <code>npm install -g serverless </code> <br>
    <li>Now you can clone the repository or you can build everything from scratch</li> <br>
    <p>
    If you have cloned the repository,
    you can directly skip to step 3.
    </p> <br>
    <li>
    If you want to build from scratch, create a serverless service, to do that run
    <ul>
    </li><br> <code>serverless</code> <br> </li>
    <li> Select <code>AWS nodejs</code> </li>
    <li>Now your project has been created.</li>
    <li> Go to <code>serverless.yml</code> </li> <br>
    </ul>
      ##Copy and paste the code in serverless.yml in our repo.
   <li>
        Now, go to <code>handler.js</code> <br>
   </li>
     ##Copy and paste the code in handler.js in our repo.
     <h2>
        Task 2 has been completed.
    </h2> <br>
    <hr>
    <h2>
        Task 3
    </h2>
    <a href="https://www.serverless.com/framework/docs/providers/aws/guide/credentials/">Follow this link</a> <br>
    <li>After you have added both the keys, it is time to deploy our project. In the terminal, run</li> <br>
    <code>
        serverless deploy
    </code> <br>
    <h1>    We are at the final phase, are you still with me?
    </h1>    
    <li>Go to the Aws, open the bot that you have created, refresh the page</li> <br>
    <li>Select lambda function</li>
    <li>Now build the bot.</li>

    <h1>There you go, successfully created a weather chat-bot</h1>
