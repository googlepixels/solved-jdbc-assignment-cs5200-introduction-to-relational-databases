Download Link: https://assignmentchef.com/product/solved-jdbc-assignment-cs5200-introduction-to-relational-databases
<br>
<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Consider the UML class diagram shown below. Create the corresponding Java Data Model that implements the equivalent relational model, fulfills the use cases, implements the relations, and enforces the constraints. Implement Data Access Objects (DAOs) that encapsulate access to the database applying best practices discussed in class. </span><u style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">​</u><a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://docs.google.com/document/d/1TF4pi52f1HIks1monqfO-qTHXapUY2pWD4yE5b2vY2A/edit?usp=sharing">A</a> <a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://docs.google.com/document/d/1TF4pi52f1HIks1monqfO-qTHXapUY2pWD4yE5b2vY2A/edit?usp=sharing">link</a> <a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://docs.google.com/document/d/1TF4pi52f1HIks1monqfO-qTHXapUY2pWD4yE5b2vY2A/edit?usp=sharing">to</a> <a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://docs.google.com/document/d/1TF4pi52f1HIks1monqfO-qTHXapUY2pWD4yE5b2vY2A/edit?usp=sharing">this</a> <a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://docs.google.com/document/d/1TF4pi52f1HIks1monqfO-qTHXapUY2pWD4yE5b2vY2A/edit?usp=sharing">assignment</a> <a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://docs.google.com/document/d/1TF4pi52f1HIks1monqfO-qTHXapUY2pWD4yE5b2vY2A/edit?usp=sharing">can</a> <a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://docs.google.com/document/d/1TF4pi52f1HIks1monqfO-qTHXapUY2pWD4yE5b2vY2A/edit?usp=sharing">be</a> <a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://docs.google.com/document/d/1TF4pi52f1HIks1monqfO-qTHXapUY2pWD4yE5b2vY2A/edit?usp=sharing">found</a> <a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://docs.google.com/document/d/1TF4pi52f1HIks1monqfO-qTHXapUY2pWD4yE5b2vY2A/edit?usp=sharing">here</a><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">​.</span>

<h1>UML Class Diagram</h1>

<strong>Disregard the attributes for the User class in this diagram. See the below diagram for updated user attributes. </strong>







<h1>Create Java Data Model (5pts.)</h1>

Use Java to implement the data model. Make use of best practices discussed in class. Each instance variables must be declared as private and have public setters and getters.




<table width="519">

 <tbody>

  <tr>

   <td width="336"><strong>1.  </strong><strong>Person.java </strong><strong>2.  </strong><strong>User.java </strong><strong>3.  </strong><strong>Developer.java </strong><strong>4.  </strong><strong>Website.java </strong><strong>5.  </strong><strong>Page.java </strong><strong>6.  </strong><strong>Widget.java </strong></td>

   <td width="183"><strong>7.   </strong><strong>HeadingWidget.java </strong><strong>8.   </strong><strong>HtmlWidget.java </strong><strong>9.   </strong><strong>ImageWidget.java </strong><strong>10.  </strong><strong>YouTubeWidget.java </strong><strong>11.  </strong><strong>Role.java </strong><strong>12.  </strong><strong>Priviledge.java </strong></td>

  </tr>

 </tbody>

</table>

<h1>Constructor Requirements: (5Pts)</h1>

<strong>There are no constructor requirements for classes not specified below. You are free to implement constructors as you see fit. </strong>

<h2><strong>1. Developers.java </strong></h2>

<ol>

 <li>Should create an instance of developer when developer Key, Developer ID, Developer First Name, Developer Last Name, with rest of the fields with default values specified by you.</li>

 <li>Should also create an instance of developer when developer key, developer ID, developer first name, developer last name, developer user-name, developer password, email and dob are passed as parameters.</li>

</ol>

<h2><strong>2. User.java </strong></h2>

<ol>

 <li>Should create an instance of user when user ID, First Name, Last Name. All new users cannot be approved users.</li>

</ol>

