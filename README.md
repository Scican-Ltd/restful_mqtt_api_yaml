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
    <img src="https://www.coltene.com/fileadmin/deepscreen_core/Public/images/logo.svg" alt="Logo">
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
    <a href="https://github.com/Scican-Ltd/restful_mqtt_api_documentation">View Web APP</a>
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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam et convallis eros. Cras ut nunc tempor, placerat neque vitae, vestibulum nunc. -- I think this is it.

Here's why:
* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ac dictum leo. Fusce tempus est non eros posuere, in vehicula felis finibus.
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should element DRY principles to the rest of your life :smile:

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam et convallis eros. Cras ut nunc tempor, placerat neque vitae, vestibulum nunc. -- I think this is it!

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Swagger](https://swagger.io/)
* [AsyncApi](https://www.asyncapi.com/)

<!-- GETTING STARTED -->
## Getting Started

This portion of the project is related to the `restful_mqtt_api_yaml` repository in the following diagram. The developer will clone this project, add a new HTTPS or MQTT documentation locally or edit a exist one and push to the `ORIGIN`. A Github Action will make this change available in the EC2 server.

### Architecture
[![Web App Architecture][app-architecture]](https://github.com/Scican-Ltd/restful_mqtt_api_yaml)
* [restful_mqtt_api_documentation](https://github.com/Scican-Ltd/restful_mqtt_api_documentation)
* [Ec2 - Web App Host](https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#InstanceDetails:instanceId=i-092d8bedec5ab75f3)
* [S3 - authentication-keys-ec2-legacy](https://s3.console.aws.amazon.com/s3/buckets/authentication-keys-ec2-legacy?region=us-east-1&tab=objects)

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Visual Code + [Swagger Viewer](https://marketplace.visualstudio.com/items?itemName=Arjun.swagger-viewer) installed.
* [AsyncAPI ???](https://playground.asyncapi.io/?load=https://raw.githubusercontent.com/asyncapi/asyncapi/master/examples/2.0.0/simple.yml) We can use the AsyncAPI PLAYGROUND in order to edit the yaml file and then copy+paste to this repository and then push to `ORIGIN`. But this is not the requirement.

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
