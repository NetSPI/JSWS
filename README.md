# JSWS

Burp Extenstion to parse JavaScript WebService Proxies and create sample requests.

The blog explaining JSWS and the use case can be found at https://blog.netspi.com/attacking-javascript-web-service-proxies-burp/

## Download

The plugin can be downloaded from the releases tab and loaded into Burp under the Extender tab.

## Use

Right click a request or response containing the JSWS and select Parse JSWS.

![alt-tag](https://blog.netspi.com/wp-content/uploads/2017/02/parse-JSWS.png)

This will send the request to the JSWS tab and parse out all possible reqeusts.

![alt-tag](https://blog.netspi.com/wp-content/uploads/2017/02/JSWS-tab.png)

From this tab you can send any of the newly crafted requests to Repeater, Scanner, Intruder, etc.
