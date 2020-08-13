# Intro
CDN - Content Delivery Network
> Problem - Let's say out main data center is in Ohio (US), and a person from japan requests an image, our cloud provider will store this image in Japan's Data center, and the next person to request that image in Japan will recieve it much faster.

## What is it and its benefits.
A CDN refers to a group of servers distributed geographically, which works together to distribute content faster (e.g - html pages, js files, images, videos).

*** Benefits ***
1. Improving Website Performance - By distributing the content closer to website visitors by using a nearby servers users experience faster loading time.
2. Increasing Reliability and availaibilty because copies of your files are now held in multiple edge locations around the world.
3. Reducing BW costs.

### Example
AWS Cloudfront
1. When a users request content that you are serving through cloudfront, the user is routed to the location that provides lowest latency (time delay), so that content is delivered in best possible time.
2. If the content is already not in that edge location, Cloudfront fetches it from the defined origin - S3, a web server etc so that it can be forwarded the next time.


### References
AWS Cloudfront - https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html
What is CDN (cloud fare) - https://www.cloudflare.com/learning/cdn/what-is-a-cdn/