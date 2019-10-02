# sample rest api used to demonstrate distributed tracing. 

This app has sleuth dependencies. Just having the dependency in classpath, enables tracing capabilities in the application.

## Log Format
[Application Name, Trace Id, Span Id, zipkin Trace Enabled/Disabled Flag]

eg: 
[hi,ef39eb1f0e8da9ca,1e4e7ee0950f23c8,false]
