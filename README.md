# WP-Access-Logger

With the WordPress Access Logger MU plugin (Must Use Plugin), you can log and analyze all access to your WordPress website that is directed to the index.php of your website.

## Log Viewer

In the Log Viewer, you can see the IP addresses with their user agent, client hints, language, Internet service provider, AbuseIP score, etc. The entries are rated based on user agent, client hints, language, and AbuseIP score.

![Access Logger - Log Viewer](images/Access%20Logger%20-%20Log%20Viewer.png)

### Blocked Entries

Blocked Entries are blocked by RewriteCond and RewriteRule in htaccess.

![Access Logger - Blocked Entries](images/Access%20Logger%20-%20Blocked%20Entries.png)

### Rate Limited Entries

Rate Limited Entries are blocked by the function access_logger_rate_limit.

![Access Logger - Rate Limited Entries](images/Access%20Logger%20-%20RateLimited%20Entries.png)

## Configuration

The Access-Logger use the API of ipinfo.io and abuseipdb.com to rate and display important information about the ip address.

![Access Logger - Third Party tools](images/Access%20Logger%20-%20Configuration.png)

## Robots.txt

The robots.txt file helps keep unwanted bots and crawlers away from your website.

As a first step to securing your WordPress installation, you should create a robots.txt file in the root directory of your website. This file helps keep unwanted bots and crawlers away from your website.

![Access Logger - Robots.txt](images/Access%20Logger%20-%20robots.png)

## .htaccess

The .htaccess file is the Swiss Army knife for configuring the Apache web server. It contains important security and redirection rules for your WordPress installation.

![Access Logger - htaccess](images/Access%20Logger%20-%20htaccess.png)

## Leassons Learned

It's not over yet! I spend many hours working with IPInfo.io, AbuseIPDB, threatbook.io, ChatGPT, and GitHub Copilot to detect and learn attack patterns and fake user agents.
