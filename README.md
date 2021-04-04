# Introduction
This application perform CRUD operations around asset.

# Technologies - Dependencies
This application was built with the below technologies and so it is compulsory to have them to run this application successfully.
<ul>
<li><a href='https://dotnet.microsoft.com/download/dotnet/5.0' target='_blank' noreferral >Dotnet 5</a> - Backend API</li>
<li><a href='https://www.docker.com/products/docker-desktop' target='_blank' noreferral >Docker</a> - Container Servicr</li>
<li><a href='https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.InMemory' target='_blank' noreferral >SQLInMemory Databse</a> - Database </li> 
<li><a href='http://aurelia.io' target='_blank' noreferral >Aurelia</a> - Frontend </li> 
<li><a href='https://nodejs.org/en/download' target='_blank' noreferral >Nodejs</a> - needed to utilize NPM</li> 
</ul>

# Application Testing
<ul>
<li>Clone this repository from your preferred terminal by running <pre>git clone https://github.com/SamuelKoroh/Hahn-Application-Process-Application.git </pre> </li>
<li>Extract <strong>Hahn.ApplicationProcess.Application.zip</strong> to the location of your choice.</li>
</ul>

## Application Testing (Docker-compose)
<ul>
<li>Goto the root directory of the extracted zip file from the terminal.</li>
<li>Restore and build the solution by running <pre>dotnet restore</pre>  <pre>dotnet build</pre></li>
<li>To build the necessary docker compose service, run  <pre>docker-compose up</pre> </li>
<li>Access the <em>frontend app </em> from http://localhost:5000/</li>
<li>Access the <em>backend api </em> from http://localhost:5000/swagger</li>
</ul>

## Application Testing (VS-Code)
<ul>
<li>Open the root directory of the extracted zip file from vs code.</li>
<li>Restore and build the solution by running <pre>dotnet restore</pre>  <pre>dotnet build</pre></li>
<li>cd into Hahn.ApplicationProcess.February2021.Web</li>
<li>Restore node packages with the command <pre>npm install</pre> </li>
<li>Build the frontend project with the command<pre>npm run webpack:Release</pre> </li>
<li>Still inside of Hahn.ApplicationProcess.February2021.Web run the project with the command <pre>dotnet run</pre> </li>
<li>Access the <em>frontend app </em> from http://localhost:5000/ or https://localhost:5001/</li>
<li>Access the <em>backend api </em> from http://localhost:5000/swaggger or http://localhost:5001/swaggger</li>
</ul>
