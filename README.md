<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Image Caption Generator: An Explorative Comparison between LSTM and Transformer Implementations</h3>

  <p align="center">
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>View the report »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</div>

### Table of Contents

<ol>
<li><a href="#authors">Authors</a></li>
<li><a href="#codes-and-resources-used">Codes and Resources Used</a></li>
<li><a href="#data-ingestion-sources">Data Ingestion Sources</a></li>
<li><a href="#getting-started">Getting Started</a></li>
<li><a href="#usage">Usage</a></li>
<li><a href="#contact">Contact</a></li>
<li><a href="#acknowledgements">Acknowledgements</a></li>
</ol>

<br />

<!-- ABOUT THE PROJECT -->

# About The Project

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi in sodales neque, vel vulputate orci. Suspendisse felis justo, blandit suscipit condimentum vel, molestie efficitur dui. Nulla in sodales purus, vestibulum congue nulla. Ut in sapien id magna congue tempor. Aliquam non metus ut tellus dictum vulputate. Praesent suscipit lacinia ex, nec finibus lectus. Morbi non est metus. Maecenas accumsan dui a rhoncus finibus. Aliquam vehicula neque in erat faucibus fringilla. Curabitur tristique nisl id augue egestas pharetra. Vivamus in semper augue. Mauris scelerisque lacinia sem quis vestibulum. Nunc varius non elit ac euismod. Sed vitae urna porta erat feugiat volutpat. Maecenas efficitur pulvinar lectus vitae facilisis.

Here's why:

- Your time should be focused on creating something amazing. A project that solves a problem and helps others
- You shouldn't be doing the same tasks over and over like creating a README from scratch
- You should implement DRY principles to the rest of your life :smile:

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have contributed to expanding this template!

Use the `BLANK_README.md` to get started.

<p align="right">(<a href="#top">back to top</a>)</p>

### _Pipeline Architecture:_

  <a>
    <img src="read_me_files/archi.png" alt="Pipeline Architecture" height="400">
  </a>

### _Keywords:_

_Deep Learning, Image Caption Generation, Transformers, LSTM, Flickr8k, NLP_

## Authors:

- Loh Hong Tak Edmund
- Sim Wee Yang
- Woo Jun Hao Bryan

<p align="right">(<a href="#top">back to top</a>)</p>

## Codes and Resources Used

**Python Version:** 3.8.10

**Built with:** [Google Colab Pro](https://colab.research.google.com/)

**Notable Packages:** matplotlib, numpy, pandas, pickle, great_expectations, tqdm, skimage, torch, nltk

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

This repository contains 2 notebooks:

1. Project_Notebook_LSTM.ipynb
2. Project_Notebook_Transformer.ipynb

Each notebook executes the tasks related to LSTM and Transformers models respectively. The two models were made with separate notebooks for clearer differentiation of the two models.

You will also need to download the Flickr8k dataset, which contains 8091 images and their corresponding captions. This folder containing the images and captions should be called 'flickr_8k_dataset'. Upload this folder into a folder called 'data' on your root directory of Google Drive.

You can download the Flickr8k dataset [here](https://www.kaggle.com/datasets/adityajn105/flickr8k).

Create a folder called 'unseen' in the 'flickr_8k_dataset' folder. This will contain the inference images later.

Overall, your file directory on Google Drive should look like this:

├── drive/My Drive

│ data

│ └── flickr_8k_dataset

| ├──├── images (folder containing training and test images)

| ├──├── captions.txt

| ├──├── unseen (folder containing inference images)

### Prerequisites

We recommend running the project notebooks on Google Colab as the environment on Google Colab has been already set up for Torch related programmes. Also, training and testing the models require large compute power, which is not feasible for small local machines.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

### Training

To train the LSTM Model, simply run the relevent cells as annotated in the Notebook. The Transformer model requires no training as the transfer learning of a pre-trained transformer model was used.

### Infering New Photos

If you have not created an 'unseen' folder in the 'flickr_8k_dataset' folder, do create a new folder called 'unseen'. Upload the image that you would like to infer the caption of in this folder. After that, run the relevant cells in the notebook as annotated.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

- [Choose an Open Source License](https://choosealicense.com)
- [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
- [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
- [Malven's Grid Cheatsheet](https://grid.malven.co/)
- [Img Shields](https://shields.io)
- [GitHub Pages](https://pages.github.com)
- [Font Awesome](https://fontawesome.com)
- [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#top">back to top</a>)</p>

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
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
