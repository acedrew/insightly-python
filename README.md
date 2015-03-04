Insightly For Python
======

NOTE: we are currently in the process of building out our version 2.2 API. The Python library is being updated to support both v2.1 and v2.2 (some features are only available in v2.2). The v2.2 branch is not complete, and is currently intended for testing purposes only. So be sure to use the master branch for now. We will make an announcement when v2.2 is ready for use beyond testing. 

======

The Insightly Python SDK makes it super easy to integrate Insightly into your Python applications and web services, as easy as:

  from insightly import Insightly
  
  i = Insightly()
  
  contacts = i.getContacts(orderby='DATE_UPDATED_UTC desc')


The library takes care of authentication and low level communication, so you can focus on building your custom application or service. 