<h2><strong>3. Websites.java </strong></h2>

<ol>

 <li>Should create an instance of website when id, website name, description, created, updated, and views are passed as parameters.</li>

</ol>

<h2><strong>4. Page.java </strong></h2>

<ol>

 <li>Should create an instance of Page when id, title, description, created, updated and views are passed as parameters.</li>

</ol>

<h2><strong>5. Widget.java </strong></h2>

<ol>

 <li>Should create an instance of Widget when ID, name, width, height, cssStyle, cssCLass, text, order are passed as parameters.</li>

</ol>


























































<h2><strong>UML Diagram </strong></h2>

The UML diagram defines several associations between various classes using lines and symbols. These are implemented in SQL using primary and foreign key fields. In Java you’ll also capture the primary key fields id, but instead of the foreign key fields, you’ll capture some collection of instances of the child class. As an example, consider the relation between entities Website and Page illustrated below. The UML class diagram captures the association using a line and the cardinality of how many of each participate in relation. The diagram says that each Website instance has zero or more Page instance.




<table width="624">

 <tbody>

  <tr>

   <td width="181">UML</td>

   <td width="225">SQL</td>

   <td width="218">Java</td>

  </tr>

 </tbody>

</table>

CREATE TABLE Website (      class Website {

id int,                     int id;

PRIMARY KEY (id)            Collection&lt;Page&gt; pages;

);                            addPage(Page) { }

CREATE TABLE Page (           removePage(Page) { }

id int,                   }

websiteId int,            class Page {

FOREIGN KEY (websiteId)   Website website;

REFERENCES Website(id) }

);







SQL implements the relation using primary and foreign keys. In the example, the <strong>Page</strong>​ table declares foreign key ​<strong>websiteId</strong> which references to the ​<strong>id</strong> field in the ​<strong>Website</strong> table. If we consider the relation between websites and pages as a whole/parts relation, where pages are the various parts that make a whole Website, then the relation implementation states that each part (page) know who the whole is (website). The Java implementation captures the relation between websites and pages by declaring a collection of pages in the ​<strong>Website</strong> class. That is, each ​<strong>Website</strong> instance has a complete list of references to its <strong>Page</strong>​ instance. Notice the difference in the direction of the relation between the SQL and the Java relation implementation. Whereas in the SQL implementation the relation is from the part to the whole, e.g., page records have foreign key references to websites, in the Java implementation, the relation goes from the whole to the parts, e.g., the websites have a collection of references to page instances. Additionally, the Java implementation also can declare a reference from the page to the website which matches the SQL implementation, but this is less common in object oriented solutions.




A good naming convention for primary and foreign keys is to name all foreign keys “<strong>id</strong>​ “​ (or “<strong>ID</strong>​ ​”) and name the foreign keys that refer to them as the table name followed by “<strong>Id</strong>​ “.​ For instance, from the example above, the foreign key from table ​<strong>Page</strong> to table ​<strong>Website</strong> should be named <strong>websiteId</strong>​ and should refer to the primary key field ​<strong>id</strong>​ in table ​<strong>Website</strong>​.

<h1>Naming Conventions (5pts)</h1>

These are the naming conventions for the project and they must be followed. Else your JUnit grader will fail and would not grade your assignments.




<ol>

 <li>Your Projects must be named cs5200_fall2018_lastname_firstname_jdbc</li>

 <li>All Packages must be created in src-&gt;main-&gt;java-&gt;edu-&gt;northeastern-&gt;cs5200</li>

 <li>Inside your edu.northeastern.cs5200 package,

  <ol>

   <li>All DAOs must be in package called ​</li>

   <li>All models must be in package called <em>models</em>​ ​.</li>

   <li>If other packages are created, please specify their names in README.txt.</li>

  </ol></li>

</ol>

<h1>Implementation(5Pts)</h1>

<strong><em>**All applications should be deployed in AWS, unless otherwise excused.** </em></strong>

<strong><em> </em></strong>

