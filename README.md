![PyPI - Python Version][python-version]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Get data</h3>

  <p align="center">
    Datasets which are usefully for sentimental analysis - NLP
    <br />
    <a href="https://github.com/nlp-project-sentiment-analysis/Get-data/tree/develop"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/nlp-project-sentiment-analysis/Get-data/blob/develop/Get-data.ipynb">View Demo</a>
    ·
    <a href="https://github.com/nlp-project-sentiment-analysis/Get-data/issues">Report Bug</a>
    ·
    <a href="https://github.com/nlp-project-sentiment-analysis/Get-data/pulls">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Repository

![Product Name Screen Shot][product-screenshot]

In this repo, we are collecting datasets which are usefully for sentimental analysis - NLP. Kaggle is an online community platform for data scientists and machine learning enthusiasts. We also used web-scrapping on wikipedia website.

### Built With

This are the frameworks & tools used in this repo

- [Python](https://www.python.org/)
- [Jupiter Notebook](https://jupyter.org/)
- [VsCode](https://code.visualstudio.com/)

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

List things you need to use the software and how to install them.

- Python

  ```powershell
  python --version
  # Python 3.8.0
  ```

- Jupiter Notebook

  ```powershell
  jupyter --version
  # Selected Jupyter core packages...
  # IPython          : 8.4.0
  # ipykernel        : 6.15.2
  # ipywidgets       : not installed
  # jupyter_client   : 7.3.5
  # jupyter_core     : 4.11.1
  # jupyter_server   : not installed
  # jupyterlab       : not installed
  # nbclient         : not installed
  # nbconvert        : not installed
  # nbformat         : not installed
  # notebook         : not installed
  # qtconsole        : not installed
  # traitlets        : 5.3.0
  ```

- Kaggle account

  `opendatasets` uses the [Kaggle Official API](https://github.com/Kaggle/kaggle-api) for donwloading dataset from Kaggle. Follow these steps to find your API credentials:

  1. Sign in to [https://kaggle.com/](https://kaggle.com), then click on your profile picture on the top right and select "My Account" from the menu.

  2. Scroll down to the "API" section and click "Create New API Token". This will download a file `kaggle.json` with the following contents:

     ```json
     { "username": "YOUR_KAGGLE_USERNAME", "key": "YOUR_KAGGLE_KEY" }
     ```

  3. When you run `opendatsets.download`, you will be asked to enter your username & Kaggle API, which you can get from the file downloaded in step 2.

  Note that you need to download the `kaggle.json` file only once. You can also place the `kaggle.json` file in the same directory as the Jupyter notebook, and the credentials will be read automatically.

### Installation

1. Get a free API Key at [Kaggle](https://www.kaggle.com/)
2. Clone the repo
   ```powershell
   git clone -b develop https://github.com/nlp-project-sentiment-analysis/Get-data.git
   ```
3. Install python packages
   ```powershell
   python -m pip install -r requirements.txt
   ```

<!-- USAGE EXAMPLES -->

## Usage

In this repo, we are collecting datasets which are usefully for sentimental analysis - NLP. List of datasets are as follow:

- `abbreviations.csv` use to convert short-words into full and meaning full word
- `apostrophe.csv` use to convert apostrophe words into full word
- `emoji.csv` use to convert unicode emoji into english words
- `emoticons.csv` use to convert special character emoji into english words
- `neg_english_text.csv` use for NLP which contains all negative statements
- `pos_english_text.csv` use for NLP which contains all positive statements

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/nlp-project-sentiment-analysis/Get-data/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin develop:feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- Contributors -->

## Contributors

- Pranav - [PranavPremakumaran](https://github.com/PranavPremakumaran)
- Komal - [komal0608](https://github.com/komal0608)
- Karthik - [KarthikUdyawar](https://github.com/KarthikUdyawar)

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- [training1600000processednoemoticoncsv](https://www.kaggle.com/datasets/ferno2/training1600000processednoemoticoncsv)
- [List of English contractions](https://www.kaggle.com/datasets/ishivinal/contractions)
- [Chat / Internet Slang | Abbreviations | Acronyms](https://www.kaggle.com/datasets/gowrishankarp/chat-slang-abbreviations-acronyms)
- [Emoji sentiment data](https://www.kaggle.com/datasets/thomasseleck/emoji-sentiment-data)
- [List of emoticons](https://en.wikipedia.org/wiki/List_of_emoticons)
- [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/nlp-project-sentiment-analysis/Get-data/blob/feature/download-datasets/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/bg.png
[python-version]: https://img.shields.io/pypi/pyversions/pandas?style=for-the-badge
