## REVE-CE: Remote Embodied Visual Referring Expression in Continuous Environment

Enabling robotics to execute actions in visual world via natural language instructions is a consistent goal and challenge. Recently, several datasets are released to solve this challenge including Vision Language Navigation (VLN) and Remote Embodied Visual Referring Expression in Real Indoor Environments (REVERIE). Compared to VLN, REVERIE is closer with the original intention of this challenge since its has higher guidance level instructions and referring target object for each trajectory. However, the navigation process of REVERIE is based on a navigation graph provided by the discrete environment, which is unrealistic in the unseen scenes in real world. To make REVERIE task more consistent with the physical world, we develop a remote embodied visual referring expression task in a continuous 3D environment in which agent is required to execute a munch longer sequence of low-level actions under the guidance of language instructions, namely REVE-CE. We provide a suite of baselines transferred from the state-of-art works in VLN and find that they could not perform well on REVE-CE. Further, we propose a multi-branch cross modal attention (MBCMA) framework and test it on REVE-CE, and our proposed framework outperforms existing baselines on REVE-CE over all key metrics and set a new benchmark for REVE-CE.


Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/lixinghang12/REVE_CE/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
