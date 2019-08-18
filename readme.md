<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better please fork the repo and create a pull request or simple open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->





<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for build-url, contributors-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Build Status][build-shield]][build-url]
[![Contributors][contributors-shield]][contributors-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">NeatCourses</h3>

  <p align="center">
    I embarked upon a journey with little resource, little hope but with enormous zeal... 
    <br />
    <a href="https://github.com/shishir1310/shoppingkori-master"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/shishir1310/shoppingkori-master">View Demo</a>
    ·
    <a href="https://github.com/shishir1310/shoppingkori-master/issues">Report Bug</a>
    ·
    <a href="https://github.com/shishir1310/shoppingkori-master/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
  * [Feature List](#feature-list)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project
ShoppingKori is an online shopping application which offers a digital platform for
vendors as well as customers for selling and buying Bengali Products.
# Feature List
- Academic Year manage
- Academic Calendar Setup
- Institute Setup
- Class & Section
- Subject & Teacher
- Student Admission
- Student Attendance
- Exam & Grading Rules
- Makrs & Result
- Employees Manage
- Employees Attendance
- Employees Leave
- Employees Work Outside
- SMS Gateway Setup 
- Attendance notification email/sms 
- Student & Employee Id-Card mass print with templates
- User & Role manage with permision grid(ACL)
- User wise Dashboard
- Report Settings
- Reports
- Dynamic Front Website
- Website Management Panel
- Photo Gallery
- Event Manage
- Google Analytics
- User Notificateion

Technology is supposed to make our life easier and convenient. So I embarked upon a journey to complete this project with enormous zeal. Having taken a few gallant strides forward, I took my time, I sat back to contemplate what more I could develop to make our life easier and comfortable. As a person, I do not aim at confining ourselves within the realm of existing technology. So I hereby call all the creative, thinking minds in open arms to contribute in this project and enrich myself with myriads of creative excellence and challenge myself to develop something fresh everyday and stand out from the rest.

### Built With
* [LoopBack](https://loopback.io/): LoopBack is a highly extensible, open-source Node.js framework based on Express that enables to quickly create APIs and microservices composed from backend systems such as databases and REST services. 
* [MongoDB](https://www.mongodb.com/): MongoDB is a document database with the scalability and flexibility that you want with the querying and indexing that you need. 


<!-- GETTING STARTED -->
## Getting Started

To set this project locally follow the following instructions:
### Prerequisites

Following things that need to installed in the machine.
- PHP >= 7.1.3
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension
- Ctype PHP Extension
- JSON PHP Extension
- NodeJS, npm, webpack

### Installation

```
$ git clone https://github.com/shishir1310/neatCourses-master.git

```
```
$ cd neatCourses-master
```
```
$ cp .env.example .env
```
**Change configuration according to your need in ".env" file and create Database**
```
$ composer install
```
```
$ php artisan migrate
```
```
$ php artisan db:seed
```
**Load demo data**
```
$ php artisan db:seed --class DemoSiteDataSeeder
```
```
$ php artisan db:seed --class DemoAppDataSeeder
```
**Clear cache**
```
$ sudo php artisan cache:clear
```
```
$ npm install
```
```
$ npm run backend-prod
```
```
$ npm run frontend-prod
```
```
$ php artisan storage:link
```
```
$ php artisan serve
```
Now visit and login: [http://localhost:8000](http://localhost:8000) \
username: admin\
password: demo123


**N.B:**
- For sms and email processing you need to run laravel queue worker. `bin` folder has supervisor config for start queue worker with supervisor.

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/shishir1310/shoppingkori-master/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create.
Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the [MIT License](https://opensource.org/licenses/MIT). See `LICENSE`for more information.



<!-- CONTACT -->
## Contact

Email: [shishirroy1310@gmail.com](shishirroy1310@gmail.com)

LinkedIn: [Shishir Roy](https://www.linkedin.com/in/shishir-roy-3937b7120/)

Project Link: [https://github.com/shishir1310/shoppingkori-master](https://github.com/shishir1310/shoppingkori-master)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Partha Protim Das](#)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[build-shield]: https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat-square
[build-url]: #
[contributors-shield]: https://img.shields.io/badge/contributors-1-orange.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[license-shield]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square
[license-url]: https://choosealicense.com/licenses/mit
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/shishir-roy-3937b7120/
[product-screenshot]: https://raw.githubusercontent.com/othneildrew/Best-README-Template/master/screenshot.png