<strong><em>In src-&gt;main-&gt;java&gt;edu&gt;northeastern&gt;cs5200 package, create a public Singleton class called Connection.java.  </em></strong>




public class Connection {




private static final String DRIVER = “com.mysql.jdbc.Driver”;

private static final String URL = “jdbc:mysql://&lt;AWS ENDPOINT&gt;/&lt;SCHEMA NAME&gt;”; private static final String USER = &lt;AWS RDS USERNAME&gt;; private static final String PASSWORD = &lt;AWS RDS PASSWORD&gt;;




public static Connection getConnection() throws ClassNotFoundException,

SQLException {

Class.forName(DRIVER);

return DriverManager.getConnection(URL, USER, PASSWORD);

}




public static void closeConnection(Connection conn) {

try {      conn.close();

} catch (SQLException e) {

// TODO Auto-generated catch block             e.printStackTrace();

}

}

}




So, everytime the test method calls the static method called getInstance() of the

Connection.java class, it should return the same instance of the connection rather than creating a new instance.

The class should have method called closeConnection(). It must be a static method and should not return anything. It closes the above said connection.

<h1>Create Data Access Objects (40pts.)</h1>

A good practice is to encapsulate all data access in a set of classes whose only responsibility is to provide an API to the database. These types of classes are commonly referred to as Data Access Objects, or DAOs. Implement the following DAOs that encapsulate the access to the database for each of the entities and relations in the UML class diagram. <strong> </strong>

<ol>

 <li><strong> DeveloperDao.java 4. WidgetDao.java 2. WebsiteDao.java 5. RoleDao.java 3. PageDao.java   6. PriviledgeDao.java </strong></li>

</ol>

<h2>Implement the Developer Data Access Object</h2>

In a file called ​<strong>DeveloperImpl.java</strong>​, create an interface shown below. Please do not make any modification to the interface.




<h3>1. void createDeveloper(Developer developer)</h3>

inserts properties in ​<strong>developer</strong>​ instance parameter in tables ​<strong>Developer</strong>​ and <strong>Person</strong>​

<ol start="2">

 <li><strong>Collection&lt;Developer&gt; findAllDevelopers()</strong> returns all joined records from ​<strong>Developer</strong> and ​<strong>Person</strong> tables as a ​<strong>Collection</strong> of <strong>Developer</strong>​ instances.</li>

</ol>

<h3>3. Developer findDeveloperById(int developerId)</h3>

returns a joined record from ​<strong>Developer</strong> and ​<strong>Person</strong> tables whose ​<strong>id</strong> field is equal to the <strong>developerId</strong>​ parameter

<ol start="4">

 <li><strong>Developer findDeveloperByUsername(String username)</strong> returns a joined record from ​<strong>Developer</strong> and ​<strong>Person</strong> tables whose ​<strong>username</strong> field matches the parameter.</li>

</ol>

<h3>5. Developer findDeveloperByCredentials(String username, String password) returns a joined record from ​Developer and ​Person tables whose ​username and password fields match the parameters​</h3>

<ol start="6">

 <li><strong>int updateDeveloper(int developerId, Developer developer)</strong> updates records in ​<strong>Developer</strong> and ​<strong>Person</strong> tables whose <strong>id</strong>​ field is equal to <strong>developerId</strong> New record field values are set to the values in the ​<strong>developer</strong> instance parameter.</li>

 <li><strong>int deleteDeveloper(int developerId)</strong> deletes records from ​<strong>Developer</strong> and ​<strong>Person</strong> tables whose ​<strong>id</strong> field is equal to <strong>developerId</strong> ​ ​<em>Do not make any modifications to the instance provided.</em></li>

</ol>




In a file called <strong>DeveloperDao.java</strong>​ ,​ develop a class which implements the Developer interface and encapsulates all database interaction between the ​<strong>Developer</strong> and ​<strong>Person</strong> entities and relations.




<strong><em>When returning the developer instance, create a new developer instance and do not modify the existing developer instance provided in the parameters.</em></strong>

<h2>Implement Website Data Access Object</h2>

