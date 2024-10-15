<h1 align="center">Event Management System</h1>

<h2>Tech Stack</h2>
<ul>
  <li><b>Java (Spring Boot)</b></li>
  <li><b>MySQL</b></li>
  <li><b>MongoDB</b></li>
  <li><b>Spring Security</b> (for authentication and authorization)</li>
  <li><b>JWT</b> (JSON Web Tokens for stateless authentication)</li>
  <li><b>Docker</b> (for containerization)</li>
  <li><b>AWS</b> (for cloud hosting and storage)</li>
  <li><b>Jenkins</b> (for Continuous Integration and Continuous Deployment)</li>
  <li><b>Kafka</b> (for real-time messaging and event-driven architecture)</li>
</ul>

<h2>Why It’s Impactful</h2>
<p>
  Event management systems are widely used in various industries, including corporate events, webinars, and conferences. This project helps demonstrate backend skills, focusing on key areas like user roles, event handling, and real-time updates.
</p>

<h3>Key Features</h3>
<ul>
  <li>User roles: Organizers, Attendees, Admins.</li>
  <li>Event creation, management, and ticket sales.</li>
  <li>Integration with external services (e.g., payment gateway for transactions).</li>
  <li>User notifications for event reminders (via email/SMS).</li>
</ul>

<h3>Additional Features</h3>
<ul>
  <li>Event calendar integration.</li>
  <li>Real-time seat availability updates using WebSockets or Kafka.</li>
  <li>Analytics dashboard for organizers, providing insights like attendee demographics and sales data.</li>
</ul>

<h2>Architecture Overview</h2>
<p>
  The system uses a microservices architecture where different components, such as user management, event management, and ticket sales, are handled by independent services. Kafka is used for communication between services to handle real-time updates. 
  The application is deployed on AWS using Docker containers and managed through Jenkins for CI/CD.
</p>

<h2>Getting Started</h2>
<h3>Prerequisites</h3>
<ul>
  <li>Java 11+</li>
  <li>MySQL or PostgreSQL</li>
  <li>MongoDB</li>
  <li>Docker</li>
  <li>AWS account (optional, for cloud deployment)</li>
</ul>

<h3>Installation</h3>
<pre>
<code>
# Clone the repository
git clone https://github.com/yourusername/event-management-system.git

# Navigate to the project directory
cd event-management-system

# Build and run the project
mvn clean install
mvn spring-boot:run
</code>
</pre>

<h3>Docker Setup</h3>
<p>If you wish to use Docker for containerization, use the following commands:</p>
<pre>
<code>
# Build the Docker image
docker build -t event-management-system .

# Run the Docker container
docker run -p 8080:8080 event-management-system
</code>
</pre>

<h2>License</h2>
<p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
