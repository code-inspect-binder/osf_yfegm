# Executable Environment for OSF Project [yfegm](https://osf.io/yfegm/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** Infants' Object Processing in the Context of Third-Party Social Interactions

**Project Description:**
> In this project we used a screen-based object-processing paradigm to investigate whether 9-month-old infants show superior processing of content presented within the context of an observed social interaction. Infants were presented with videos showing an object together with two adults. Based on a within-subjects 2x2 design, we manipulated the context of the scenarios with regard to the degree of third-party ostensive context between the two actors (ostensive or non-ostensive) and their look at the object (yes or no). By manipulating both variables we aimed to disentangle two factors that may have an impact on infants' object processing. To assess infants’ encoding performance we measured their looking times when the familiarized object subsequently appeared next to a novel object, assuming that an enhanced novelty preference would reversely indicate greater encoding of the familiarized object. Infants showed an increased novelty preference, but only after they had observed a joint attentional setting during which two adults attended to the familiarized object in an ostensive context (i.e., following mutual eye contact).

Note: In the published study (https://doi.org/10.1037/dev0001189), we refer to this project as “Experiment 1”. This OSF project is directly linked to the OSF project " The Role of Ostensive Context and Others' Gaze on Infants' Object Processing" (https://osf.io/dp5cg/). The supplemental information document (uploaded files section) contains information relevant for both studies, referring to the two studies as "Experiment 1" and "Experiment 2". 



**Original OSF Page:** [https://osf.io/yfegm/](https://osf.io/yfegm/)

---

**Important Note:** The contents of the `yfegm_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_yfegm/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_yfegm/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `yfegm_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

**Pull the Docker Image**

```bash
docker pull meet261/repo2docker-yfegm:latest
```

**Launch RStudio Server**

```bash
docker run -e PASSWORD=yourpassword -p 8787:8787 meet261/repo2docker-yfegm
```
Replace `yourpassword` with a secure password of your choice. You will use this to log in to the RStudio web interface.

**Once the container is running, visit `http://localhost:8787` in your browser.**
Use username: `rstudio` and the password you set with `-e PASSWORD=...`.
