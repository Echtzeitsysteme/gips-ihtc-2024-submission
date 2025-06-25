# GIPS IHTC 2024 Submission

[**GIPS**](https://github.com/Echtzeitsysteme/gips) is an open-source framework for **G**raph-Based (M)**I**LP **P**roblem **S**pecification.
This repository holds the GIPS-based IHTC (Integrated Healthcare Timetabling Competition) 2024 submission of the group "GIPS" consisting of the following members:

- [Maximilian Kratz](https://www.es.tu-darmstadt.de/en/es-real-time-systems-lab/team/maximilian-kratz) (Real-Time Systems Lab, Technical University of Darmstadt, Germany)
- [Steffen Zschaler](https://steffen-zschaler.de/) (Department of Informatics, King's College London, United Kingdom)
- [Jens Kosiol](https://www.uni-marburg.de/de/fb12/arbeitsgruppen/swt/team/jens-kosiol) (Software Engineering Group, Philipps-Universität Marburg, Germany)
- [Andy Schürr](https://www.es.tu-darmstadt.de/es/team/andy-schuerr) (Real-Time Systems Lab, Technical University of Darmstadt, Germany)


## Textual Description

As part of the submission, we prepared a textual (and visual) description of our approach.
This description can be found as a PDF here: [description.pdf](./description.pdf).


## Presentation

We held a [talk](https://www.euro-online.org/conf/euro34/treat_abstract?paperid=1842) at the [EURO 2025 conference](https://euro2025leeds.uk).
The slides of the presentation can be found here: [euro2025-slides.pdf](./euro2025-slides.pdf).


## Solutions

- Our obtained solutions can be found in this [subfolder](./solutions/) of the repository.
- The obtained scores can be found in the corresponding [CSV file](./scores.csv).


## Implementation

This repository contains all of our implementation details.
See below for more details about our implementation.

A JAR build of our solution can also be found in the repository: [gips-ihtc.jar](./gips-ihtc.jar)

### Setup

* Install [GIPS](https://github.com/Echtzeitsysteme/gips) as described in its [repository](https://github.com/Echtzeitsysteme/gips).
* Launch a runtime workspace (while using a runtime Eclipse) as stated in the eMoflon::IBeX installation steps. (Please refer to the installation steps of GIPS above.)
* Use this [PSF file](https://raw.githubusercontent.com/Echtzeitsysteme/gips-ihtc-2024-submission/main/projectSet.psf) to import all submission-related projects.
* Build all your projects with the black eMoflon hammer. Sometimes, it is required to trigger a cleaning in Eclipse (*Project -> Clean... -> Clean all projects*).
* You can use the [IhtcGipsStrategyRunner.java](./ihtcrunner/src/org/emoflon/gips/ihtc/runner/strategy/IhtcGipsStrategyRunner.java) to run our solution.


### Project Overview

| **Name** | **Description**                                                             |
| -------- | --------------------------------------------------------------------------- |
| `ihtc*`  | Projects related to the GIPS-based solution for the IHTC 2024 (competition) |


### License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for more details.
