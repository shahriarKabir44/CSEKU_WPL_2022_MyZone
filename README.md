# MyZone
A Web based social media application
## Technologies used:
<ol>
  <li>React</li>
  <li>Redux</li>
  <li>Material UI</li>   
  <li>Express.Js</li>
  <li>MySQL</li>
  <li>WebSocket</li>
  <li>Node.Js</li>
</ol>

## How to use:
<ul>
<li>
      <h2>Prerequisites:</h2>
      <ol>
        <li>Node.js version 18 or above.</li>
        <li>
          The machine needs to have MySQL server installed.
        </li>
      </ol>
  </li>
  <li>
      <h2>Installation</h2>
      <ol>
        <li>Clone this repository</li>
        <li>Go to each folder and run the command <br/>
          <code>npm i </code>
          <br/> This will download all the project dependencies.
        </li>
      </ol>
  </li>
  
  <li>
    <h2>Environment setup</h2>
    <ol>
        <li>Open the file <code>Globals.js</code> located at <code>myzone/services</code>.
        <br/>
        Set the <code>SERVER_IP_ADDRESS</code> to your IPv4 address. 
        </li>
        <li>Go to the<code>myZone-API</code> folder and create a file named <br/>
          <code>.env</code>
          <br/>  Write the following content on the file:
          <br/> <code>jwtSecret="some random string"</code>
        </li>
      </ol>
  </li>   
  <li>
      <h2>Execution</h2>
      Every sub-project can be run individually by executing the command <code>npm run start</code>. <br/>
      So, open terminals into each of the 3 folders and execute the command. 
      <br/> After that, Open     <code>localhost:3000</code> on your browser!
  </li>
  
  
</ul>
