# FAQ3

<div class="HtmlViewer"><p><strong>What type of API architecture is being used?</strong></p>
<p>The API architecture being used is based on a REST API which is a standard API protocol utilized by many modern applications. REST leverages less bandwidth, making it generally faster for internet usage.</p>
<p><strong>What output format is delivered?</strong></p>
<p>JSON format data is returned including any errors in the API Responses (output).</p>
<p><strong>What does the Supplier API search include?</strong></p>
<p>The supplier API search shows information specific to your apikey and only displays Suppliers connected to your organization.</p>
<p><strong>How accurate is the information being pulled?</strong></p>
<p>The information pulled is live production data and is the most accurate, up to date information available.</p>
<p><strong>What endpoints are provided?</strong></p>
<p>The following Endpoints are provided:</p>
<ul>
<li>Suppliers provides a list of supplier’s profile information including flag status</li>
<li>Suppliers Count provides the number of supplier records for that call</li>
<li>PQF/Audits provides requested PQF or Audits data for that call</li>
<li>Audits Count provides the number of audits data records for that call</li>
<li>Hierarchy provides a list of hierarchy/site data with each parent ID</li>
<li>Document provides a document file path</li>
<li>Supplier ID provides a list of supplier profile information including flag status</li>
<li>Insurance provides insurance policy names, types, and type details</li>
</ul>
<p><strong>What are the details of the Suppliers endpoints?</strong></p>
<p>The Supplier(s) end point provides the following information:</p>
<ul>
<li>Supplier Name and Avetta ID</li>
<li>Primary Contact</li>
<li>Address</li>
<li>Billing Address</li>
<li>Avetta Account Status</li>
<li>System Flags and Forced Flags information:
<ul>
<li>Overall flag color and reasons</li>
<li>Detail (line item level) flag color and reasons</li>
</ul>
</li>
<li>Supplier trades</li>
<li>Service type (on-site/off-site)</li>
</ul>
<p><strong>What does the Audits endpoint provide?</strong></p>
<p>The Audits end point data is coming from PQF / other audits and is mapped per client requirements. The data is presented in a Question and answer format.</p>
<p><strong>What does the Documents endpoint provide?</strong></p>
<p>The Documents end point provides the FILE PATH for documents so Clients can download the document using that path.</p>
<p><strong>What does the Suppliers or Audit count endpoint provide?</strong></p>
<p>The Suplier or Audits Count Endpoint provides the number of records available</p>
<p><strong>What details does the ‘flags’ field provide?</strong></p>
<p>The ‘flags’ field returns the flags for a specific supplier across all connections within your hierarchy. Suppliers with connections to more than one site will have flags displayed for each related site.</p>
<p><strong>What type of flags are displayed?</strong></p>
<p>Both forced flags and regular flags can be displayed. The forced flags are designated using the ‘is_forced’ field.</p>
<p><strong>What are the ‘reasons’ being displayed describing?</strong></p>
<p>The reasons being displayed are describing why a Supplier flag is a specific compliance color.</p>
<p><strong>What contact information is being pulled for the ‘phone’ and ‘fax’ fields?</strong></p>
<p>The ‘phone’ and ‘fax’ fields display the phone and fax number of the Suppliers’ indicated primary contact.</p>
<p><strong>When is the ‘external_id’ field populated?</strong></p>
<p>The ‘external_id’ field is populated whenever the external ID is provided. The Client ID, Type and External ID is displayed.</p>
<p><strong>What is the frequency of the Pull?</strong></p>
<p>Pulls can be provided Daily or As-Needed. Daily Pull is recommended for Supplier, Audit or Document Endpoints. Pull As-Needed is recommended for Suppliers and Audit Counts.</p>
<p><strong>What is the maximum number of records that can be returned?</strong></p>
<p>The maximum number of records that can be returned is 3,000, but each record provides deeper levels of information.  You will have to make multiple calls through the API if more than 3,000 records are needed.</p>
<p><strong>What is the response time?</strong></p>
<p>The average response time is 10 to 15 seconds for every 3,000 supplier records</p>
<p><strong>How do I access the API documentation?</strong></p>
<p>Your account manager can provide you with a link and submit a ticket to request a login to Stoplight.io which contains all API technical documentation. An NDA will need to be signed before the Technical API Documentation is given.</p>
<p><strong>What is Stoplight.io?</strong></p>
<p>Stoplight.io is a web-based API management system that provides access to technical documentation and allows users to view and test code and responses.</p>
<p><strong>How long does it take to receive an API Key?</strong></p>
<p>It generally takes about 3 weeks to have an API key generated</p>
</div>
