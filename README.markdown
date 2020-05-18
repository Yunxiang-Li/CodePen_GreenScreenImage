# Green Screen Image

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

A Pen created on CodePen.io. Original URL: [https://codepen.io/Kitzukikokone/pen/rNOGrzp](https://codepen.io/Kitzukikokone/pen/rNOGrzp).

## Table of Contents

- [Background](#Background)
- [Exhibition](#Exhibition)
- [Install](#install)
- [Usage](#usage)
- [Structure](#Structure)
- [Maintainers](#Maintainers)
- [License](#license)

## Background
This is a very simple Green Screen Image processing program made on CodePen.io according to the [Duke University](https://duke.edu/)'s coursera course [Programming Foundations with JavaScript, HTML and CSS](https://www-cloudfront-alias.coursera.org/learn/duke-programming-web/home/welcome).

## Exhibition

All example images are from [here](https://www.dukelearntoprogram.com/course1/greenscreencode/).

![Start Page](https://github.com/Yunxiang-Li/CodePen_GreenScreenImage/blob/master/Pictures/exhibition1.PNG)

![Exhibition 1](https://github.com/Yunxiang-Li/CodePen_GreenScreenImage/blob/master/Pictures/exhibition2.PNG)

![Exhibition 2](https://github.com/Yunxiang-Li/CodePen_GreenScreenImage/blob/master/Pictures/exhibition3.PNG)

![Exhibition 3](https://github.com/Yunxiang-Li/CodePen_GreenScreenImage/blob/master/Pictures/exhibition4.PNG)

## Install

I only use CodePen.io[https://codepen.io/] itself in this tiny project.<br>

## Usage

1.Download this repo,open(or zip and open) the **Unity_Simple-Solar-System-Simulation** folder.

2.Open the **Assets** folder, then open the **Scenes** folder.

3.Finally double click **Solar System.unity** to open this project in unity.

4.You may need a little bit more time to wait for downloading some additional resource.

**You can use mouse to left click on each planet, then the view will be changed as the clicked planet is always in the center of the view. You can change view both by left clicking each planet directly or just clicking each on the map in the left bottom corner.**

## Structure

The whole project in Unity contains two main folders, **Assets** folder and **Package** folder.<br>
Under **Assets** folder, there are altogether 6 subfolders:
```
1.Materials folder: contains all materials need for each planet and the universe.

2.Plugins folder: Plugins/Editor/JetBrains, creates for JetBrains Rider IDE.

3.Scences folder: contains the main scence(Solar System) of the project.

4.Scripts folder: contains all three C# scripts. RotateAround script for letting each planet
to rotate(both rotation and revolution),FollowAtTarget script for setting camera to follow a 
target object through aiming at its positive z axis and ChangeLookAtTarget script for setting
camera to look at another target object when we click the left mouse button upon that target object.

5.Sounds folder: contains all sounds files of each planet.

6.Textures folder: contains all textures for each planet and the universe.
```

## Maintainers

[@Yunxiang-Li](https://github.com/Yunxiang-Li).

## License

[MIT license](https://github.com/Yunxiang-Li/CS61B/blob/master/LICENSE)
