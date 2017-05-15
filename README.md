A quick demo to show how the maven dependencies plugin can be used with OpenShift S2I for creating docker images from artefacts stored in a maven repository.

You can try it with:

    # oc new-build jboss-webserver30-tomcat8-openshift~https://github.com/fgiloux/ocp-mvn-deps.git
    # oc new-app ocp-mvn-deps
