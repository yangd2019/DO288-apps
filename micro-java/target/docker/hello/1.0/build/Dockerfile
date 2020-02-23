FROM fabric8/s2i-java:2.3
ENV AB_PROMETHEUS_OFF=true JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="Hello microservice using Thorntail" org.label-schema.version=1.0 org.label-schema.schema-version=1.0 org.label-schema.build-date=2020-02-23T18:58:06.691 org.label-schema.name="Red Hat Training Hello Java app" org.label-schema.vcs-ref=ff5ab13fb1ae15c6f3ac33633e9abb8bceb9be26 org.label-schema.vcs-url=https://github.com/yangd2019/DO288-apps
EXPOSE 8080 8778 9779
COPY maven /deployments/
