# Verapamil-Model
Whole-body PBPK model of verapamil as CYP3A4 perpetrator drug 

<a title="Verapamil" href="https://commons.wikimedia.org/wiki/File:Verapamil_structure.svg"><img width="512" alt="Verapamil structure" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Verapamil_structure.svg/512px-Verapamil_structure.svg.png"></a>



This repository contains:

- a PK-Sim snapshot (*.json) file of the current PBPK model
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found [here](https://github.com/Open-Systems-Pharmacology/Verapamil-Model/releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found [here](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases).**

This verapamil model is intended to be used as perpetrator drug in CYP3A4-mediated drug-drug interactions (DDI). 

This  whole-body verapamil PBPK model comprises metabolization by CYP3A4 and CYP2C8. The dose- and time-dependent nonlinear behavior of verapamil is described through implementation of the CYP3A4 mechanism-based (auto-)inactivation by verapamil. The verapamil PBPK model has been developed using in particular published pharmacokinetic clinical data by Barbarash *et al.* 2010 [[1](https://github.com/Open-Systems-Pharmacology/verapamil-Model#references)], Johnston *et al.* 1999 [[2](https://github.com/Open-Systems-Pharmacology/verapamil-Model#references)] and McAllister *et al.* 2013 [[3](https://github.com/Open-Systems-Pharmacology/verapamil-Model#references)]. 

## Code of conduct

Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution

We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License

The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References

[1] [Barbarash 1988 Barbarash RA, Bauman JL, Fischer JH, Kondos GT, Batenhorst RL. Near-total reduction in verapamil bioavailability by rifampin. Electrocardiographic correlates. Chest. 1988 Nov;94(5):954-9. PubMed PMID: 3180898.](https://www.ncbi.nlm.nih.gov/pubmed/3180898)

[2] [Johnston 1981 Johnston A, Burgess CD, Hamer J. Systemic availability of oral verapamil and effect on PR interval in man. Br J Clin Pharmacol. 1981 Sep;12(3):397-400. PubMed PMID: 7295469; PubMed Central PMCID: PMC1401793.](https://www.ncbi.nlm.nih.gov/pubmed/7295469)

[3] [McAllister 1982 McAllister RG Jr, Kirsten EB. The pharmacology of verapamil. IV. Kinetic and dynamic effects after single intravenous and oral doses. Clin Pharmacol Ther. 1982 Apr;31(4):418-26. PubMed PMID: 7060323.](https://www.ncbi.nlm.nih.gov/pubmed/7060323)