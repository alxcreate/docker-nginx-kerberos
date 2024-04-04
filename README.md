# Nginx with Kerberos Auth in Docker

This is a simple example of how to use Nginx with Kerberos authentication in Docker.

## How to use

1. Clone this repository;
    - Replace key and certificate files with your own in the `nginx/certs` directory;
    - Edit the `krb5.conf` file with your domain information.
2. Run `docker-compose up -d`;
3. Open your browser and go to `https://localhost`;
4. You should be prompted for your domain username and password.
