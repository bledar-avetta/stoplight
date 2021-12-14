# FAQ

The beginning of an awesome article...

<div class="flex flex-1 z-1"><div class="flex flex-1 flex-col z-1"><div class="flex-1 flex flex-col z-1 relative"><div class="ProjectFileEditor flex flex-col overflow-x-scroll relative h-full"><div class="ThemeWrapper bg-white flex flex-col h-100 w-100"><div class="Hub flex flex-col h-full"><style>
        .HubHeaderItem:hover,
        .HubHeaderItem.is-active {
          color: #3B99FC;
        }
      
      .HubBlock-tab.active {
        border-color: #3B99FC !important;
      }

      .markdown-body a {
        color: #3B99FC;
      }

      .HubMain .text-active,
      .HubMain .hover\:text-active:hover,
      .HubMain .HubBlock-tab:hover {
        color: #3B99FC !important;
      }
    </style><div class="HubHeader print:hidden bg-white border-b border-grey-light"><div class="HubHeader-inner relative hidden sm:flex items-center h-16 p-0"><div class="HubHeaderMobile-sidebar-toggle h-16 w-16 flex items-center justify-center text-2xl is-light"></div><div class="FormDropdown HubHeaderMobile-title flex-grow text-center font-bold text-xl"><div role="listbox" aria-expanded="false" class="ui floating dropdown FormDropdown-inner" tabindex="0"><div class="text" role="alert" aria-live="polite">API FAQ</div><i aria-hidden="true" class="dropdown icon"></i><div class="menu transition"><div style="pointer-events: all;" role="option" aria-checked="false" aria-selected="false" class="item"><a class="text HubHeaderItem flex items-center text-lg mx-1 px-4 py-2 rounded font-bold with-image is-light hover:text-primary text-black cursor-pointer" aria-current="false" href="/avetta/client-api/version%2F2.0/main.hub.yml?view=%2F"><div class="HubHeaderItem-image flex items-center"><img src="https://next.stoplight.io/images/mark-light-bg.png" alt="Avetta API Documentation"> <div class="ml-4">Avetta API Documentation</div></div></a></div><div style="pointer-events: all;" role="option" aria-checked="true" aria-selected="true" class="active selected item"><a class="text HubHeaderItem flex items-center text-lg mx-1 px-4 py-2 rounded font-bold without-image is-light hover:text-primary text-black cursor-pointer" aria-current="false" href="/avetta/client-api/version%2F2.0/main.hub.yml?view=%2Fapifaq"><div class="HubHeaderItem-name">API FAQ</div></a></div><div style="pointer-events: all;" role="option" aria-checked="false" aria-selected="false" class="item"><a class="text HubHeaderItem flex items-center text-lg mx-1 px-4 py-2 rounded font-bold without-image is-light hover:text-primary text-black cursor-pointer" aria-current="false" href="/avetta/client-api/version%2F2.0/main.hub.yml?view=%2Fapi-reference%2FConnect"><div class="HubHeaderItem-name">Connect API Reference</div></a></div><div style="pointer-events: all;" role="option" aria-checked="false" aria-selected="false" class="item"><a class="text HubHeaderItem flex items-center text-lg mx-1 px-4 py-2 rounded font-bold without-image is-light hover:text-primary text-black cursor-pointer" aria-current="false" href="/avetta/client-api/version%2F2.0/main.hub.yml?view=%2Fwm-api-reference%2FWorkerManagement"><div class="HubHeaderItem-name">Worker Management API Reference</div></a></div></div></div></div><div class="HubHeaderMobile-sidebar-toggle h-16 w-16 flex items-center justify-center text-lg is-light"><svg aria-hidden="true" data-prefix="fas" data-icon="search" class="svg-inline--fa fa-search fa-w-16 " role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M505 442.7L405.3 343c-4.5-4.5-10.6-7-17-7H372c27.6-35.3 44-79.7 44-128C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c48.3 0 92.7-16.4 128-44v16.3c0 6.4 2.5 12.5 7 17l99.7 99.7c9.4 9.4 24.6 9.4 33.9 0l28.3-28.3c9.4-9.4 9.4-24.6.1-34zM208 336c-70.7 0-128-57.2-128-128 0-70.7 57.2-128 128-128 70.7 0 128 57.2 128 128 0 70.7-57.2 128-128 128z"></path></svg></div></div><div class="HubHeader-inner sm:hidden flex items-center h-24"><div class="HubHeader-section flex items-center flex-grow is-left"><a class="HubHeaderItem flex items-center text-lg mx-1 px-4 py-2 rounded font-bold with-image is-light hover:text-primary text-black cursor-pointer" aria-current="false" href="/avetta/client-api/version%2F2.0/main.hub.yml?view=%2F"><div class="HubHeaderItem-image flex items-center"><img src="https://next.stoplight.io/images/mark-light-bg.png" alt="Avetta API Documentation"> <div class="ml-4">Avetta API Documentation</div></div></a></div><div class="HubHeader-section flex items-center justify-end is-right flex-grow relative"><a class="HubHeaderItem flex items-center text-lg mx-1 px-4 py-2 rounded font-bold without-image is-active is-light hover:text-primary text-primary cursor-pointer" aria-current="false" href="/avetta/client-api/version%2F2.0/main.hub.yml?view=%2Fapifaq"><div class="HubHeaderItem-name">API FAQ</div></a><a class="HubHeaderItem flex items-center text-lg mx-1 px-4 py-2 rounded font-bold without-image is-light hover:text-primary text-black cursor-pointer" aria-current="false" href="/avetta/client-api/version%2F2.0/main.hub.yml?view=%2Fapi-reference%2FConnect"><div class="HubHeaderItem-name">Connect API Reference</div></a><a class="HubHeaderItem flex items-center text-lg mx-1 px-4 py-2 rounded font-bold without-image is-light hover:text-primary text-black cursor-pointer" aria-current="false" href="/avetta/client-api/version%2F2.0/main.hub.yml?view=%2Fwm-api-reference%2FWorkerManagement"><div class="HubHeaderItem-name">Worker Management API Reference</div></a><div class="HubHeader-search h-24 flex items-center"><div class="FormSearch HubSearch"><div class="ui category fluid search"><div class="ui icon input fluid"><input placeholder="Search..." type="text" tabindex="0" class="prompt" autocomplete="off" value=""><i aria-hidden="true" class="search icon"></i></div><div class="results transition"><div class="message empty"><div class="header">Search is only enabled in published Hubs.</div></div></div></div></div></div></div></div></div><div class="HubMain flex flex-1 relative"><div class="HubPage-wrapper flex-1 bg-white w-full overflow-y-scroll min-h-100"><div class="HubPage"><div class="HubPage-inner flex"><div class="HubPage-content flex-1 relative"><div class="HubPageBody"><div class="HubBlockList"><div class="HubBlock HubBlock--text flex is-viewing is-solo is-last is-padded"><div class="HubBlock-inner flex-1 w-full"><div class="HubBlock-content"><div class="MarkdownViewer markdown-body"><div class="HtmlViewer"><p><strong>What type of API architecture is being used?</strong></p>
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
</div></div></div></div></div></div></div><div class="HubPageFooter absolute pin-x pin-b"><a href="https://stoplight.io/documentation?utm_source=Avetta&amp;utm_medium=docs&amp;utm_campaign=powered_by" class="hover:text-primary transition-all" style="width: 100%; display: flex; visibility: visible; align-items: center; justify-content: center; max-width: 100%; height: 3rem; opacity: 0.75; color: rgba(19, 15, 33, 0.7); background: rgba(19, 15, 33, 0.075) none repeat scroll 0% 0%; padding: 0px 13px;"><div class="ml-1 pr-3 text-primary"><svg aria-hidden="true" data-prefix="fas" data-icon="bolt" class="svg-inline--fa fa-bolt fa-w-10 " role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><path fill="currentColor" d="M295.973 160H180.572L215.19 30.184C219.25 14.956 207.756 0 192 0H56C43.971 0 33.8 8.905 32.211 20.828l-31.996 240C-1.704 275.217 9.504 288 24.004 288h118.701L96.646 482.466C93.05 497.649 104.659 512 119.992 512c8.35 0 16.376-4.374 20.778-11.978l175.973-303.997c9.244-15.967-2.288-36.025-20.77-36.025z"></path></svg></div><div style="display: block; visibility: visible; color: rgba(19, 15, 33, 0.7);">Powered by <b>Stoplight</b></div></a></div></div></div></div></div></div><div class="pin absolute flex z--1" role="presentation"><div class="h-full flex-1 bg-grey-lightest"></div><div class="h-full flex-1 bg-white"></div></div></div><style>.Hub .ApiOperation--tryItOutTitle {
	display: none;
}

.Hub .ApiOperation--tryItOut {
	display: none;
}</style></div></div></div></div></div>