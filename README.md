# GIPS IHTC 2024 Submission

[**GIPS**](https://github.com/Echtzeitsysteme/gips) is an open-source framework for **G**raph-Based (M)**I**LP **P**roblem **S**pecification.
This repository holds the GIPS-based IHTC (Integrated Healthcare Timetabling Competition) 2024 submission.


## Setup

* Install [GIPS](https://github.com/Echtzeitsysteme/gips) as described in its [repository](https://github.com/Echtzeitsysteme/gips).
* Launch a runtime workspace (while using a runtime Eclipse) as stated in the eMoflon::IBeX installation steps. (Please refer to the installation steps of GIPS above.)
* Use this [PSF file](https://raw.githubusercontent.com/Echtzeitsysteme/gips-ihtc-2024-submission/main/projectSet.psf) to import all submission-related projects.
* Build all your projects with the black eMoflon hammer. Sometimes, it is required to trigger a cleaning in Eclipse (*Project -> Clean... -> Clean all projects*).
* You can use the [IhtcGipsStrategyRunner.java](./ihtcrunner/src/org/emoflon/gips/ihtc/runner/strategy/IhtcGipsStrategyRunner.java) to run our solution.


## Example Overview

| **Name**                                           | **Description**                                                                         |
| -------------------------------------------------- | --------------------------------------------------------------------------------------- |
| `ihtc*`                                            | Projects related to the GIPS-based solution for the IHTC 2024 (competition)             |


## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for more details.
