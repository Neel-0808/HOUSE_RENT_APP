<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="Home_Rental_Web_Application_0"></a>Home Rental Web Application</h1>
<h2 class="code-line" data-line-start=2 data-line-end=3 ><a id="Team_Members_2"></a>Team Members</h2>
<ol>
<li class="has-line-data" data-line-start="4" data-line-end="5"><strong>[Neelraj.S]</strong> - <strong>310121104068</strong></li>
<li class="has-line-data" data-line-start="5" data-line-end="6"><strong>[Naraayanan.T]</strong> - <strong>310121104067</strong></li>
<li class="has-line-data" data-line-start="6" data-line-end="7"><strong>[Sri Arvind]</strong> - <strong>310121104100</strong></li>
<li class="has-line-data" data-line-start="7" data-line-end="8"><strong>[Rajesh.D]</strong> - <strong>310121104080</strong></li>
<li class="has-line-data" data-line-start="8" data-line-end="10"><strong>[Nandha Kumar.S]</strong> - <strong>310121104066</strong></li>
</ol>
<h2 class="code-line" data-line-start=10 data-line-end=11 ><a id="Overview_10"></a>Overview</h2>
<p class="has-line-data" data-line-start="12" data-line-end="13">The Home Rental Web App is a platform developed using the MERN stack (MongoDB, Express.js, React, and Node.js) to help users find, list, and manage rental properties. The application enables property owners to post rental listings and potential renters to search for properties that match their preferences. This web app streamlines the rental process by connecting landlords and renters in one platform, making it easy to find or advertise rental properties.</p>
<h2 class="code-line" data-line-start=14 data-line-end=15 ><a id="Table_of_Contents_14"></a>Table of Contents</h2>
<ul>
<li class="has-line-data" data-line-start="16" data-line-end="17">#team-members</li>
<li class="has-line-data" data-line-start="17" data-line-end="18">#overview</li>
<li class="has-line-data" data-line-start="18" data-line-end="19">#features</li>
<li class="has-line-data" data-line-start="19" data-line-end="20">#tech-stack</li>
<li class="has-line-data" data-line-start="20" data-line-end="21">#setup-and-installation</li>
<li class="has-line-data" data-line-start="21" data-line-end="23">#license</li>
</ul>
<h2 class="code-line" data-line-start=23 data-line-end=24 ><a id="Features_23"></a>Features</h2>
<ul>
<li class="has-line-data" data-line-start="25" data-line-end="26"><strong>User Authentication</strong>: Secure login and registration for landlords and renters.</li>
<li class="has-line-data" data-line-start="26" data-line-end="27"><strong>Property Listings</strong>: Landlords can post new listings with details like property type, location, price, and photos.</li>
<li class="has-line-data" data-line-start="27" data-line-end="28"><strong>Property Search</strong>: Renters can search properties based on location, price range, and other filters.</li>
<li class="has-line-data" data-line-start="28" data-line-end="29"><strong>Booking Requests</strong>: Allows renters to submit booking requests directly through the app.</li>
<li class="has-line-data" data-line-start="29" data-line-end="30"><strong>Favorites List</strong>: Renters can save properties they’re interested in.</li>
<li class="has-line-data" data-line-start="30" data-line-end="32"><strong>Responsive Design</strong>: Ensures usability on both desktop and mobile devices.</li>
</ul>
<h2 class="code-line" data-line-start=32 data-line-end=33 ><a id="Tech_Stack_32"></a>Tech Stack</h2>
<ul>
<li class="has-line-data" data-line-start="34" data-line-end="35"><strong>Frontend</strong>: React.js</li>
<li class="has-line-data" data-line-start="35" data-line-end="36"><strong>Backend</strong>: Node.js, Express.js</li>
<li class="has-line-data" data-line-start="36" data-line-end="37"><strong>Database</strong>: MongoDB</li>
<li class="has-line-data" data-line-start="37" data-line-end="38"><strong>Styling</strong>: CSS</li>
<li class="has-line-data" data-line-start="38" data-line-end="39"><strong>Authentication</strong>: JWT (JSON Web Tokens)</li>
</ul>
<h2 class="code-line" data-line-start=41 data-line-end=42 ><a id="Setup_and_Installation_41"></a>Setup and Installation</h2>
<ol>
<li class="has-line-data" data-line-start="43" data-line-end="49">
<p class="has-line-data" data-line-start="43" data-line-end="44"><strong>Clone the repository</strong></p>
<pre><code class="has-line-data" data-line-start="45" data-line-end="48" class="language-bash">git <span class="hljs-built_in">clone</span> https://github.com/your-repo/House-Rental.git
<span class="hljs-built_in">cd</span> House-Rental
</code></pre>
</li>
<li class="has-line-data" data-line-start="49" data-line-end="58">
<p class="has-line-data" data-line-start="49" data-line-end="51"><strong>Install dependencies</strong><br>
Navigate to the backend and frontend directories to install dependencies:</p>
<pre><code class="has-line-data" data-line-start="52" data-line-end="57" class="language-bash"><span class="hljs-built_in">cd</span> backend
npm install
<span class="hljs-built_in">cd</span> ../frontend
npm install
</code></pre>
</li>
<li class="has-line-data" data-line-start="58" data-line-end="66">
<p class="has-line-data" data-line-start="58" data-line-end="60"><strong>Configure Environment Variables</strong><br>
Set up the required environment variables in a <code>.env</code> file in the backend directory:</p>
<pre><code class="has-line-data" data-line-start="61" data-line-end="65" class="language-plaintext">PORT=8000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
</code></pre>
</li>
<li class="has-line-data" data-line-start="66" data-line-end="75">
<p class="has-line-data" data-line-start="66" data-line-end="68"><strong>Run the Application</strong><br>
Start both the backend and frontend servers:</p>
<pre><code class="has-line-data" data-line-start="69" data-line-end="74" class="language-bash"><span class="hljs-comment"># In the backend directory</span>
npm start
<span class="hljs-comment"># In the frontend directory</span>
npm start
</code></pre>
</li>
<li class="has-line-data" data-line-start="75" data-line-end="77">
<p class="has-line-data" data-line-start="75" data-line-end="77"><strong>Access the Application</strong><br>
Visit <code>http://localhost:3000</code> to view the app in your browser.</p>
</li>
</ol>
<h2 class="code-line" data-line-start=79 data-line-end=80 ><a id="License_79"></a>License</h2>
<p class="has-line-data" data-line-start="81" data-line-end="102">This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.<br>
About<br>
No description, website, or topics provided.<br>
Resources<br>
Readme<br>
Activity<br>
Stars<br>
0 stars<br>
Watchers<br>
1 watching<br>
Forks<br>
0 forks<br>
Releases<br>
No releases published<br>
Create a new release<br>
Packages<br>
No packages published<br>
Publish your first package<br>
Languages<br>
JavaScript<br>
93.5%</p>
<p class="has-line-data" data-line-start="103" data-line-end="105">CSS<br>
6.1%</p>
<p class="has-line-data" data-line-start="106" data-line-end="121">HTML<br>
0.4%<br>
Suggested workflows<br>
Based on your tech stack<br>
Publish Node.js Package to GitHub Packages logo<br>
Publish Node.js Package to GitHub Packages<br>
Publishes a Node.js package to GitHub Packages.<br>
Node.js logo<br>
Node.js<br>
Build and test a Node.js project with npm.<br>
Grunt logo<br>
Grunt<br>
Build a NodeJS project with npm and grunt.<br>
More workflows<br>
Footer</p>
