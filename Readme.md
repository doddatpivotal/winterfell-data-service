# Winterfell Data Service

Includes following standards for data services:

- Coding Style Enforced by Checkstyle Using Google's Java Standard
- FlyWay DB
- Actuator
- Wavefront
- Lombok
- Build Info in Actuator
- Properties File Standards
- Oauth Resource Server
- POM Files Standards
- Maven Build: Prefer Maven build over gradle

Spring Configuration will be pulled from Spring Config Server when deployed to k8s using the k8s profile. This contains information like:
- Enable wavefront
- Wavefront proxy information
- Oauth jwk-set-uri given expectation of sitting beyond SCG
