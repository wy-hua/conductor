![Conductor](docs/docs/img/logo.png)

# Conductor
[![Github release](https://img.shields.io/github/v/release/Netflix/conductor.svg)](https://GitHub.com/Netflix/conductor/releases)
[![CI](https://github.com/Netflix/conductor/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Netflix/conductor/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/Netflix/conductor.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![NetflixOSS Lifecycle](https://img.shields.io/osslifecycle/Netflix/conductor.svg)]()

[![GitHub stars](https://img.shields.io/github/stars/Netflix/conductor.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/Netflix/conductor/stargazers/)
[![GitHub forks](https://img.shields.io/github/forks/Netflix/conductor.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/Netflix/conductor/network/)


Conductor is a platform originally created at Netflix to orchestrate microservices and events.
This Conductor repository is maintained by the team at [Orkes](https://orkes.io/content) and a group of volunteers from the community.

For more information, see [Main Documentation Site](https://orkes.io/content)


## Releases
The latest version is [![Github release](https://img.shields.io/github/v/release/Netflix/conductor.svg)](https://GitHub.com/Netflix/conductor/releases)
The next scheduled release is in Dec 2023.

## Resources
#### [Slack Community](https://join.slack.com/t/orkes-conductor/shared_invite/zt-xyxqyseb-YZ3hwwAgHJH97bsrYRnSZg)
We have an active [community](https://join.slack.com/t/orkes-conductor/shared_invite/zt-xyxqyseb-YZ3hwwAgHJH97bsrYRnSZg) of Conductor users and contributors on the channel.
#### [Documentation Site](https://orkes.io/content)
[Documentation](https://orkes.io/content) and tutorial on how to use Conductor

## Workflow SDKs
Conductor supports creating workflows using JSON and Code.  
SDK support for creating workflows using code is available in multiple languages and can be found at https://github.com/conductor-sdk


[Discussion Forum](https://github.com/conductor-oss/conductor/discussions): Please use the forum for questions and discussing ideas and join the community.


## Getting Started - Building & Running Conductor
###  Using Docker:
The easiest way to get started is with Docker containers. Please follow the instructions [here](https://conductor.netflix.com/devguide/running/docker.html). 

###  From Source:
Conductor Server is a [Spring Boot](https://spring.io/projects/spring-boot) project and follows all applicable conventions. See instructions [here](https://conductor.netflix.com/devguide/running/source.html).

## Database Requirements

* The default persistence used is Redis
* The indexing backend is [Elasticsearch](https://www.elastic.co/) (6.x)
* The default queues are [orkes-queues](https://github.com/orkes-io/orkes-queues)

## Other Requirements
* JDK 17+
* UI requires Node 14 to build. Earlier Node versions may work but is untested.

## Get Support
There are several ways to get in touch with us:
* [Slack Community](https://join.slack.com/t/orkes-conductor/shared_invite/zt-xyxqyseb-YZ3hwwAgHJH97bsrYRnSZg)

## Contributions
Whether it is a small documentation correction, bug fix or a new feature, contributions are highly appreciated. We just ask you to follow standard OSS guidelines. The [Discussion Forum](https://github.com/Netflix/conductor/discussions) is a good place to ask questions, discuss new features and explore ideas. Please check with us before spending too much time, only to find out later that someone else is already working on a similar feature.

`main` branch is the current working branch. Please send your PR's to `main` branch, making sure that it builds on your local system successfully. Also, please make sure all the conflicts are resolved.