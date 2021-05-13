# Awesome Site Reliability Engineering Tools [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

<!--lint ignore no-dead-urls--> 

A curated list of Site Reliability and Production Engineering tools

## Contents

- [Development](#development)
  - [Source Code Management](#source-code-management)
  - [Project Management &amp; Issue Tracking Software](#project-management--issue-tracking-software)
  - [Bug / Defect Tracking Software](#bug--defect-tracking-software)
  - [Code Editors and IDE's](#code-editors-and-ides)
- [Continous Testing](#continous-testing)
- [Continous Integration](#continous-integration)
  - [Build](#build)
  - [Integration](#integration)
- [Continous Delivery](#continous-delivery)
  - [Deployment](#deployment)
  - [Infrastructure orchestration](#infrastructure-orchestration)
  - [Container](#container)
  - [Docker Registry](#docker-registry)
  - [Container Orchestration](#container-orchestration)
- [Continous Monitoring](#continous-monitoring)
- [Incident Management / Incident Response / IT Alerting / On-Call](#incident-management--incident-response--it-alerting--on-call)
  - [IT Service Management](#it-service-management)

## Development
### Source Code Management
- [Git](https://git-scm.com/)
- [Fossil](https://www.fossil-scm.org/)
- [CVS](https://www.nongnu.org/cvs/)
- [Subversion](https://subversion.apache.org/)
- [Mercurial](https://www.mercurial-scm.org/)
- [GitHub](https://github.com/)
- [Gitlab](https://about.gitlab.com/)
- [Bitbucket](https://bitbucket.org/)

### Project Management & Issue Tracking Software
- [Jira](https://www.atlassian.com/software/jira)
- [Trello](https://trello.com/)
- [Zoho Sprints](https://www.zoho.com/sprints/)
- [Taiga](https://taiga.io/)
- [Wrike](https://www.wrike.com/)
- [Asana](https://asana.com/)
- [monday.com](https://monday.com/)

### Bug / Defect Tracking Software
- [Bugzilla](https://www.bugzilla.org/)
- [Bugsee](https://www.bugsee.com/)
- [Instabug](https://instabug.com/)
- [Zoho BugTracker](https://www.zoho.in/bugtracker/)
- [Bugasura](https://bugasura.io)

### Code Editors and IDE's
- [GNU Emacs](https://www.gnu.org/software/emacs/)
- [Notepad++](https://notepad-plus-plus.org/)
- [Atom](https://atom.io/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Sublime Text](https://www.sublimetext.com/)
- [Vim](https://www.vim.org/)
- [Eclipse](https://www.eclipse.org/downloads/)
- [GNU Nano](https://www.nano-editor.org/)
- [UltraEdit](https://www.ultraedit.com/)
- [TextMate](https://macromates.com/)
- [gedit](https://gitlab.gnome.org/GNOME/gedit/)
- [WebStorm](https://www.jetbrains.com/webstorm/)

## Continous Testing
- [Selenium](https://www.seleniumhq.org/)
- [JUnit](https://junit.org/)
- [TestNG](https://testng.org/doc/index.html)
- [NUnit](https://nunit.org/)
- [TestSigma](https://testsigma.com/)
- [Unified Functional Testing (UFT)](https://www.microfocus.com/en-us/products/unified-functional-automated-testing/overview)
- [Tricentis Tosca](https://www.tricentis.com/products/automate-continuous-testing-tosca/)
- [IBM Rational Functional Tester](https://www.ibm.com/in-en/marketplace/rational-functional-tester)
- [TestComplete](https://smartbear.com/product/testcomplete/overview/)
- [Waitr](http://watir.com/)
- [Zephyr](https://www.getzephyr.com/)
- [accelQ](https://www.accelq.com/)
- [Apache jMeter](https://jmeter.apache.org/)
- [Appium](http://appium.io/)

## Continous Integration
### Build
- [Ninja](https://ninja-build.org/)
- [Meson](https://mesonbuild.com/)
- [CMake](https://cmake.org/)
- [Autotools/Automake](https://www.gnu.org/software/automake/)
- [premake](https://premake.github.io/)
- [Maven](https://maven.apache.org/)
- [Ant](https://ant.apache.org/)
- [Gradle](https://gradle.org/)
- [Make](https://www.gnu.org/software/make/)
- [Cake](https://cakebuild.net/)
- [Rake](https://ruby.github.io/rake/)
- [MS Build](https://www.microsoft.com/en-us/build)
- [Drill](https://gitlab.com/aki237/drill)
- [Hydra](https://nixos.org/hydra/)

### Integration
- [Jenkins](https://jenkins.io/)
- [Bamboo](https://www.atlassian.com/software/bamboo)
- [Hudson](http://hudson-ci.org/)
- [CircleCI](https://circleci.com)
- [TeamCity](https://www.jetbrains.com/teamcity/)
- [Gitlab CI](https://about.gitlab.com/product/continuous-integration/)
- [Travis CI](https://travis-ci.org/)
- [AWS CodeStar](https://aws.amazon.com/codestar/)
- [Buildbot](http://buildbot.net/)
- [Semaphore CI](https://semaphoreci.com/)
- [Concourse CI](https://concourse-ci.org/)
- [Abstruse CI](https://github.com/bleenco/abstruse)
- [Appcenter](https://appcenter.ms/)
- [Appveyor](https://ci.appveyor.com/)
- [Assertible](https://assertible.com/)
- [Badwolf](https://github.com/bosondata/badwolf)
- [Britise](http://bitrise.io/)
- [Buildkite](https://buildkite.com/)
- [Chrono CI](http://www.chronoci.com/)
- [Codacy](https://www.codacy.com/)
- [CodeClimate](https://www.codeclimate.com/)
- [CodeFresh](https://codefresh.io/)
- [Codeship](https://www.codeship.io/)
- [Continousphp](https://continuousphp.com/)
- [Drone](https://drone.io/)
- [Hound CI](https://houndci.com/)
- [Probo.CI](https://probo.ci/)
- [Solano CI](https://xebialabs.com/technology/solano-ci/)
- [Visual Studio Team Services](https://www.visualstudio.com/team-services/)
- [Go CD](https://www.gocd.org/)


## Continous Delivery
### Deployment
- [AWS CodeDeploy](https://aws.amazon.com/codedeploy/)
- [ElectricFlow](http://electric-cloud.com/products/electricflow/)
- [Octopus Deploy](https://octopus.com/)
- [IBM UrbanCode](http://www-03.ibm.com/software/products/en/ucdep)
- [DeployBot](https://deploybot.com/)
- [Shippable](https://app.shippable.com/)
- [Codar Continous Delivery](https://www.microfocus.com/en-us/products/codar-continuous-deployment/overview)
- [Wercker](https://app.wercker.com/)
- [Humanitec](https://humanitec.com/)
- [ArgoCD](https://argo-cd.readthedocs.io/en/stable/)

### Infrastructure orchestration
- [Vagrant](https://www.vagrantup.com/)
- [Puppet](https://puppet.com/)
- [Chef](https://www.chef.io/)
- [SaltStack](https://www.saltstack.com/)
- [Ansible](https://www.ansible.com/)
- [Terraform](https://www.terraform.io/)
- [AWS CloudFormation](https://aws.amazon.com/cloudformation/)

### Container
- [Docker](https://www.docker.com/)
- [Turbo.NET](https://turbo.net/)
- [WinDocks](https://windocks.com/)

### Docker Registry
- [Docker Hub](https://hub.docker.com/)
- [Google Container Registry](https://cloud.google.com/container-registry/)
- [Amazon ECR](https://aws.amazon.com/ecr/)
- [Gitlab Container Registry](https://about.gitlab.com/2016/05/23/gitlab-container-registry/)
- [JFrog Artifactory](https://jfrog.com/artifactory/)
- [Quay.io](https://quay.io/)
- [Azure Container Registry](https://azure.microsoft.com/en-in/services/container-registry/)
- [Oracle Container Registry](https://container-registry.oracle.com)
- [Nexus Container Registry](https://help.sonatype.com/repomanager3/formats/docker-registry)

### Container Orchestration
- [Kubernetes](https://kubernetes.io/)
- [Docker Swarm](https://docs.docker.com/engine/swarm/)
- [Apache Mesos](http://mesos.apache.org/) - with [Marathon](https://mesosphere.github.io/marathon/)

## Continous Monitoring
- [AWS CloudWatch](https://aws.amazon.com/cloudwatch/)
- [Prometheus](https://prometheus.io/)
- [StackDriver](https://cloud.google.com/stackdriver/)
- [Sensu](https://sensu.io/)
- [Sentry](https://sentry.io/welcome/)
- [CopperEgg](https://www.idera.com/infrastructure-monitoring-as-a-service)
- [Crashlytics](https://fabric.io/kits/android/crashlytics)
- [Kapacitor](https://www.influxdata.com/time-series-platform/kapacitor/)
- [loggly](https://www.loggly.com/)
- [logmatic](https://logmatic.io/)
- [Logstash](https://www.elastic.co/products/logstash)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) 
- [MongoDB Cloud Manager](https://www.mongodb.com/cloud/cloud-manager)
- [NewRelic](https://newrelic.com/)
- [Papertrail](https://papertrailapp.com/)
- [Pingdom](https://tools.pingdom.com/)
- [ServerDensity](https://www.serverdensity.com/)
- [Zabbix](https://www.zabbix.com/)
- [InsightOps](https://www.rapid7.com/products/insightops/)
- [AppSignal](https://appsignal.com)
- [Grafana](https://grafana.com)
- [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/)

## Incident Management / Incident Response / IT Alerting / On-Call
- [Squadcast](https://www.squadcast.com)
- [PagerDuty](https://www.pagerduty.com/)
- [VictorOps](https://victorops.com/)
- [OpsGenie](https://www.opsgenie.com/)
- [AlertOps](https://alertops.com/)
- [Blameless](https://www.blameless.com/)
- [Jira Ops](https://www.atlassian.com/software/jira/ops)
- [OnPage](https://www.onpage.com/)
- [PagerTree](https://pagertree.com/)
- [Cabot](https://cabotapp.com/)
- [AlertAgility](http://www.alertagility.com/)
- [xMatters](https://www.xmatters.com/)
- [Derdack Enterprise Alert](https://www.derdack.com/)
- [Bigpanda](https://www.bigpanda.io/)
- [OpenDuty](https://github.com/ustream/openduty)
- [ngDesk](https://www.ngdesk.com/)
- [Geneos](https://www.itrsgroup.com/products/geneos)
- [FireHydrant](https://www.firehydrant.com)
- [SLO exporter](https://github.com/seznam/slo-exporter)
- [SLO Calculator](https://github.com/last9/slo-computer)


### IT Service Management
- [FreshService](https://freshservice.com/)
- [ServiceNow](https://www.servicenow.com/)
- [BMC Remedy](http://www.bmcsoftware.in/it-solutions/remedy-itsm.html)
- [Jira ServiceDesk](https://www.atlassian.com/software/jira/service-desk)
- [Samanage](https://www.samanage.com/)
- [Cherwell](https://www.cherwell.com/products/it-service-management/)
- [SysAid](https://www.sysaid.com/it-service-management-software)
- [ManageEngine Servicedesk plus](https://www.manageengine.com/products/service-desk/)


## Licence

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
