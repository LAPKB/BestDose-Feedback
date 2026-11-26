# BestDose <img align="right" width="96" height="96" alt="BestDose logo" src="assets/logo.svg">

BestDose is software for model-informed precision dosing (MIPD). It helps healthcare professionals choose a dose for an individual patient from that patient's characteristics and measured drug concentrations.

BestDose works with the [Pmetrics](https://github.com/LAPKB/Pmetrics) package for R and uses its non-parametric population models. It is the only non-parametric, Bayesian adaptive control software for clinical use. See [Goutelle et al., J Clin Pharmacol, 2022](https://pubmed.ncbi.nlm.nih.gov/33103785) for background on the method.

> Note : **This repository is where you ask questions and report problems.**  
> The BestDose source code is not published here.

## What BestDose does

- _A priori_ dosing from a population model, and _a posteriori_ (Bayesian) dosing once concentrations are measured.
- Pharmacokinetic and pharmacodynamic models.
- Customizable PDF reports.
- A model library you can browse, edit and extend inside the app.
- Import of models from the published literature with the companion app `BestDose autopilot` downloadable on the LAPKB website (see below).
- EUCAST bacteria and MIC data for antibiotic targets (partially supported).
- A full user manual inside the app.

## Get BestDose

BestDose is a desktop application for Windows and macOS (Apple silicon). Download it from [lapkb.org/downloads/apps](https://lapkb.org/downloads/apps/).

BestDose needs an LAPKB licence. On first launch, sign in with your LAPKB account, or use **Activate offline** if the computer has no internet access.

BestDose shows when a newer version is available: open the account menu (your initials, top right). It shows your version, and an **Update to …** button when a newer one is out.

## Ask a question or report a problem

Open an [issue](https://github.com/LAPKB/BestDose-Feedback/issues). In BestDose, **Report issues** in the account menu opens this page.

> [!CAUTION]
> **Never post patient data.** Issues are public. Remove names, dates of birth, record numbers and any other identifying information from text, files and screenshots before you post.

To help us fix a problem quickly, include:

- **Your BestDose version**, shown in the account menu.
- **Your operating system** (Windows or macOS).
- **What you did, what you expected, and what happened.** A screenshot of any error message helps.
- **For sign-in or licence problems on Windows**, the log file `%LOCALAPPDATA%\BestDose\logs\bestdose.log` and `%LOCALAPPDATA%\org.lapkb.desktop\auth-dialog.log`. It contains no patient data.

## Teams

- Dr Romain Garreau, PharmD, PhD
- Pr Michael Neely, MD, MSc, FCP
- Dr Julián Otálvaro, PhD
- Dr Markus Hovd, MSc. Pharm, Ph.D
- Pr Sylvain Goutelle, Pharm.D, Ph.D
- Pr Laurent Bourguignon, Pharm.D, Ph.D

## Licence and copyright

**BestDose**® is a registered trademark of LAPKB. The open-source license for this repository does not grant rights to use the trademark.  
All rights are held by the [LAPKB (Laboratory of Applied Pharmacokinetics and Bioinformatics, University of Southern California, Los Angeles, CA, USA)](https://lapkb.org).
