# Fail2Ban_Filters
These are the filters that I built for Fail2Ban that may be useful to others. Some follow fairly routine online recommendations and others I developed by trial and error. I'm sure some could be a bit more efficient, but they have been tested and work as of the time they were posted. Not all are still in use as I've added or removed containers over the years, but if you have questions, I may be able to help.

## Real or Remote IPs
One thing I don't address in this repository is the issue of passing the remote or "real IP" to the logs that Fail2Ban reads. This is a particularly important concept if you're using Docker and/or Cloudflare. So, when you set up any of these jails and filters, take the time to test them and look at the logs to be sure the IP you're seeing is the one you expect and not the Docker container IP or Cloudflares.
If you don't see the right IPs, you'll need to sort out how to correct that. Some are easy and others take some creativity to get right.

#### If you have any questions, please contact me.