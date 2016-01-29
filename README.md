# LICIT-ROBOTS

LICIT-ROBOTS is a repository, containing files (robots.txt files, .htaccess, etc.) to help webmasters keep unwanted web robots (e.g. scraper bots, people search engines, seo tools, marketing tools, etc.) away from their websites but allow legitimate robots (e.g. search engines).

## Files

### Robots Exclusion Standard (robots.txt)

The robots.txt files in the `/robots-exclusion-standard/` directory conatin an (alphabetically ordered) whitelisting of legitimate web robots. Legitimate means the bots obey the Robots Exclusion Standard (robots.txt) and are somehow useful the website owner and other users.

Each bot is shortly described in a comment above the (list of) user-agent(s). Uncomment or delete bots (User-agents) you do not wish to allow on your website / which you do not need to visit your website.

There are two versions of LICIT-ROBOTS robots.txt file:

1. The regular file (inlc. comments)  
   `/robots-exclusion-standard/robots.txt`
2. The minified file (no comments)  
   `/robots-exclusion-standard/robots.min.txt`

If you use the minified version, do not forget to rename it to `robots.txt` to be affective.

### .htaccess files

The files in the `/htaccess/` directory contain several different pieces of information (e.g. User-agents, referers, etc.) useful to block unwanted bots in `.htaccess` files for Apache 2.2. Work in progress...

#### Apache documentation to access control

* [https://httpd.apache.org/docs/2.2/howto/access.html](https://httpd.apache.org/docs/2.2/howto/access.html)
* [https://httpd.apache.org/docs/2.4/howto/access.html](https://httpd.apache.org/docs/2.4/howto/access.html)
* [https://httpd.apache.org/docs/2.4/upgrading.html#access](https://httpd.apache.org/docs/2.4/upgrading.html#access)

***

## Warranty and Liability
Compared to the vastness of the topic of blocking bots, LICIT-ROBOTS is a very small, private project! The author makes absolutely no claims and representations to warranties regarding the accuracy or completeness of the information provided. However, you can use the files in this repository AT YOUR OWN RISK.

The descision which bot is wanted/unwanted is done by the author, who is very conservative and opinionated when it comes to blocking bots. However, the author's decisions should be sufficient for many. Adjust all files to your needs.

## License

<span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">LICIT-ROBOTS</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/jonasjacek/licit-robots" property="cc:attributionName" rel="cc:attributionURL">Jonas Jacek</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>. Permissions beyond the scope of this license may be available upon request at <a xmlns:cc="http://creativecommons.org/ns#" href="http://jonas.me/contact" rel="cc:morePermissions">http://jonas.me/contact</a>.

## Contribute

**Found a mistake? Want to help? Send a pull request!**