In a file called ​<strong>WebsiteImpl.java</strong>​, create an interface as shown below. Do not make any modifications to the interface.




<h3>1. void createWebsiteForDeveloper(int developerId, Website website)</h3>

inserts properties in ​<strong>website</strong> instance parameter into the ​<strong>Website</strong> table. The website’s <strong>developerId</strong> foreign key refer to ​<strong>Developer </strong>​table primary key ​<strong>id</strong> whose value is equal to the <strong>developerId</strong>​ parameter. You can use the owner’s user id as the foreign key​

<ol start="2">

 <li><strong>Collection&lt;Website&gt; findAllWebsites()</strong></li>

</ol>

returns all records from ​<strong>Website</strong>​ table as a ​<strong>Collection</strong>​ of ​<strong>Website</strong>​ instances

<ol start="3">

 <li><strong>Collection&lt;Website&gt; findWebsitesForDeveloper(int developerId)</strong> returns all records from ​<strong>Website</strong> table as a ​<strong>Collection</strong> of ​<strong>Website</strong> instances whose <strong>developerId</strong>​ is equal to the ​<strong>developerId</strong>​ parameter <strong>Website findWebsiteById(int websiteId)</strong></li>

</ol>

returns a record from ​<strong>Website</strong>​ table whose ​<strong>id</strong>​ field is equal to the ​<strong>websiteId</strong>​ parameter

<h3>5. int updateWebsite(int websiteId, Website website)</h3>

updates record in ​<strong>Website</strong> table whose ​<strong>id</strong> field is equal to ​<strong>websiteId</strong> parameter. New record field values are set to the values in the ​<strong>website</strong>​ instance parameter

<h3>6. int deleteWebsite(int websiteId)</h3>

deletes record from ​<strong>Website</strong>​ table whose ​<strong>id</strong>​ field is equal to ​<strong>websiteId</strong> parameter​




In a file called ​<strong>WebsiteDao.java</strong>​, implement a class that encapsulates all database interaction between the ​<strong>Website</strong>​ and ​<strong>Developer</strong>​ entities and relations.




<strong><em>When returning the website instance, create a new website instance and do not modify the existing developer instance provided in the parameters.</em></strong>

<h2>Implement Page Data Access Object</h2>

In a file called ​<strong>PageImpl.java, </strong>​create an interface with the methods given below. Do not make any modifications.




<h3>1. void createPageForWebsite(int websiteId, Page page)</h3>

inserts properties in <strong>page</strong>​    instance parameter into the <strong>Page</strong>​      table. The page’s <strong>websiteId</strong>​            foreign key refer to <strong>Website</strong>​       ​table primary key <strong>id</strong>​ whose value is equal to the ​<strong>websiteId</strong> parameter

<ol start="2">

 <li><strong>Collection&lt;Page&gt; findAllPages()</strong></li>

</ol>

returns all records from ​<strong>Page</strong>​ table as a ​<strong>Collection</strong>​ of ​<strong>Page</strong>​ instances

<ol start="3">

 <li><strong>Page findPageById(int pageId)</strong></li>

</ol>

returns a record from ​<strong>Page</strong>​ table whose ​<strong>id</strong>​ field is equal to the ​<strong>pageId</strong>​ parameter

<h3>4. Collection&lt;Page&gt; findPagesForWebsite(int websiteId)</h3>

returns all records from ​<strong>Page</strong> table as a ​<strong>Collection</strong> of ​<strong>Page</strong> instances whose ​<strong>websiteId</strong> is equal to the ​<strong>websiteId</strong>​ parameter

<h3>5. int updatePage(int pageId, Page page)</h3>

updates record in ​<strong>Page</strong> table whose ​<strong>id</strong> field is equal to ​<strong>pageId</strong> parameter. New record field values are set to the values in the ​<strong>page</strong>​ instance parameter

<h3>6. int deletePage(int pageId)</h3>

deletes record from ​<strong>Page</strong>​ table whose ​<strong>id</strong>​ field is equal to ​<strong>pageId</strong>​ parameter




