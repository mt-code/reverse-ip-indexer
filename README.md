## Reverse IP Indexer

A tool created to crawl the internet and create an index of domains and their associated IP addresses. This helps form a map of servers on the internet and can be useful for various analytical purposes.

### TODO:

- [ ] Create a function that generates random IP address and checks port 80/443
- [ ] For any open ports, check if it's a web server and if so spider it for domains
- [ ] For any domains found, store the associated IP in a database

### Extras:

- [ ] Check found domains for commonly used sub-domains to further increase our index
- [ ] Periodically go through previously found domains and check they are still live / up-to-date

