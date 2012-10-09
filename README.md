rrdtool-nginx
=============

<img src="http://logotype.se/serverStatsGenerated/connections-day.png">

simple graphics stats for nginx

Get started
===========

1. Make sure RRDTool and nginx are installed.

2. Edit your nginx .conf file with stub_status on.

    location /rrdtool-nginx {
        stub_status on;
        access_log   off;
    }

3. Run the rrdtool-nginx script.