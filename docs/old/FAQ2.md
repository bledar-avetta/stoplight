# FAQ2

The beginning of an awesome article...

What type of API architecture is being used?

The API architecture being used is based on a REST API which is a standard API protocol utilized by many modern applications. REST leverages less bandwidth, making it generally faster for internet usage.

What output format is delivered?

JSON format data is returned including any errors in the API Responses (output).

What does the Supplier API search include?

The supplier API search shows information specific to your apikey and only displays Suppliers connected to your organization.

How accurate is the information being pulled?

The information pulled is live production data and is the most accurate, up to date information available.

What endpoints are provided?

The following Endpoints are provided:

    Suppliers provides a list of supplier’s profile information including flag status
    Suppliers Count provides the number of supplier records for that call
    PQF/Audits provides requested PQF or Audits data for that call
    Audits Count provides the number of audits data records for that call
    Hierarchy provides a list of hierarchy/site data with each parent ID
    Document provides a document file path
    Supplier ID provides a list of supplier profile information including flag status
    Insurance provides insurance policy names, types, and type details

What are the details of the Suppliers endpoints?

The Supplier(s) end point provides the following information:

    Supplier Name and Avetta ID
    Primary Contact
    Address
    Billing Address
    Avetta Account Status
    System Flags and Forced Flags information:
        Overall flag color and reasons
        Detail (line item level) flag color and reasons
    Supplier trades
    Service type (on-site/off-site)

What does the Audits endpoint provide?

The Audits end point data is coming from PQF / other audits and is mapped per client requirements. The data is presented in a Question and answer format.

What does the Documents endpoint provide?

The Documents end point provides the FILE PATH for documents so Clients can download the document using that path.

What does the Suppliers or Audit count endpoint provide?

The Suplier or Audits Count Endpoint provides the number of records available

What details does the ‘flags’ field provide?

The ‘flags’ field returns the flags for a specific supplier across all connections within your hierarchy. Suppliers with connections to more than one site will have flags displayed for each related site.

What type of flags are displayed?

Both forced flags and regular flags can be displayed. The forced flags are designated using the ‘is_forced’ field.

What are the ‘reasons’ being displayed describing?

The reasons being displayed are describing why a Supplier flag is a specific compliance color.

What contact information is being pulled for the ‘phone’ and ‘fax’ fields?

The ‘phone’ and ‘fax’ fields display the phone and fax number of the Suppliers’ indicated primary contact.

When is the ‘external_id’ field populated?

The ‘external_id’ field is populated whenever the external ID is provided. The Client ID, Type and External ID is displayed.

What is the frequency of the Pull?

Pulls can be provided Daily or As-Needed. Daily Pull is recommended for Supplier, Audit or Document Endpoints. Pull As-Needed is recommended for Suppliers and Audit Counts.

What is the maximum number of records that can be returned?

The maximum number of records that can be returned is 3,000, but each record provides deeper levels of information. You will have to make multiple calls through the API if more than 3,000 records are needed.

What is the response time?

The average response time is 10 to 15 seconds for every 3,000 supplier records

How do I access the API documentation?

Your account manager can provide you with a link and submit a ticket to request a login to Stoplight.io which contains all API technical documentation. An NDA will need to be signed before the Technical API Documentation is given.

What is Stoplight.io?

Stoplight.io is a web-based API management system that provides access to technical documentation and allows users to view and test code and responses.

How long does it take to receive an API Key?

It generally takes about 3 weeks to have an API key generated

