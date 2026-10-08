# Task 1 — Nginx Server Setup

## Objective

Set up an Nginx server to serve the custom HTML page provided by the organizers.

## Organizer HTML

http://10.10.110.79:3923/test/index.html

## Implementation

The organizer-provided HTML page was downloaded and placed in:

/var/www/html/index.html

Nginx was configured and started successfully.

## Verification

Nginx configuration was tested using:

```bash
sudo nginx -t
The command completed successfully with:

nginx: configuration file /etc/nginx/nginx.conf test is successful

The server was verified using:

curl -I http://172.28.234.35/

The HTTP response returned:

HTTP/1.1 200 OK

The organizer-provided HTML page was successfully served by Nginx.

## Result

Task 1 completed successfully.

## Evidence

Terminal output and screenshots are stored in:

PROOFS/TASK1/
