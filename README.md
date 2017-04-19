# jenkins-pipeline
Example of a jenkins pipeline

docker run -p 8080:8080 -p 50000:50000 jenkins

Configure your jenkins with default plugins.

Create a bunch of shell-based jobs i.e.
- build
- generate
- test
- deploy

Create your pipeline using the Jenkinsfile as groovy script and invoke your shell-based jobs from there in a pipeline.
- pipeline

https://jenkins.io/doc/book/pipeline/jenkinsfile/
