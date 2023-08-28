<p align="center">
    <a href="https://ppchain.org" target="_blank">
        <img border="0" alt="PP Chain logo" src="https://github.com/shadowboxingskills/ppchainR/blob/master/logo.svg?raw=true" width="340" height="auto" style="background-color: transparent;
border: none;">
    </a>
</p>
<h2 align="center" style="border-bottom: none">Your Probabilistic Modeling Copilot</h2>

<br/>

[![Documentation Status](https://readthedocs.org/projects/ppchain/badge/?version=latest)](https://ppchain.readthedocs.io/en/latest/?version=latest) [![Open Issues](https://img.shields.io/github/issues-raw/shadowboxingskills/ppchainR)](https://github.com/shadowboxingskills/ppchainR/issues) [![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<br/>

## 🤔 What is this?

Generative AI meets Probabilistic Programming.
`ppchain` an open-source toolkit for intuitive, effective modeling.
Your copilot to build model internal representations and optimize your Bayesian workflow.

<br>

## 🚀 What can this help with?

`ppchain` aims to ease the pains of building a model.

Following the 3 main steps of the Bayesian data analysis process, as defined in [[1]](#1), `ppchain` provides a (progressively growing) toolbox of AI-assisted functions aiming to make your life easier along the way:

1. Setting up a full probability model—a joint probability distribution for all observable and unobservable quantities in a problem. `ppchain` searches for domain knowledge about your underlying problem and helps building an internal representation that is consistent with both background knowledge and collected data.

2. Conditioning on observed data: calculating and interpreting the appropriate posterior distribution—the conditional probability distribution of the unobserved quantities of ultimate interest, given the observed data.

3. Evaluating the fit of the model and the implications of the resulting posterior distribution: how well does the model fit the data? are the substantive conclusions reasonable? and how sensitive are the results to the modeling assumptions made?

<br>

## ⚙ Workflow

`ppchain` provides a (progressively growing) set of AI-assisted functions to progress through the following workflow (where $P$ denotes a probability distribution, $\theta$ the parameters, and $y$ the data):

- Define the problem statement

  - Problem statement (conversational AI)
  - Specify hypothesis
  - Select model type
  - Data collection method

- Formalize priors, $P(\theta)$

  - Search for background knowledge
  - Prior elicitation
  - Formalize prior distributions
  - Prior predictive checks

- Determine the likelihood function, $P(y \mid \theta)$

  - Search for background knowledge
  - Load & preprocess data
  - Formalize the likelihood function

- Compute the posterior distribution, $P(\theta \mid y) \propto P(y \mid \theta) P(\theta)$

  - Variables selection, identifying the subset of predictors to include in the model
  - Determine the functional form of the model
  - Fit the model to the observed data to estimate the unknown model parameters
  - Compute posterior distribution

- Run posterior inference

  - Compute posterior inference
  - Posterior predictive checking
  - Sensitivity analysis
  - Make predictions about future events

<br>

## 📖 Documentation

- Documentation: https://ppchain.readthedocs.io

<br>

## 💁 Contributing

Contributions are very welcome, whether it is in the form of a new feature, improved infrastructure, or better documentation. Please use [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/shadowboxingskills/ppchainR/pulls/).

If you are interested to get further involved with the <a href="https://valuegrid.io" target="_blank">ValueGrid</a> team, please [contact us](mailto:nawel@valuegrid.io?subject=[GitHub]%20APPChainR).

<br>

## License

Usage is provided under the MIT license.
See [LICENSE](https://github.com/shadowboxingskills/ppchainR/blob/master/LICENSE) for full details.

<br>

## Credits

- Initial inspiration for `ppchain` came from [Thomas Wiecki, PhD](https://www.linkedin.com/in/twiecki) and [Daniel Lee](https://www.linkedin.com/in/syclik), as explained in more details in this [LinkedIn post](https://www.linkedin.com/pulse/harnessing-gpts-next-significant-advancement-marc-fournier-carrie) and [Medium article](https://medium.com/@marc.fourniercarrie/harnessing-gpts-for-the-next-significant-advancement-in-probabilistic-programming-70ccfc33846f).

<a id="1">[1]</a> Gelman, A., Carlin, J. B., Stern, H. S., Dunson, D. B., Vehtari, A. & Rubin, D. B. (2013). Bayesian data analysis (3rd ed.). Chapman & Hall/CRC

<br>
