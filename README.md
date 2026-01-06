# "Developers and Generative AI: A Study of Self-Admitted Usage in Open Source Projects"

This is the replication package of the work *"Developers and Generative AI: A Study of Self-Admitted Usage in Open Source Projects"*

## Content

The two folders `chatgpt` and `copilot` contain the same type of files for the two analysis conducted. 
In particular they contain:

- `<AI-tool>_discarded_instances.csv`: contains the instances discarded during the manual analysis. Each instance comes with its category (commit/issue/PR) and the link to open the instance on GitHub.
- `<AI-tool>_labeled_instances.csv`: contains the valid instances used to build the taxonomy. Each instance comes with the assigned label(s), its category (commit/issue/PR) and the link to open the instance on GitHub.
- `<AI-tool>_labels.csv` : contains the labels that make up the taxonomy. Each label comes with the number of instances (commit/issue/PR) tagged with it.
- `<AI-tool>_ngrams.txt` : contains the list of n-grams used to select the instances to analyze from the initial dataset.
- `taxonomy_<AI-tool>.png`: is the representation of the taxonomy built on top of the manual analysis (shown also below)

## Utils

In this study we used the labeler platform from the SEART group (https://github.com/seart-group/labeler) to facilitate manual labeling.

## Taxonomies

### Taxonomy for ChatGPT
![taxonomy_chatgpt](./chatgpt/taxonomy_chatgpt.png?raw=true)


### Taxonomy for Copilot
![taxonomy_copilot](./copilot//taxonomy_copilot.png?raw=true)

### Merged Taxonomy
![merged_taxonomy](./merged_taxonomy.png?raw=true)
