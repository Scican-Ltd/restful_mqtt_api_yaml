<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="docs/img/Coltene_logo.png" alt="Logo">
  </a>

  <h3 align="center">Restful API / MQTT - Documentation | YAML Repo</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/Scican-Ltd/restful_mqtt_api_yaml"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="http://18.208.186.68/login">View Project</a>
    ·
    <a href="https://github.com/Scican-Ltd/restful_mqtt_api_yaml">View Yaml</a>
    ·
    <a href="https://github.com/Scican-Ltd/restful_mqtt_api_yaml/issues">Report Bug</a>
    ·
    <a href="https://github.com/Scican-Ltd/restful_mqtt_api_yaml/issues">Request Feature</a>
    ·
    <a href="https://synergo.atlassian.net/browse/SC-15">JIRA Ticket</a>
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## About The Project  

[![Product Name Screen Shot][product-screenshot]](http://18.208.186.68/login)

There are many great README templates available on GitHub, however, I didn't find one that really suit my needs so I created this enhanced one. I want to create a README template so amazing that it'll be the last one you ever need -- I think this is it.

Here's why:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should element DRY principles to the rest of your life :smile:

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have have contributed to expanding this template!

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Swagger](https://swagger.io/)
* [AsyncApi](https://www.asyncapi.com/)
* [Docker](https://www.docker.com/)
* [VueJS](https://vuejs.org/)
* [Cognito](https://aws.amazon.com/cognito/)

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Architecture
[![Web App Architecture][app-architecture]](https://github.com/Scican-Ltd/restful_mqtt_api_yaml)
* [restful_mqtt_api_yaml](https://github.com/Scican-Ltd/restful_mqtt_api_yaml)
* [Ec2 - Web App Host](https://github.com/Scican-Ltd/restful_mqtt_api_yaml)
* [S3-Secretes](https://www.asyncapi.com/)
  
### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```JS
   const API_KEY = 'ENTER YOUR API';
   ```



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/Scican-Ltd/restful_mqtt_api_yaml/graphs/contributors

[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/Scican-Ltd/restful_mqtt_api_yaml/issues

[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/company/coltene-whaledent/

[product-screenshot]: docs/img/screenshot.png
[app-architecture]: docs/img/architecture.png


The backend API for the UI-App 

The configuration, see: https://console.aws.amazon.com/cognito/users/?region=us-east-1#/pool/us-east-1_5S8wvQFY3/details?_k=r2uz40

# node-jwt-authentication-api

NodeJS JWT Authentication API

For documentation and instructions check out http://jasonwatmore.com/post/2018/08/06/nodejs-jwt-authentication-tutorial-with-example-api

    aws cognito-idp admin-set-user-password --user-pool-id "us-east-1_5S8wvQFY3"  --username "nicolicioiu.liviu" --password "Passw@rd1" --permanent

The config https://console.aws.amazon.com/cognito/users/?region=us-east-1#/pool/us-east-1_5S8wvQFY3/users?_k=krlmhw
    
    # aws --version

    aws-cli/1.18.220 Python/2.7.17 Linux/4.4.0-19041-Microsoft botocore/1.19.60
    aws cognito-idp admin-set-user-password --user-pool-id "us-east-1_5S8wvQFY3"  --username "nicolicioiu.liviu" --password "Passw@rd1" --permanent

To start the project in docker-compose, run

    docker-compose up -d [service]
    docker-compose up [service]
    docker-compose logs -f [service] 
    docker-compose down [service]
    docker-compose restart [service]
  
  







# api-docs-test

Showcasing GitHub actions setup to work with the API documentation webhooks. 
