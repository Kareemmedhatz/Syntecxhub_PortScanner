# Syntecxhub_PortScanner

## Port Scanner

This is a simple TCP port scanner written in Python.

## Description
The script scans ports from 1 to 1000 on a specific IP address (142.250.74.174) and checks whether each port is open or closed.

## How it works
- Uses Python socket library
- Tries to connect to each port
- If the connection is successful → the port is open
- Otherwise → the port is closed

## Usage
Run the script using:

python Syntecxhub_PortScanner.py

## Output
The program will print the status of each port (open or closed).
