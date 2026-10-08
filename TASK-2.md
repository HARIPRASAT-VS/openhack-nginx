# Task 2 — Access from Another Device

## Objective

Access the Nginx-hosted custom HTML page from another device on the same network.

## Network

Windows LAN IP:

10.10.159.219

WSL IP:

172.28.234.35

## Access URL

http://10.10.159.219:8081/

## Network Configuration

Windows port 8081 was forwarded to the WSL Nginx HTTP service:

10.10.159.219:8081
        ↓
172.28.234.35:80
        ↓
Nginx
        ↓
Organizer HTML

## Verification

The organizer's custom HTML page was successfully accessed from another device.

## Result

HTTP/1.1 200 OK

The page content displayed:

Linux Community - OpenHack Hackathon

## Evidence

Terminal output is available in:

evidence/task-2-output.txt

A screenshot of the page accessed from another device is included in:

screenshots/task-2-other-device.png

## Status

COMPLETED
