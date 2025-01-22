# TransformaerLens

# TransformerLens Demo: Exploring Language Model Interpretability

This repository demonstrates the use of the TransformerLens library for mechanistic interpretability of GPT-2 style language models. It provides a hands-on exploration of how these models work by dissecting their internal components and behaviors.

## Key Features:

- **Loading and Running Models:**  Easily load pre-trained GPT-2 Small model and run inference on text inputs.
- **Caching all Activations:** Access and visualize internal activations (attention patterns, hidden states) during model execution.
- **Hooks: Intervening on Activations:**  Inject custom functions to modify activations, enabling experiments like activation patching to understand causal importance.
- **Hooks: Accessing Activations:**  Extract specific activation values for further analysis and exploration.
- **Available Models:** Explore a wide range of pre-trained models, including GPT-2 variants, GPT-Neo, OPT, and more.
- **Visualization with CircuitsVis:**  Utilize CircuitsVis to interactively visualize attention patterns and understand model behavior.
- **Induction Head Analysis:**  Identify and analyze induction heads, revealing how the model detects and continues repeated sequences.
- **Indirect Object Identification (IOI) Task:**  Apply activation patching to the IOI task to uncover the key activations involved in its solution.

## Usage:

- Clone this repository: `git clone https://github.com/imaiimaiimaiimaiimaiimai/TransformaerLens.git`
- Install required libraries: `pip install torch einops fancy_einsum tqdm plotly jaxtyping transformer_lens circuitsvis`
- Open the Jupyter Notebook (`Main_Demo.ipynb`) and run the cells to explore the demos.

## Resources:

- **TransformerLens Library:** [https://github.com/TransformerLensOrg/TransformerLens](https://github.com/TransformerLensOrg/TransformerLens)
- **CircuitsVis Library:** [https://github.com/alan-cooney/CircuitsVis](https://github.com/alan-cooney/CircuitsVis)
- **Mechanistic Interpretability Explainer:** [https://neelnanda.io/glossary](https://neelnanda.io/glossary)
- **Concrete Open Problems in Mechanistic Interpretability:** [https://neelnanda.io/concrete-open-problems](https://neelnanda.io/concrete-open-problems)

## Contributing:

Feel free to contribute by opening issues, suggesting improvements, or submitting pull requests. 