In a file called ​<strong>PageDao.java</strong>​, implement a class that encapsulates all database interaction between the ​<strong>Website</strong>​ and ​<strong>Page</strong>​ entities and relations. Use the interface shown below.




<strong><em>When returning the page instance, create a new page instance and do not modify the existing developer instance provided in the parameters.</em></strong>

<h2>Implement Widget Data Access Object</h2>

In a file called ​<strong>WidgetImpl.java, </strong>​create an interface with the methods given below. Do not make any modifications.




<h3>1. int createWidgetForPage(int pageId, Widget widget)</h3>

inserts properties in ​<strong>widget</strong> instance parameter into the ​<strong>Widget</strong> table. The widget’s <strong>pageId</strong> foreign key refer to ​<strong>Page </strong>​table primary key ​<strong>id</strong> whose value is equal to the <strong>pageId</strong>​ parameter

<ol start="2">

 <li><strong>Collection&lt;Widget&gt; findAllWidgets()</strong></li>

</ol>

returns all records from ​<strong>Widget</strong>​ table as a ​<strong>Collection</strong>​ of ​<strong>Widget</strong> instances​

<h3>3. Widget findWidgetById(int widgetId)</h3>

returns a record from ​<strong>Widget</strong>​ table whose ​<strong>id</strong>​ field is equal to the ​<strong>widgetId</strong>​ parameter

<ol start="4">

 <li><strong>Collection&lt;Widget&gt; findWidgetsForPage(int pageId)</strong> returns all records from ​<strong>Widget</strong> table as a ​<strong>Collection</strong> of ​<strong>Widget</strong> instances whose <strong>pageId</strong>​ is equal to the ​<strong>pageId</strong>​ parameter</li>

 <li><strong>int updateWidget(int widgetId, Widget widget)</strong> updates record in ​<strong>Widget</strong> table whose ​<strong>id</strong> field is equal to ​<strong>widgetId</strong> New record field values are set to the values in the ​<strong>widget</strong>​ instance parameter</li>

</ol>

<h3>6. int deleteWidget(int widgetId)</h3>

deletes record from ​<strong>Widget</strong>​ table whose ​<strong>id</strong>​ field is equal to ​<strong>widgetId</strong>​ parameter




In a file called ​<strong>WidgetDao.java</strong>​, implement a class that encapsulates all database interaction between the ​<strong>Widget</strong> and ​ ​<strong>Page</strong> entities and relations.​




<strong><em>When returning the widget instance, create a new widget instance and do not modify the existing developer instance provided in the parameters.</em></strong>

<h2>Implement Role Data Access Object</h2>

In a file called ​<strong>RoleDao.java</strong>​, implement a class that encapsulates all database access that manage website and page roles assigned to ​<strong>Developer</strong>​. Use the interface shown below. Feel free to implement additional or improved versions of the API




<ol>

 <li>assignWebsiteRole(int developerId, int websiteId, int roleId)</li>

</ol>

inserts into table Role a record that assigns a developer whose id is developerId, the role with roleId, to the website with websiteId

<ol start="2">

 <li>assignPageRole(int developerId, int pageId, int roleId)</li>

</ol>

inserts into table Role a record that assigns a developer whose id is developerId, the role with roleId, to the page with pageId

<ol start="3">

 <li>deleteWebsiteRole(int developerId, int websiteId, int roleId)</li>

</ol>

deletes from table Role a record that removes roleId from developerId, on websiteId

<ol start="4">

 <li>deletePageRole(int developerId, int pageId, int roleId)</li>

</ol>

deletes from table Role a record that removes roleId from developerId, on pageId

<h2>Implement Priviledge Data Access Object</h2>

In a file called <strong>PriviledgeDao.java</strong>​ ,​ implement a class that encapsulates all database access that manage website and page priviledges assigned to ​<strong>Developer</strong>​. Use the interface shown below. Feel free to implement additional or improved versions of the API




<h3>1. assignWebsitePriviledge(int developerId, int websiteId, String priviledge)</h3>

