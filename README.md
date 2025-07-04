# Shutdown Voting System for Ubuntu

A safety-oriented system that requires consensus from designated users before shutting down an Ubuntu server.

## Use
Run `shutdown_vote` to cast your vote, check status, or initiate a shutdown once all votes are in.

Run `cancel_shutdown` to withdraw your vote if you change your mind.


## Overview

This application provides a democratic approach to system shutdown management. It ensures critical servers aren't accidentally turned off while important users are working by requiring all designated eligible voters to approve a shutdown.

## Features

- **Voting System**: Only shuts down when all eligible voters agree
- **Status Tracking**: Easy-to-read status of current votes
- **Safety Guards**: Prevents accidental shutdowns
- **Vote Reset on Boot and SSH login**: All votes are cleared on system startup and ssh login

## Installation
sudo ./setup

## Configuration
sudo nano /opt/shutdown_system/eligible_voters.txt
