This is a repo for the AWS cloud resume challenge, I am recording the steps i take as i emback in this cloud journey to get better

from the basic architectur above we are working in setting up the following

1. a resume which has been codded in HTML with bootstrap css,
  users will connect to the resume website throught a custom secure DNS tmresume.com which is pointed to the 
  HTTPs Load balancer which also leverages caching technologies of a content delivery network CDN


2. The DNS. here i bought a domain tmresume.com from a dns provider. implemented an SSL to it then added the load balancer's IP adrees to the A-record of my Domain t
   this is to point the domain to the loadbalancer 
