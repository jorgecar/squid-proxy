# About The Project

A proxy server configured to hide the client's IP.

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Make sure you have an updated version of Docker

    $ docker --version
    Docker version 19.03.12, build 48a66213fe

### Installation

Clone the repo:
    
    $ git clone git@github.com:jorgecar/squid-proxy.git

### Usage

    sudo docker run -v $(pwd)/squid.conf:/etc/squid/squid.conf -p 3128:3128 sameersbn/squid:3.5.27-

Run with docker-compose:
    
    $ docker-compose up -d
    
Now you have your proxy server running on the port 3128.
