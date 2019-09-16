<h1>Dive into the yuuvis<sup>®</sup> API</h1>
<p>The yuuvis<sup>®</sup> API lets you build new or enhance existing information management / document management solutions. Take the time to familiarize yourself with how the yuuvis<sup>®</sup> API works and what it can do for you. The <b>"Getting started ..."</b> will get you started. Move on to the <b>"How to ..."</b> section to learn more about each endpoint, read further background information and jump right in to the <a href="https://yuuvis.io/products" target="_blank">product</a>.</p>
<h2>Getting started ....</h2>
<p>The following information provides the foundation for you to work with the yuuvis<sup>®</sup> API.</p>
<ol>
   <li><a href="https://github.com/yuuvis/Documentation/wiki/Sign-Up" target="_blank">How to Sign Up for the Dev Platform ...</a></li>
   <li><a href="https://github.com/yuuvis/Documentation/wiki/Quick-start" target="_blank">Quick Start: API Intro Guide ...</a></li>
   <li><a href="https://yuuvis.io/docs/services/yuuvis-admin" target="_blank">Configuration and Settings</a> endpoints</li>
   <li><a href="https://yuuvis.io/docs/services/yuuvis-dms-core" target="_blank">Core Capabilities (CRUD)</a> endpoints</li>
</ol>
<h2>How to ...</h2>
<p>The following descriptions provide an introduction to the yuuvis<sup>®</sup> API. Learn how to upload documents (objects) into your centralized storage, retrieve and manage them. If you are new to content services and document management systems, please go through them in the order in which they are listed below. This order represents a logical progression in the knowledge of the product.</p>
<p>Please note that we use Java code samples for our "How to ..." descriptions.</p>
<ol>
   <!-- 
   <li><a href="https://yuuvis.io/how-to/login" target="_blank">Login to the yuuvis<sup>®</sup> API</a></li>-->
   <li><a href="https://github.com/yuuvis/Documentation/wiki/Import-and-store" target="_blank"><b>Import and Store Documents ...</b></a> 
      (<a href="https://github.com/yuuvis/Documentation/wiki/Import-and-store#ImportingDocumentsviaCoreAPI-ImportaSingleDocument" target="_blank">single</a> / <a href="https://github.com/yuuvis/Documentation/wiki/Import-and-store#ImportingDocumentsviaCoreAPI-ImportMultipleDocumentsinBatchMode" target="_blank">multiple</a>)
   </li>
   <!--
   <ul>
      <li><a href="https://github.com/yuuvis/Documentation/wiki/Compound-documents" target="_blank">Compound Documents ...</a></li>
   </ul>
   -->
   <li><a href="https://github.com/yuuvis/Documentation/wiki/Retrieve-documents" target="_blank"><b>Retrieve Documents ...</b></a> 
      (<a href="https://github.com/yuuvis/Documentation/wiki/Retrieve-documents#RetrievingDocumentsviaCoreAPI-RetrievingDocumentsviaObjectID" target="_blank">via ObjectID</a> / <a href="https://github.com/yuuvis/Documentation/wiki/Retrieve-documents#RetrievingDocumentsviaCoreAPI-RetrievingDocumentsviaSearchEndpoint" target="_blank">search endpoint</a> using <a href="https://github.com/yuuvis/Documentation/wiki/Query-language" target="_blank">query language</a>)
   </li>
   <li><a href="https://github.com/yuuvis/Documentation/wiki/Retrieve-history-entries" target="_blank"><b>Retrieve the History Entries of a Document ...</b></a> 
      (<a href="https://github.com/yuuvis/Documentation/wiki/Retrieve-history-entries#RetrievingtheHistoryEntriesofaDocument-TheHistoryEntry" target="_blank">structure</a> / 
      <a href="https://github.com/yuuvis/Documentation/wiki/Retrieve-history-entries#RetrievingtheHistoryEntriesofaDocument-RetrieveHistoryEntriesofaDocument" target="_blank">retrieving entries</a> / 
      <a href="https://github.com/yuuvis/Documentation/wiki/Retrieve-history-entries#RetrievingtheHistoryEntriesofaDocument-WhichHistoryEntriesAreThere?" target="_blank">entry types</a>)
   </li>
   <li><a href="https://github.com/yuuvis/Documentation/wiki/Update-documents" target="_blank"><b>Update Documents ...</b></a> 
      (<a href="https://github.com/yuuvis/Documentation/wiki/Update-documents#UpdatingDocumentsviaCoreAPI-UpdateMetadata" target="_blank">meta
      data</a> / 
      <a href="https://github.com/yuuvis/Documentation/wiki/Update-documents#UpdatingDocumentsviaCoreAPI-UpdateContent" target="_blank">content</a> / 
      <a href="https://github.com/yuuvis/Documentation/wiki/Update-documents#UpdatingDocumentsviaCoreAPI-Versioningversioning" target="_blank">versioning</a>)
   </li>
   <li><a href="https://github.com/yuuvis/Documentation/wiki/Delete-documents" target="_blank"><b>Delete Documents ...</b></a> 
      (<a href="https://github.com/yuuvis/Documentation/wiki/Delete-documents#DeletingDocumentsviaCoreAPI-DeleteaDocument" target="_blank">document</a> / 
      <a href="https://github.com/yuuvis/Documentation/wiki/Delete-documents#DeletingDocumentsviaCoreAPI-DeleteaVersionofaDocument" target="_blank">version</a> / 
      <a href="https://github.com/yuuvis/Documentation/wiki/Delete-documents#DeletingDocumentsviaCoreAPI-DeleteaReferencingDocument" target="_blank">link document</a> / 
      <a href="https://github.com/yuuvis/Documentation/wiki/Delete-documents#DeletingDocumentsviaCoreAPI-DeleteCompoundDocuments" target="_blank">compound document</a>)
   </li> 	
   <li><a href="https://github.com/yuuvis/Documentation/wiki/Rendition-requests" target="_blank"><b>Rendition Requests ...</b></a>
   (<a href="https://github.com/yuuvis/Documentation/wiki/Rendition-requests#FileTypes" target="_blank">file types</a> / <a href="https://github.com/yuuvis/Documentation/wiki/Rendition-requests#title-heading" target="_blank">extraction service</a>)</li>
   <li><a href="https://github.com/yuuvis/Documentation/wiki/Schema-definition" target="_blank"><b>Schema Definition ...</b></a> 
   (<a href="https://github.com/yuuvis/Documentation/wiki/Schema-definition#SchemaDefinition-Endpoints" target="_blank">retrieve, validate and update endpoints</a> /
         <a href="https://github.com/yuuvis/Documentation/wiki/Schema-definition#SchemaDefinition-Structure" target="_blank">structure</a>)
   </li>      
   <!-- <li><a href="https://github.com/yuuvis/Documentation/wiki/Rendition-requests" target="_blank">What are Rendition Requests?</a></li> -->
   <!-- <li><a href="https://github.com/yuuvis/Documentation/wiki/Query-language" target="_blank">CMIS-Based Query Language ...</a></li> -->
   <li><a href="https://github.com/yuuvis/Documentation/wiki/Glossary" target="_blank"><b>Glossary ...</b></a></li>
</ol>
<!-- <h2>Getting ready ....</h2> -->
<!-- <p>Just getting started with our yuuvis<sup>®</sup> API, or considering trying it for the first time? We've put together a list of requirements to help you get ready. </br>Dive right in and get started on your own.</p> -->
<!-- <ol>
   <li><a href="https://yuuvis.io/how-to/buildtool" target="_blank">Let a Build Tool Support you ...</a></li>
   <li><a href="https://yuuvis.io/how-to/requests" target="_blank">Configure your Client for HTTP Requests ...</a></li>
   <li><a href="https://yuuvis.io/how-to/permissions" target="_blank">Check out your Permissions ...</a></li>
</ol> -->
