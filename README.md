# searo-dashboard
DHSR042-WHO_SEARO-DHIS2 Dashboard Support

Basic requirement is to develop a dashboard with tables, charts, maps in the login screen for public­ Any user can view & generate dashboard without logging in to theapplication.

Approach :
1. Configure reverse proxy for the instance: Reverse proxy is a type of proxy server that
retrieves resources on behalf of a client from one or more servers. These
resources are then returned to the client as though they originated from the proxy
server itself. Below is the document to setup reverse proxy based upon nginx.
Reverse Proxy Configuration
2. Create an OAuth2 client : OAuth2 protocol will be used to grant the dhis access to the
application. A dedicated oauth2 client will be created in dhis and that credentials will be
used in the application to access Dhis application.
Below is the document to create oauth2 client in dhis
OAuth Authentication
3. Finalize dashboard design: For generation of charts , tables & maps we are going to use
Dhis plugins. DHIS 2 comes with plugins which enables you to embed live data directly in
your web portal or web site. Currently, plugins exist for charts, maps and pivot tables.
DHIS plugins
