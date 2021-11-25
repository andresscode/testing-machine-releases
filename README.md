# Testing Machine Releases
Use a *Stress Testing* approach based on *auto-generated* test cases to validate the correctness of your algorithms. Setup your favorite programming language or multiple ones to compare their results.

### For Students
Design and implement your algorithms without looking at the solutions on the Internet.

### For Professionals
Improve and benchmark your algorithms using different programming languages.

## Quick Start Guide

### Setup

1. Download the application installer from the [releases](https://github.com/andresscode/testing-machine-releases/releases) section and install the application:
- **Linux/Ubuntu** `.deb`
- **MacOSX** `.dmg`
- **Windows** `.msi`

> Please, avoid using the *.zip* files.

2. Download the `sorting-sample.zip` file which contains files for testing the application.

### Usage

1. From the *Files* tab select the required files to run the program.

> Make sure you use the `generetor.py` file as the *Generator* and any of the main files as the *Model* and *Solution*.

2. Click *Run*.

#### Configs

- **Params:** from this tab you can tweak the *Generator*; i.e., the maximum number of elements within the array.

> The point of using *Generators* is to be able to create different implementations to test different algorithms and use cases.

- **Settings:** From this tab you can adjust some global options for the program; i.e., how many test cases you would like to run.

> The *Dynamic* option is not working as expected and should be refactored or removed in future releases. 
