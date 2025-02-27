**[summary](#summary) | [prerequisites](#prerequisites) | [setup](#setup) | [resources](#resources) | [license](#license)**

[![License](https://img.shields.io/github/license/simpeg-research/earthscope-mt-course.svg)](https://github.com/simpeg-research/earthscope-mt-course/blob/main/LICENSE)
[![SimPEG](https://img.shields.io/badge/powered%20by-SimPEG-blue.svg)](http://simpeg.xyz)
![example workflow](https://github.com/simpeg-research/earthscope-mt-course/actions/workflows/python-package-conda.yml/badge.svg)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=Follow%20%40sgkang09)](https://twitter.com/sgkang09)

# Magnetotelluric (MT) Instrumentation and Data Processing Short Course


|         | Info |
|--------:|:-----|
| When    | October 18-20th 2022|
|        | October 28-Nov 1 2024|
| conda environment  | `em` |

**Team**
- [Seogi Kang](https://github.com/sgkang) (Instructor)
- [Jared Peacock](https://github.com/kujaku11) (Instructor)
- [Karl Kappler](https://github.com/kkappler) (Instructor)
- [Lindsey Heagy](http://github.com/lheagy) 
- [Mike Mitchell]()(Instructor)
- [Paul Bedrosian]()
- and the [SimPEG contributors](https://github.com/simpeg/simpeg/graphs/contributors)



## Summary

This repository contains the notebooks and tutorial resources for the Magnetotelluric (MT) Instrumentation and Data Processing Short Course - through Day 2-Day 4: 

- Day 2: MT Data, Data Formats, Software, & Data Processing
- Day 3: MT Dataset Explorations
- Day 4: MT inversions and Earth Models. 

This set of tutorials focus on providing hands-on examples of downloading, processing, visualzing, and inverting MT data. 

## Prerequisites

**Software**

* Some knowledge of Python is assumed.
* All coding will be done in Jupyter notebooks. I'll explain how they work
  briefly but it will help if you've used them before.
* We will use [numpy](https://numpy.org/), [matplotlib](https://matplotlib.org/), and
  [ipywidgets](https://ipywidgets.readthedocs.io/)
  You don't need to be an expert in these tools but some familiarity will help.

## Setup

### Anaconda

If you do not already have Anaconda you can download it [here](https://www.anaconda.com/download/success). 

*Be sure to download the correct package for your operating system.*
 

### Step 1: Download the MT tutorial notebooks

To clone this repository, open up an Anaconda terminal and navigate to where you want this repository stored on your computer.

Then run
```
git clone https://github.com/simpeg-research/earthscope-mt-course.git
```
to clone the repository, and `cd` into the `earthscope-mt-course-2024` directory
```
cd earthscope-mt-course
```

### Step 2: Create `em` conda environment

#### Create environment



From inside of the `earthscope-mt-course` repository, create the `em` conda environment
```
conda env create -f environment.yml
```

and activate the environment

```
conda activate em
```

### Step 3: Launching the notebooks

Once you have activated the conda environment, you can launch the notebooks

```
jupyter lab
```

Jupyter will then launch in your web-browser.

## Resources

**Resources on MT processing and inversions**
- [mt-metadata](https://github.com/kujaku11/mt_metadata)
- [MTH5](https://github.com/kujaku11/mth5)
- [MTpy-v2](https://github.com/MTgeophysics/mtpy-v2)
- [aurora](https://github.com/simpeg/aurora)
- [SimPEG](https://www.simepg.xyz)

**Resources on SimPEG**
- [Docs](http://docs.simpeg.xyz/)
- [Discourse](http://simpeg.discourse.group/)
- [Slack](http://slack.simpeg.xyz/)


## License

All code and text in this repository is free software: you can redistribute it and/or
modify it under the terms of the MIT License.
A copy of this license is provided in [LICENSE](LICENSE).

