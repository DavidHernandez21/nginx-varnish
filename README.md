# nginx-varnish
using nginx as a ssl proxy, caching with varnish and then forward the request to nginx again before hitting the "web app"

Actually the "web app" is missing but you can easily add one instead of the two nginx servers "server1" and "server2"
As is the nginx-proxy cannot act as a load balancer for the two server donwstream becuase there are no explicit rules for forwarding and varnish caches the requests
