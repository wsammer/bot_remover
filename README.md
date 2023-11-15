# bot_remover
Removes unnecessary robots, spiders and crawlers from visiting your website by modifying htaccess file

The file bot_remover.txt contains the mod_rewrite rules for webserver.

You should replace http://192.168.1.2/ with whatever your website address is.

I have chosen to allow robots of google, bing, and duckduckgo.

If you want to add further types of robots, spiders and crawlers, include them in the list of google|bing|duckduckgo

The bots, spiders and crawlers are rejected with a 405 HTTP code, you can change that to whatever you want.
