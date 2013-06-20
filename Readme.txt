I recently started working on a project requiring data on local retailers. The first step was to get
names and addresses of local retailers/industries/restraunts from the local yellowpages. So, I tried
developing a script for webharvest, which would crawl the site and save all the data in a csv file. 
Then to position the retailerss on a map I needed a way to gecocode every address. As I had 46340
addresses and Bing allows 50000 addresses in a day, so i developed a script on webharvest which would
read from the .csv file containing addresses and then geocode it using the bing api and then store the 
lat/long coordinates in a separate file, which could be noe used to position the markers on a Bing map.
