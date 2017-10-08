In an attempt to make communication between developers and to on-ramp non-technical people faster  
we attempt to isomorph & merge as many libraries, frameworks, as possible. Configs, dependency management
should be able to be spread across different repositories with minimal changes. We use a small array of tools
but make sure we know the ins and outs of all of them.

#Frameworks
* React
* React Native for Mobile

#Infrastructure
We're an Amazon shop. No service that can be found off Amazon as a competitor should be used. 
Digital Ocean, Linode, etc.
Following are permissible AWS services:
* EC2
* ECS
* S3
* Lambda

#Node
* Version 8.5 wherever possible if not see below
* Latest version of Node possible on the service depended on.

#NPMJS
* All HTTP requests should use the fetch API: use node-fetch for server-side.
* Build tools : NPM, Yarn




