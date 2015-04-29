##Testing

####Load testing tools
- Gaitling: http://gatling.io/
- JMeter: http://jmeter.apache.org/
(JMeter How-to: https://www.digitalocean.com/community/tutorials/how-to-use-jmeter-to-record-test-scenarios)
- Boom for simple http benchmarking: https://github.com/rakyll/boom
- Loader.io (but alternatives like Gaitling are better - too many bugs and requires payment): loader.io
- Apache ab for pure page load times: http://httpd.apache.org/docs/2.2/programs/ab.html

####Load testing to-think-abouts
- Premature optimization?
- Know the purpose of your load testing don't do a 1000x just because.
- Establishing boundaries of the system. What makes it fall over? How does it behave when it falls over?
- Proving that a system can handle x traffic and given boundaries gracefully. Only optimize according to real data(real need), raising boundaries (caching, scaling etc).
