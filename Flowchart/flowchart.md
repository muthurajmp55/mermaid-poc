# This is flow chart for Property HUB

````mermaid
graph TD
Propertyhub --> Frontend
Propertyhub --> Backend
Backend --> Django --> Apps
Frontend --> React
Apps --> property_info
Apps --> clients
Apps --> User
User --> login
User --> logout
User --> Signup
User --> Changepassword
User --> update_User
User --> delete_User
property_info --> View_properties
property_info --> update_property
property_info --> deleter_property
clients --> client_view_page
clients --> update_client
clients --> Delete_client
clients --> datagrid
datagrid --> update
datagrid --> delete
React --> Routes
Routes --> properties
Routes --> PropertyName
Routes -->Home
Routes --> addclient
Routes --> property_form
Routes --> property_form
Routes --> propertyName
Routes --> client_form
Routes --> super_admin
Routes --> add_user
Routes --> login
Routes --> change_password