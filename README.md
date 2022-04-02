
# Auto Poster Generator

## Introduction

A prototype to generate posters, certificates, banners, images with custom texts using a base template. The configuration is designed to be very easy and user friendly. Another major advantage of this software is it's designed to run on very low resources, while offering flexibility.

This program can be very helpful for both education and other organization including commercial ones since the need to generate posters/certificates etc. It is one that arises in many such organizations.

Auto Poster Generator is coded using both Python and C#. The image manipulations process, which analyzes the and manipulates the image in order to  place the text is written in Python. A user friendly GUI was coded in C#, making this software both easy and modular.

The Python scripts making up the backend can be accessed and modified easily to suit a person's/organization's preferences.

## Programming Languages & Frameworks

* Python
  * Pillow
  * Textwrap
  * OS
* C#

## Configuration & Setup

* Installing Pillow

  ```
  pip install pillow
  ```

* Installing textwrap

  ```
  pip install textwrap3
  ```


## System Explained

This system generate images writing text on a base template, first we need to give the Y1, Y2 (Starting point) | X1, X2 (Ending point) coordinates.

We can write many text elements on a base template, but, the number of texts elements in all batches should be same.

### Input

**Note** As an input, we give this base template, here we want to write the tutorial number on the first box, and the tutorial heading on the second big box, these headings and tutorial numbers' data are given in the .txt format.

![Image](github-readme-contents/input.png)

### Output

**Note** As outputs, the system generates images with tutorial numbers and tutorial headings from the given .txt files, but if we are writing more than 1 text elements into a base template, the number of texts must be same, for an example, if we want to generate 60 posters, we need to give 60 text elements for tutorial numbers, and 60 text elements for tutorial headings. We can call one processing as a batch. We can write many text elements as we want, but the number of texts in element must match with others.

### Text files inputs

![Image](github-readme-contents/output.png)

## Execution & Running

### Run Method 1

```
Execute Auto_Poster_Generator.exe found in "auto-poster-generator/0-auto-poster-generator-design-vs/Auto_Poster_Generator/Auto_Poster_Generator/bin/Debug/"
```

### Run Method 2

```
Open the project in Visual Studio and click debugging to run the prohect.
```


Any Questions? | Conduct Me
---

* [Linkedin Profile](https://www.linkedin.com/in/gunarakulan-gunaretnam-161119156/)
* [Facebook Profile](https://www.facebook.com/gunarakulan)
* [Twitter Profile](https://twitter.com/gunarakulang)
* [Instagram Profile](https://www.instagram.com/gunarakulan_gunaretnam/)
* [Youtube Channel](https://www.youtube.com/channel/UCMWkED5sabgVZSCKjZuRJXA/videos)
