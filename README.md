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

[Contributors][contributors-url]
[Forks][forks-url]
[Stargazers][stars-url]
[Issues][issues-url]
[MIT License][license-url]
[LinkedIn][linkedin-url]

<!-- PROJECT LOGO -->

<br />
<div align="center">
  <a href="https://github.com/kennethtegrado/zernlp">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">zernlp</h3>

<p align="center">
    A Natural Language Processing (NLP) Library for Filipino
    <br />
    <a href="https://github.com/kennethtegrado/zernlp"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/kennethtegrado/zernlp/issues">Report Bug</a>
    ·
    <a href="https://github.com/kennethtegrado/zernlp/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

**zernlp** is a user-friendly Python library designed to provide a comprehensive set of tools and algorithms for Natural Language Processing (NLP) tasks. Whether you are a researcher, data scientist, or developer working on language-related projects, **zernlp** offers a wide range of functionalities to process and analyze human language data efficiently for texts written in Filipino.

<p align="right">(<a href="#top">back to top</a>)</p>

## Installation

1. To start using **zernlp**, you can easily install it via pip:
   ```sh
   pip install zernlp
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

```python
from zernlp.tokenizers import sentence_tokenizer, tokenizer

text = "Ito'y isang halimbawa ng paggamit sa zernlp para sa pag-tokenize ng isang pangungusap."

# ipasa ang text
sentences = sentence_tokenizer(text)
tokens = tokenizer(text)

for token in tokens:
  print(tokens)

for sentence in sentences:
  print(sentences)

```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [ ]**Tokenization:** Efficiently split text into individual words or tokens, catering the Filipino language and tokenization rules.
- [ ]**Lemmatization and Stemming:** Reduce words to their base or root form for better information retrieval and analysis.
- [ ]**Part-of-Speech (POS) Tagging:** Assign grammatical tags to words, enabling linguistic analysis and information extraction.
- [ ]**Named Entity Recognition (NER):** Identify and categorize entities like persons, locations, and organizations in the text.
- [ ]**Dependency Parsing:** Analyze the grammatical structure of sentences and identify the relationships between words.

See the [open issues](https://github.com/kennethtegrado/zernlp/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

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

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Kenneth Tegrado - kategrado@up.edu.ph

Project Link: [https://github.com/kennethtegrado/zernlp](https://github.com/kennethtegrado/zernlp)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

<!-- * []()
* []()
* []() -->

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/kennethtegrado/zernlp.svg?style=for-the-badge
[contributors-url]: https://github.com/kennethtegrado/zernlp/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/kennethtegrado/zernlp.svg?style=for-the-badge
[forks-url]: https://github.com/kennethtegrado/zernlp/network/members
[stars-shield]: https://img.shields.io/github/stars/kennethtegrado/zernlp.svg?style=for-the-badge
[stars-url]: https://github.com/kennethtegrado/zernlp/stargazers
[issues-shield]: https://img.shields.io/github/issues/kennethtegrado/zernlp.svg?style=for-the-badge
[issues-url]: https://github.com/kennethtegrado/zernlp/issues
[license-shield]: https://img.shields.io/github/license/kennethtegrado/zernlp.svg?style=for-the-badge
[license-url]: https://github.com/kennethtegrado/zernlp/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/kennethtegrado
[product-screenshot]: images/screenshot.png