inserts into table Priviledge a record that assigns a developer whose id is developerId, the priviledge with priviledgeId, to the website with websiteId

<h3>2. assignPagePriviledge(int developerId, int pageId, String priviledge)</h3>

inserts into table Priviledge a record that assigns a developer whose id is developerId, the priviledge with priviledgeId, to the page with pageId

<ol start="3">

 <li><strong>deleteWebsitePriviledge(int developerId, int websiteId, String priviledge)</strong></li>

</ol>

deletes from table Priviledge a record that removes priviledgeId from developerId, on websiteId

<h3>4. deletePagePriviledge(int developerId, int pageId, String priviledge)</h3>

deletes from table priviledge a record that removes priviledgeId from developerId, on pageId




<h1>Exercise Your Data Model and DAOs (20pts.)</h1>

In a file called hw_jdbc_last_first.java, use the Data Model and Data Access Objects implemented earlier, to create the data shown below




<ol>

 <li>(5pts.) Create the following developers and users. Insert into the correct tables depending on the type</li>

</ol>




<table width="652">

 <tbody>

  <tr>

   <td width="41">id</td>

   <td width="83">Username</td>

   <td width="82">Password</td>

   <td width="66">First</td>

   <td width="68">Last</td>

   <td width="82">Type</td>

   <td width="149">Email</td>

   <td width="81">Key</td>

  </tr>

  <tr>

   <td width="41">12</td>

   <td width="83">alice</td>

   <td width="82">alice</td>

   <td width="66">Alice</td>

   <td width="68">Wonder</td>

   <td width="82">Developer</td>

   <td width="149"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="a2c3cecbc1c7e2d5cdccc6c7d08cc1cdcf">[email protected]</a></td>

   <td width="81">4321rewq</td>

  </tr>

  <tr>

   <td width="41">23</td>

   <td width="83">bob</td>

   <td width="82">bob</td>

   <td width="66">Bob</td>

   <td width="68">Marley</td>

   <td width="82">Developer</td>

   <td width="149"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="97f5f8f5d7faf6e5fbf2eeb9f4f8fa">[email protected]</a></td>

   <td width="81">5432trew</td>

  </tr>

  <tr>

   <td width="41">34</td>

   <td width="83">charlie</td>

   <td width="82">charlie</td>

   <td width="66">Charles</td>

   <td width="68">Garcia</td>

   <td width="82">Developer</td>

   <td width="149"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="abc8c3dec8c3ebcccad9c8c2ca85c8c4c6">[email protected]</a></td>

   <td width="81">6543ytre</td>

  </tr>

  <tr>

   <td width="41">45</td>

   <td width="83">dan</td>

   <td width="82">dan</td>

   <td width="66">Dan</td>

   <td width="68">Martin</td>

   <td width="82">Use</td>

   <td width="149"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="83e7e2edc3eee2f1f7eaedade0ecee">[email protected]</a></td>

   <td width="81">7654fda</td>

  </tr>

  <tr>

   <td width="41">56</td>

   <td width="83">ed</td>

   <td width="82">ed</td>

   <td width="66">Ed</td>

   <td width="68">Karaz</td>

   <td width="82">User</td>

   <td width="149"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="583d3c1833392a763b3735">[email protected]</a></td>

   <td width="81">5678dfgh</td>

  </tr>

 </tbody>

</table>




<ol start="2">

 <li>(5pts.) Create the following web sites for the developers above. For both the created field and updated field, use the date your assignment will be graded, e.g., do not hardcode it</li>

</ol>




