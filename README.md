What is Google Dorks?
Search engines are nothing but a blessing. There are billions of websites in existence, each with a unique domain name. Finding the right website to visit based on your interest and purpose would be painstakingly hard otherwise. Thankfully, search engines such as Google Search allow users to look up websites based on keywords. It’s simple, reliable, and extremely fast.

As a search engine, Google allows you to look up relevant domains through keywords. The same query-based search can be used to expose a website’s information, such as login credentials.

Google allows websites to index themselves in search results. This allows the websites to appear in search results when a user looks up the relevant keyword. Once the website has been admitted into the Google Search Console, Google’s bots will crawl all the listed pages and subdomains, and index and rank them in the search engine.

Dorks can be thought of as queries that the search engine considers legit and pulls up information from the website. There has even been evidence that Google Dorks can expose SQL injection vulnerabilities.

How Does Google Dorks Work?
The first thing to note here is that Google Dorks is not a hack. It does not allow you to gain access to a web server and steal information, such as credentials and financial information. What it does is provide information that then can be used for malicious activities, such as Phishing. It is one of the ways that hackers can collect information, then target users if they have enough relevant information.

So, Google Dorks is a search string that when used on Google Search, can pull information from a website that would typically not show through normal queries.

Google recognizes these search functions and allows them to look for specific information. For example, let’s you wanted to see all the indexed web pages of a particular website, the search string “site:” followed by the name of the website will pull up all the web pages that the search engine has indexed.

The search engine is able to bring that information to the front because the website has allowed those pages to be indexed.

If a website has accidentally exposed important information like login username and password to the search engine, it can be revealed through such search functions, which is what hackers do to find personal information.

But it’s not just personal information like names and passwords, but vulnerabilities like SSH private keys of a server and open FTP servers that can be searched using Google Search. Private keys are used for authorization to access a remote server. If a hacker obtains the SSH key of a web server, it can gain access to the core functionality of the website.

Examples of Google Dorks
Google Dorks queries can be found pretty easily on the internet. Some of the queries are useful for search engine optimization. Since Google does not block these queries, it is up to the individual how to use them. They are often used by the infosec communities to find vulnerabilities in the form of the exposed information, but they can also be used by malicious actors.

You can try Google dorks yourself. Here are some of Google dorks queries to try:

site: the query followed by the URL of the website shows all the web pages indexed by the search engine.
cache: the query shows the cached version of a website.
intitle: searches for specific keywords in titles.
inurl: searches for specific keywords in URLs.
filetype: this query pulls up all files with the specified file extension.
You can also use more than one query together, like pulling file types from a specified website.

These are some of the very basic Google dorks queries. It can get more complex. Here are some queries as examples:

intext:username filetype:log: this query finds log files and finds any text matching “username” in log files.
intext:password filetype:log: this query finds any text matching “password” in log files.
intile:index.of id_rsa -id_rsa.pub: the query will search for exposed SSH private keys.
filetype: log username putty: putty is a tool that’s used to generate SSH private keys and also connect to SSH servers. It logs the connections which can be exposed to Google. The query will find logs of putty with usernames.

Conclusion – Should You Be Worried?
Security is an essential factor that decides your privacy on the internet. While Google dorks is not a hacking technique, it exploits weaknesses that were left exposed to the internet. It also shows how powerful search engines have become.

Save your data from being exposed on an unsecured network like public Wi-Fi by using FastestVPN’s AES 256-bit encryption. Connect to a remote server to hide your identity on the internet
