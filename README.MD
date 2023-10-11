# How the Web Works

#1 What is HTTP?
Hyper text transfer protocal is the protocal that browsers will use to access websites

#2 What is a URL?
Univseral resourse locator includes the protocal, the site name, port and resources of a given website.

#3 What is DNS?
Domain name server is like the phonebook of the internet. It will change a site into a ip address and port number.

#4 What is a query string?
A query string is extra information that comes from a form or a search bar. The server is given this information and is usually configured to change the page.

#5 What are two HTTP verbs and how are they different?
Get and post are to verbs. Most requests through a browser is a Get request. A Post request is when information is sent to the server and most of the time will change some aspect of the page.

#6 What is an HTTP request?
Some method that is asked of the server.

#7 What is an HTTP response?
A response is dependent on whther the request is valid and what type of verb was used. A response aim is to provide the requested resource.

#8 What is an HTTP header? Give a couple examples of request and response headers you have seen.
A header is used to pass additional information to the server. An example would be a accept-language header.

#9 What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
Your browser checks several locations to find the IP address for the website. Once found, the browser sents a Get request from the server. You get a response code, hopefully 200. The page would then repsond with the desired content