<table width="652">

 <tbody>

  <tr>

   <td width="41">id</td>

   <td width="81">Name</td>

   <td width="251">Description</td>

   <td width="73">Owner</td>

   <td width="60">Editor</td>

   <td width="58">Admin</td>

   <td width="88">Visits</td>

  </tr>

  <tr>

   <td width="41">123</td>

   <td width="81">Facebook</td>

   <td width="251">an online social media and social networking service</td>

   <td width="73">alice</td>

   <td width="60">bob</td>

   <td width="58">charlie</td>

   <td width="88">1234234</td>

  </tr>

  <tr>

   <td width="41">234</td>

   <td width="81">Twitter</td>

   <td width="251">an      online     news     and      socialnetworking service</td>

   <td width="73">bob</td>

   <td width="60">charlie</td>

   <td width="58">alice</td>

   <td width="88">4321543</td>

  </tr>

  <tr>

   <td width="41">345</td>

   <td width="81">Wikipedia</td>

   <td width="251">a free online encyclopedia</td>

   <td width="73">charlie</td>

   <td width="60">alice</td>

   <td width="58">bob</td>

   <td width="88">3456654</td>

  </tr>

  <tr>

   <td width="41">456</td>

   <td width="81">CNN</td>

   <td width="251">an American basic cable andsatellite television news channel</td>

   <td width="73">alice</td>

   <td width="60">bob</td>

   <td width="58">charlie</td>

   <td width="88">6543345</td>

  </tr>

  <tr>

   <td width="41">567</td>

   <td width="81">CNET</td>

   <td width="251">an American media website that publishes reviews, news, articles, blogs, podcasts and videos ontechnology      and      consumer electronics</td>

   <td width="73">bob</td>

   <td width="60">charlie</td>

   <td width="58">alice</td>

   <td width="88">5433455</td>

  </tr>

  <tr>

   <td width="41">678</td>

   <td width="81">Gizmodo</td>

   <td width="251">a design, technology, science and science fiction website that also</td>

   <td width="73">charlie</td>

   <td width="60">alice</td>

   <td width="58">bob</td>

   <td width="88">4322345</td>

  </tr>

  <tr>

   <td width="41"></td>

   <td width="81"></td>

   <td width="251">writes articles on politics</td>

   <td width="73"></td>

   <td width="60"></td>

   <td width="58"></td>

   <td width="88"></td>

  </tr>

 </tbody>

</table>




<ol start="3">

 <li>(5pts.) Create the following pages for the web sites above. Use the semester’s start date for the created field. Use the assignment’s due date for the updated field.</li>

</ol>




<table width="653">

 <tbody>

  <tr>

   <td width="44">id</td>

   <td width="94">Name</td>

   <td width="173">Description</td>

   <td width="80">Website</td>

   <td width="59">Editor</td>

   <td width="78">Reviewer</td>

   <td width="67">Writer</td>

   <td width="58">Views</td>

  </tr>

  <tr>

   <td width="44">123</td>

   <td width="94">Home</td>

   <td width="173">Landing page</td>

   <td width="80">CNET</td>

   <td width="59">alice</td>

   <td width="78">bob</td>

   <td width="67">charlie</td>

   <td width="58">123434</td>

  </tr>

  <tr>

   <td width="44">234</td>

   <td width="94">About</td>

   <td width="173">Website description</td>

   <td width="80">Gizmodo</td>

   <td width="59">bob</td>

   <td width="78">charlie</td>

   <td width="67">alice</td>

   <td width="58">234545</td>

  </tr>

  <tr>

   <td width="44">345</td>

   <td width="94">Contact</td>

   <td width="173">Addresses, phones, and contact info</td>

   <td width="80">Wikipedia</td>

   <td width="59">charlie</td>

   <td width="78">alice</td>

   <td width="67">bob</td>

   <td width="58">345656</td>

  </tr>

  <tr>

   <td width="44">456</td>

   <td width="94">Preferences</td>

   <td width="173">Where users can configure theirpreferences</td>

   <td width="80">CNN</td>

   <td width="59">alice</td>

   <td width="78">bob</td>

   <td width="67">charlie</td>

   <td width="58">456776</td>

  </tr>

  <tr>

   <td width="44">567</td>

   <td width="94">Profile</td>

   <td width="173">Users can configure their personalinformation</td>

   <td width="80">CNET</td>

   <td width="59">bob</td>

   <td width="78">charlie</td>

   <td width="67">alice</td>

   <td width="58">567878</td>

  </tr>

 </tbody>

