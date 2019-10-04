<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

# DOS Impact on API POC

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- ABOUT THE PROJECT -->
## Proof-of-Concept

This Python 3 script creates;
* threads and makes GET API calls to any endpoint you specify.
* threads and makes POST API calls to any endpoint you specify.

Use this only on your own APIs to stress test and see how many concurrent requests your server can support, as well as testing the rate limit of your APIs. **STRICTLY FOR EDUCATIONAL PURPOSE ONLY**.

<!-- USAGE EXAMPLES -->
## Usage

- Change the number of threads and how many requests each thread makes to adjust the number of total requests to make.
- Add the API URL endpoint to call (```make_requests.py```).

To run: ```python3 stress_test.py``` 

### Prerequisites

- Python3 requests



## Article Highlight

The most common type of Layer 7 attacks is so-called HTTP floods, which send seemingly legitimate requests in too large numbers. They are particularly effective when they target resource-hungry elements of the web application, such as large file downloads or form submissions.

![HTTP Flood Attack](https://security.syafiqhadzir.dev/assets/images/http-flood-attack.webp)

When flooding, the attacker wants to submerge the target server under many requests, to saturate its computing resources. Flooding works best when the server allocates a lot of resources in response to a single request.

Since POST requests include parameters, they usually trigger relatively complex processing on the server (e.g. database accesses), which are more expensive for the server than serving a much simpler GET. Thus, POST-based flooding tends to be more effective than GET-based flooding (it takes fewer requests to drown the server if the requests are POST). On the other hand, GET requests being much more common, it is often way easier for the attacker to enlist (involuntary) help in the flooding effort when GET-flooding.



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Syafiqhadzir - [@syafiqhadzir_](https://twitter.com/syafiqhadzir_) - inquiry@syafiqhadzir.dev

Project Link: [https://github.com/ctsecurity/API-DOS_POC](https://github.com/ctsecurity/API-DOS_POC)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ctsecurity/API-DOS_POC.svg?style=flat-square
[contributors-url]: https://github.com/ctsecurity/API-DOS_POC/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ctsecurity/API-DOS_POC.svg?style=flat-square
[forks-url]: https://github.com/ctsecurity/API-DOS_POC/network/members
[stars-shield]: https://img.shields.io/github/stars/ctsecurity/API-DOS_POC.svg?style=flat-square
[stars-url]: https://github.com/ctsecurity/API-DOS_POC/stargazers
[issues-shield]: https://img.shields.io/github/issues/ctsecurity/API-DOS_POC.svg?style=flat-square
[issues-url]: https://github.com/ctsecurity/API-DOS_POC/issues
[license-shield]: https://img.shields.io/github/license/ctsecurity/API-DOS_POC.svg?style=flat-square
[license-url]: https://github.com/ctsecurity/API-DOS_POC/blob/master/LICENSE.txt
