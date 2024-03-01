# Technical Assessment

This project demonstrates the use of Selenium IDE and Selenium Side Runner for automating the download of the latest PDF from the arXiv website, focusing on the computer science section. The task involves identifying a source of regularly updated PDFs, automating the download of the newest PDF, and verifying the automation script's effectiveness through the command line.

## Overview

1. **Objective**: Automate the download of the latest PDF posted in the computer science section of the arXiv website.
2. **Tools Used**: Selenium IDE for recording the test automation and Selenium Side Runner for executing the .side file via command line.
3. **Website Chosen**: [arXiv](https://arxiv.org/) for its public accessibility and regular updates of research papers in PDF format.

## Requirements

- Firefox or Chrome Browser.
- Selenium WebDriver for the chosen browser.
- Node.js and npm for installing Selenium Side Runner.

## Setup Instructions

### Selenium IDE Installation

1. Install Selenium IDE from [Selenium IDE Download Page](https://www.selenium.dev/selenium-ide/).
2. Add the extension to your browser (Firefox or Chrome).

### Selenium Side Runner Installation

```bash
npm install -g selenium-side-runner
