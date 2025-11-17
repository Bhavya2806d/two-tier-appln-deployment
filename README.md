# two-tier-appln-deployment
using eks cluster -aws

error encountered-
edit load balancer d=security group add inbound rule
Type: HTTP
Port: 80
Source: ::/0 (Allow IPv6)

try locally 
curl -I http://a362a95fd465940cd96a5098a93be840-1681703291.eu-north-1.elb.amazonaws.com

ubuntu@ip-172-31-23-32:~$ curl -I http://a362a95fd465940cd96a5098a93be840-1681703291.eu-north-1.elb.amazonaws.com HTTP/1.1 200 OK Server: Werkzeug/2.3.7 Python/3.9.18 Date: Mon, 17 Nov 2025 16:55:14 GMT Content-Type: text/html; charset=utf-8 Content-Length: 2573 Connection: close

Your LoadBalancer is reachable and returning:
HTTP/1.1 200 OK

try again in browser
http://a362a95fd465940cd96a5098a93be840-1681703291.eu-north-1.elb.amazonaws.com
