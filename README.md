# TeethSegmentation
Identify teeth in X-ray images using instance segmentation and labelling.

<div id="top"></div>

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
<!-- [![LinkedIn][linkedin-shield]][linkedin-url] -->



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/RobertSmithers/TeethSegmentation">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Teeth Segmentation</h3>

  <p align="center">
    With machine learning, we aim to identify teeth via segmentation and labelling.
    <br />
    <br />
    <a href="https://github.com/RobertSmithers/TeethSegmentation/issues">Report Bug</a>
    ·
    <a href="https://github.com/RobertSmithers/TeethSegmentation/issues">Request Feature</a>
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Teeth Art][teeth-art1]](https://github.com/RobertSmithers/TeethSegmentation)
[![Teeth Art][teeth-art2]](https://github.com/RobertSmithers/TeethSegmentation)

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Python](https://www.python.org/)
* [PyTorch](https://pytorch.org/)
* [PyTorch3D](https://pytorch3d.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Demo
```diff
- To try our program or test your own x-ray image, open 'Test.ipynb' and follow instruction.
```

<!-- ### Prerequisites

This is an example of how to list things you need to use the software and how to install them. It is recommended to install these within a virtual environment within the repository.

* PyTorch
  ```sh
  pip install torch
  ```

* PyTorch3D
  ```sh
  pip install "git+https://github.com/facebookresearch/pytorch3d.git@stable"
  ``` -->

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/RobertSmithers/TeethSegmentation.git
   ```
2. (Optional) Create a virtual environment
3. Install all required prerequisites

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Teeth Labelling is not a brand new field of study, though the amount of available data is highly limited. Teeth data is rarely open source, a product of scarcity in related machine learning research as well as protection of patients' privacy.

With this teeth segmentation utility, artifical intelligence can autonomously label teeth scans and identify malformed, missing, or otherwise important concerns relating to the count and placement of teeth. The ability to label teeth in fractions of a second serves as a vital aide to dentistry personnel.

I hope this repository will help advance research within the academic community!

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Ground Truth Masking
- [x] Data Augmentation
- [x] Model Optimization
    - [x] Autonomous model saving

See the [open issues](https://github.com/RobertSmithers/3DTeethSegmentation/issues) for a full list of proposed features (and known issues).

## Work Contribution

- README.md: Robert, Yuting
- data/: Yuting, Daniella
- results/: Robert
- connected_component_images/: Daniella
- models/: Robert
- 
- '3Ddata_attempt.ipynb': Robert
- 'pytorch3d_render.ipynb': Yuting
- 'Loader.py': Yuting, Robert
- 'contour_generation.ipynb': Daniella
- 'Loader.ipynb': Yuting
- 'Res-Unet.py': Yuting
- 'data_preparation.ipnyb': Daniella
- 'model.py': Robert
- 'pre_process.py': Daniella
- 'train.ipynb': Robert
- 'connected_component.py': Yuting
- 'connected_component_segmentation.ipynb': Yuting, Daniella
- 'Test.ipynb': Yuting 
- 
- 'X-Ray TeethSegmentation.pptx'(the powerpoint): Yuting, Daniella, Robert
- Final Report: Daniella, Yuting, Robert


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## To Contribute

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

Robert Smithers - [Website](https://robertsmithers.github.io/) - rjsmithers3@gmail.com

Yuting Ji - jiyz@bc.edu

Daniella Zunic - zunicd@bc.edu

Project Link: [https://github.com/RobertSmithers/TeethSegmentation](https://github.com/RobertSmithers/TeethSegmentation)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Image Analysis Course](https://bc-cv.github.io/csci3397/s22/)
* [TSegNet](https://www.sciencedirect.com/science/article/pii/S1361841520303133)
* [3D Teeth Segmentation using Deep CNNs](https://www.youyizheng.net/docs/tooth_seg.pdf)
* [MeshSegNet](https://github.com/Tai-Hsien/MeshSegNet)

<p align="right">(<a href="#top">back to top</a>)</p>

[![Teeth Art][product-screenshot]](https://github.com/RobertSmithers/TeethSegmentation)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/RobertSmithers/3DTeethSegmentation.svg?style=for-the-badge
[contributors-url]: https://github.com/RobertSmithers/3DTeethSegmentation/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/RobertSmithers/3DTeethSegmentation.svg?style=for-the-badge
[forks-url]: https://github.com/RobertSmithers/3DTeethSegmentation/network/members
[stars-shield]: https://img.shields.io/github/stars/RobertSmithers/3DTeethSegmentation.svg?style=for-the-badge
[stars-url]: https://github.com/RobertSmithers/3DTeethSegmentation/stargazers
[issues-shield]: https://img.shields.io/github/issues/RobertSmithers/3DTeethSegmentation.svg?style=for-the-badge
[issues-url]: https://github.com/RobertSmithers/3DTeethSegmentation/issues
[license-shield]: https://img.shields.io/github/license/RobertSmithers/3DTeethSegmentation.svg?style=for-the-badge
[license-url]: https://github.com/RobertSmithers/3DTeethSegmentation/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
<!-- [linkedin-url]: https://linkedin.com/in/linkedin_username -->
[product-screenshot]: images/logo.jpg
<!-- [teeth-art]: images/logo.png -->
[teeth-art1]: images/input.png
[teeth-art2]: images/predicted.png