</table>




<ol start="4">

 <li>(5pts.) Create the following widgets for the pages shown.</li>

</ol>




<table width="650">

 <tbody>

  <tr>

   <td width="81">Name</td>

   <td width="73">Type</td>

   <td width="112">Text</td>

   <td width="61">Order</td>

   <td width="106">Width/Height</td>

   <td width="125">Url</td>

   <td width="92">Page</td>

  </tr>

  <tr>

   <td width="81">head123</td>

   <td width="73">heading</td>

   <td width="112">Welcome</td>

   <td width="61">0</td>

   <td width="106">null</td>

   <td width="125">null</td>

   <td width="92">Home</td>

  </tr>

  <tr>

   <td width="81">post234</td>

   <td width="73">html</td>

   <td width="112">&lt;p&gt;Lorem&lt;/p&gt;</td>

   <td width="61">0</td>

   <td width="106">null</td>

   <td width="125">null</td>

   <td width="92">About</td>

  </tr>

  <tr>

   <td width="81">head345</td>

   <td width="73">heading</td>

   <td width="112">Hi</td>

   <td width="61">1</td>

   <td width="106">null</td>

   <td width="125">null</td>

   <td width="92">Contact</td>

  </tr>

  <tr>

   <td width="81">intro456</td>

   <td width="73">html</td>

   <td width="112">&lt;h1&gt;Hi&lt;/h1&gt;</td>

   <td width="61">2</td>

   <td width="106">null</td>

   <td width="125">null</td>

   <td width="92">Contact</td>

  </tr>

  <tr>

   <td width="81">image345</td>

   <td width="73">image</td>

   <td width="112">null</td>

   <td width="61">3</td>

   <td width="106">50×100</td>

   <td width="125">/img/567.png</td>

   <td width="92">Contact</td>

  </tr>

  <tr>

   <td width="81">video456</td>

   <td width="73">youtube</td>

   <td width="112">null</td>

   <td width="61">0</td>

   <td width="106">400×300</td>

   <td width="125">https://youtu.be/h67VX51QXiQ</td>

   <td width="92">Preference s</td>

  </tr>

 </tbody>

</table>




<h1>Implement Updates (15pts.)</h1>

Using the DAOs implemented earlier, do the following updates

<ol>

 <li>Update developer – Update Charlie’s primary phone number to 333-444-5555</li>

 <li>Update widget – Update the relative order of widget head345 on the page so that it’s new order is 3. Note that the other widget’s order needs to update as well</li>

 <li>Update page – Append ‘CNET – ‘ to the beginning of all CNET’s page titles</li>

 <li>Update roles – Swap Charlie’s and Bob’s role in CNET’s Home page</li>

</ol>

<h1>Implement Deletes (15pts.)</h1>

Using the DAOs implemented earlier, do the following deletes

<ol>

 <li>Delete developer – Delete Alice’s primary address</li>

 <li>Delete widget – Remove the last widget in the Contact page. The last widget is the one with the highest value in the order field</li>

 <li>Delete page – Remove the last updated page in Wikipedia</li>

 <li>Delete website – Remove the CNET web site, as well as all related roles and privileges relating developers to the Website and Pages</li>

</ol>

<h1>Stored Procedures (10pts.)</h1>

Using the DAOs implemented, create stored procedures for the following cases.

<ol>

 <li>Create a Stored Procedure “getUnasnweredQuestions” which retrieves the question with most number of answers and no correct answer. Group the questions by module and print the question text and numbers of answer for the question. (5M)</li>

 <li>Create a Stored Procedure, “endorsedUsersforWeek”, which retrieves the 5 most endorsed users (having the most number of correct answers for the questions posted in the given week). If there multiple endorsed Users per week, sort by their First Name. (5M)</li>

</ol>

<h1>Deliverables</h1>

In the folder provided to you, submit your entire code into the directory on Github. And also make a submission on Blackboard with the submission text as your Github URL.


