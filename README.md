<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/AKapaldo/GarageHelper">
    <img src="images/GarageHelper.png" alt="Logo" height="256px" width="256px">
  </a>

<h3 align="center">Garage Helper</h3>

  <p align="center">
    Garage Helper is an Alexa skill designed to help remind the user of the wrench sizes, oil weight, and quantity for performing oil changes on your vehicles.
    <br />
    <a href="https://github.com/AKapaldo/GarageHelper"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/AKapaldo/GarageHelper">View Demo</a>
    ·
    <a href="https://github.com/AKapaldo/GarageHelper/issues">Report Bug</a>
    ·
    <a href="https://github.com/AKapaldo/GarageHelper/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#version-history">Version History</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Garage Helper is an Alexa skill that can be run in AWS Lambda to accept requests via your personal Amazon account. To run the skill you will need an Amazon Alexa Developer account.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Python](https://python.org/)
* [Amazon Alexa Developer](https://developer.amazon.com/en-US/alexa)


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

You will need to create an Amazon Alexa Developer account.

### Prerequisites

You will need to create aan Amazon Alexa Developer account:
* You will also need to create an <a href="https://developer.amazon.com/en-US/alexa">Amazon Alexa Developer account</a> and put the included files under Lambda in the "Code" section of your skill.

  

### Installation


1. Clone the repo
   ```sh
   git clone https://github.com/AKapaldo/GarageHelper.git
   ```
2. In your <a href="https://developer.amazon.com/en-US/alexa">Amazon Alexa Developer account</a>, put the files you cloned above under Lambda in the "Code" section of your skill.
    * <img src="/images/lambdagarage.png">
4. You will need to update the oil.py function with the information for your vehicles.
5. In the "Build" section, you will need to create phrases to say to use the skill. e.g. how much oil do I need for {Vehicle}<br>You will need Intents for the following.
    * Oil
    * Wrench
    * Filter
    * Change

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Once you have everything in place, you can ask your Alexa device to use the skill based on what you called in the developer console and how you configured the intents. For example, in mine we can use:
```
Alexa, ask Garage Helper what I need to perform an oil change on a {Vehicle}.
```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- VERSION -->
## Version History

- v1.0: Created Garage Helper.
    - v1.1: Added a few more vehicles.
    - v1.2: Seperated out different parts allowing for intents to be created to get just the oil needed or wrench needed instead of the full information each time.

See the [open issues](https://github.com/AKapaldo/GarageHelper/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING --->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU General Public License. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Andrew Kapaldo - [@KapaldoA](https://twitter.com/kapaldoa)

Project Link: [https://github.com/AKapaldo/GarageHelper](https://github.com/AKapaldo/GarageHelper)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p>
---->


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/AKapaldo/GarageHelper.svg?style=for-the-badge
[contributors-url]: https://github.com/AKapaldo/GarageHelper/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/AKapaldo/GarageHelper.svg?style=for-the-badge
[forks-url]: https://github.com/AKapaldo/GarageHelper/network/members
[stars-shield]: https://img.shields.io/github/stars/AKapaldo/GarageHelper.svg?style=for-the-badge
[stars-url]: https://github.com/AKapaldo/GarageHelper/stargazers
[issues-shield]: https://img.shields.io/github/issues/AKapaldo/GarageHelper.svg?style=for-the-badge
[issues-url]: https://github.com/AKapaldo/GarageHelper/issues
[license-shield]: https://img.shields.io/github/license/AKapaldo/GarageHelper.svg?style=for-the-badge
[license-url]: https://github.com/AKapaldo/GarageHelper/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/andrew-kapaldo
[product-screenshot]: images/GarageHelper.png
