# Pre-work

This section is broken up into the following steps:

1. [Setup](#1-setup)

## 1. Setup

### Mac OSX

Install SonarQube,

```
% brew install sonar
% brew install sonar-scanner

% sonar-scanner -v
INFO: Scanner configuration file: /usr/local/Cellar/sonar-scanner/4.4.0.2170/libexec/conf/sonar-scanner.properties
INFO: Project root configuration file: NONE
INFO: SonarScanner 4.4.0.2170
INFO: Java 1.8.0_191 Oracle Corporation (64-bit)
INFO: Mac OS X 10.15.6 x86_64

% sonar start
Starting SonarQube...
Started SonarQube.

% open http://localhost:9000/projects
```

