# Verapamil-Model
Whole-body PBPK model of verapamil and norverapamil as CYP3A4 and P-gp perpetrator drug 

<a title="Verapamil" href="https://commons.wikimedia.org/wiki/File:Verapamil_structure.svg"><img width="512" alt="Verapamil structure" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Verapamil_structure.svg/512px-Verapamil_structure.svg.png"></a>



This repository contains:

- a PK-Sim snapshot (*.json) file of the current PBPK model
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found [here](https://github.com/Open-Systems-Pharmacology/Verapamil-Model/releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found [here](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases).**


This whole-body verapamil PBPK model comprises verapamil R- and S-enantiomers and their main metabolites R- and S-norverapamil. The processes implemented to describe the pharmacokinetics of verapamil and norverapamil include enantioselective plasma protein binding, enantioselective metabolism by CYP3A4, non-stereospecific Pgp transport, and passive glomerular filtration. 
This verapamil model includes mechanism-based inactivation of CYP3A4 and non-competitive inhibition of Pgp by the verapamil and norverapamil enantiomers and is intended to be used as perpetrator drug in CYP3A4-mediated and P-gp-mediated drug-drug interactions (DDI). 
The verapamil PBPK model has been developed using data from 45 clinical studies. Model development and application has been published by Hanke *et al.* 2020 [[1](https://github.com/Open-Systems-Pharmacology/verapamil-Model#references)]. 

## Code of conduct

Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution

We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License

The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References

[1] [Hanke N, Türk D, Selzer D, Wiebe S, Fernandez É, Stopfer P, Nock V, Lehr T. A Mechanistic, Enantioselective, Physiologically Based Pharmacokinetic Model of Verapamil and Norverapamil, Built and Evaluated for Drug-Drug Interaction Studies. Pharmaceutics. 2020 Jun 16;12(6):556. doi: 10.3390/pharmaceutics12060556. PMID: 32560124; PMCID: PMC7355632.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7355632/)
