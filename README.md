# OuterLayer

OuterLayer is a small project where I log IP addresses that are TOR exit nodes. I have been scraping https://check.torproject.org/exit-addresses since July 2018. 

## Usage

Feel free to clone or download this repo as you see fit. You may also want to fetch the lists programatically:

```bash
wget https://raw.githubusercontent.com/maxthauer/OuterLayer/master/results/all-distinct-IPs.txt

wget https://raw.githubusercontent.com/maxthauer/OuterLayer/master/results/distinct-IPs-past-30-days.txt

```

Server side, I am logging IPs and the date on an hourly basis. Should you have a request for data I can provide, please feel free to contact me and I'll see what I can do.

