# httpd-gcsfuse
dockerbuild -t httpd-gcsfuse:latest .

# k8s deployment
- create secret from google service account key
- mount secret to container
- add environemnt variable
    name: GOOGLE_APPLICATION_CREDENTIALS
    value: secret mount path
