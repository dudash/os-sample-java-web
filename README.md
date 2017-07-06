# OpenShift Example - Java Web App
Sample Java Web Application for use in OpenShift - uses the Red Hat Tomcat 8 image as a base.

If you're using Red Hat's OpenShift you should already have the Tomcat8 builder.

Use with the following command:
```oc new-app --name=myapp jboss-webserver30-tomcat8-openshift~https://github.com/dudash/openshiftexamples-javawebapp.git```

and expose a route for users to access it with:
```oc expose svc/myapp```
