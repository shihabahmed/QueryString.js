#QueryString.js
A few javascript functions for working with query strings. Might come in handy sometimes.

##Usage
	var a = QueryString("key");

##Methods
####QueryStringCount
Returns the number of keys in the query string of the current URL. Can be used with External URL as well.

	var a = QueryStringCount();
	var b = externalURL.QueryStringCount();

####QueryString
Returns the value of the specified key in the query string of the current URL. This function can be used for external URL too.

	var a = QueryString("key");
	var b = externalURL.QueryString("key");

####Example
http://jsbin.com/faluveqayeya/2
