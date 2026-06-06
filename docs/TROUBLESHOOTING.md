# Troubleshooting Guide

## Problem

Website was not accessible through public IP.

## Investigation

1. Checked container status using docker ps
2. Checked nginx logs
3. Verified port 80 listening
4. Verified Security Group rules
5. Checked UFW firewall
6. Tested with curl

## Root Cause

Browser cache issue.

## Resolution

Opened application in incognito mode and verified connectivity.
