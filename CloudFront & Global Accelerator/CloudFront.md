* Improves read performance by caching the content at different edge locations. 
* 216 Point of Presence globally (edge locations)
* By having the content tdistributed globally, we get DDoS protection. Also [[AWS Shield]] and [[AWS Web Application Firewall]] can be integrated.

At a high level, edge locations are all around the world. If a client does a HTTP request into an edge location, then the edge location will see if it has it cached. If it doesn't have it in the cache it will forward the request to any of the previous [[CloudFront - Origins]] to get the request result. Then it will be caching it in a local cache for future requests.

### Related
* [[CloudFront vs S3 Cross Region Replication]]
* [[CloudFront Geo Restriction]]
* [[CloudFront - Pricing]]
* [[CloudFront - Cache Invalidations]]
#### Tags
#SAA-C03 #CDN 