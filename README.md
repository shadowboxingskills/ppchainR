<p align="center">
    <a href="https://ppchain.org" target="_blank">
        <img border="0" alt="PP Chain logo" src="https://github.com/shadowboxingskills/ppchainR/blob/master/logo.svg?raw=true" width="340" height="auto" style="background-color: transparent;
border: none;">
    </a>
</p>
<h2 align="center" style="border-bottom: none">Your Probabilistic Modeling Copilot</h2>

<br/>

[![Documentation Status](https://readthedocs.org/projects/ppchain/badge/?version=latest)](https://ppchain.readthedocs.io/en/latest/?version=latest)

[![Open Issues](https://img.shields.io/github/issues-raw/shadowboxingskills/ppchainR)](https://github.com/shadowboxingskills/ppchainR/issues)

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<br/>

## 🤔 What is this?

Generative AI meets Probabilistic Programming.
`ppchain` an open-source toolkit for intuitive, effective modeling.
Your copilot to build model internal representations and optimize your Bayesian workflow.

<br>

## 🚀 What can this help with?

`ppchain` aims to ease the pains of building a model.

Following the 3 main steps of the Bayesian data analysis process, as defined in [1], `ppchain` provides a (progressively growing) toolbox of AI-assisted functions aiming to make your life easier along the way:

1. Setting up a full probability model—a joint probability distribution for all observable and unobservable quantities in a problem. `ppchain` searches for domain knowledge about your underlying problem and helps building an internal representation that is consistent with both background knowledge and collected data.

2. Conditioning on observed data: calculating and interpreting the appropriate posterior distribution—the conditional probability distribution of the unobserved quantities of ultimate interest, given the observed data.

3. Evaluating the fit of the model and the implications of the resulting posterior distribution: how well does the model fit the data? are the substantive conclusions reasonable? and how sensitive are the results to the modeling assumptions made?

<br>

## Technical

_TK: Instructions on how to bootstrap project, run ETL processes, etc._

An outline of the basic project structure is available at https://github.com/associatedpress/cookiecutter-r-project

### Project setup instructions

After cloning the git repo:

`datakit data pull` to retrieve the data files.

Open `ppchainr.Rproj` in RStudio.

_TK: For more complex or unusual projects additional directions follow_

<br>

## 💁 Contributing

Contributions are very welcome, whether it is in the form of a new feature, improved infrastructure, or better documentation.
For detailed information on how to contribute, see [CONTRIBUTING](https://github.com/shadowboxingskills/ppchainR/blob/master/CONTRIBUTING.rst).

If you are interested to get further involved with the ValueGrid\_ team, please [contact us](mailto:nawel@valuegrid.io?subject=[GitHub]%20PPChainR).

## License

Usage is provided under the MIT license.
See [LICENSE](https://github.com/shadowboxingskills/ppchainR/blob/master/LICENSE) for full details.

## Credits

- Initial inspiration for this package came from [Thomas Wiecki, PhD](https://www.linkedin.com/in/twiecki) and [Daniel Lee](https://www.linkedin.com/in/syclik), as explained in more details in this [LinkedIn post](https://www.linkedin.com/pulse/harnessing-gpts-next-significant-advancement-marc-fournier-carrie) and [Medium article](https://medium.com/@marc.fourniercarrie/harnessing-gpts-for-the-next-significant-advancement-in-probabilistic-programming-70ccfc33846f).
