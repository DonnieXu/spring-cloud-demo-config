# spring-cloud-demo-config
When I put the config files directly in repository 'spring-cloud-demo' and I often get a 'java.net.SocketTimeoutException: Read timed out' exception.   
So I read some others' code, I find that they will cresate a pure repository to hold all these config files. This help me to resolve the problem above.