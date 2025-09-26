---
layout: home
title: AI Universe
permalink: /
---

Connecting the dots in AI Universe





# 🌌 AI Universe Courses

**Welcome to \*AI Universe Courses\*** — a curated gateway into the vast world of Artificial Intelligence.
 This project brings together free and open-access courses across the entire AI spectrum:

- **Machine Learning (ML)** — foundations, algorithms, applied ML.
- **Deep Learning (DL)** — neural networks, transformers, generative models.
- **Large Language Models (LLMs)** — advanced NLP, prompt engineering, applications.
- **Natural Language Processing (NLP)** — text mining, embeddings, classic methods.
- **Computer Vision (CV)** — image recognition, visual perception, applied vision AI.
- **Reinforcement Learning (RL)** — agents, robotics, decision-making under uncertainty.
- **Ethics & Governance** — responsible AI, fairness, interpretability, compliance.

Our goal is simple: **make world-class AI education accessible to everyone**.
 Whether you’re a beginner exploring your first ML model or an advanced learner diving into LLM architectures, this repo is your map through the AI cosmos.



## How to Get Started

This theme can be used just as other [Jekyll themes][1] and support [remote theme][12],
see [the official guide][13] as well.

You can introduce this jekyll theme into your own site by either

- [Fork][3] this repository and add your markdown posts to the `_posts` folder.
- Use as a remote theme in your [`_config.yml`][14](just like what we do for this
  site itself),

```yaml
remote_theme: sighingnow/jekyll-gitbook
```

### Deploy Locally with Jekyll Serve

This theme can be ran locally using Ruby and Gemfiles.

[Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) - GitHub

## Full-text search

The search functionality in jekyll-gitbook theme is powered by the [gitbook-plugin-search-pro][5] plugin and is enabled by default.

[https://sighingnow.github.io/jekyll-gitbook/?q=generated](https://sighingnow.github.io/jekyll-gitbook/?q=generated)

## Code highlight

The code highlight style is configurable the following entry in `_config.yaml`:

```yaml
syntax_highlighter_style: colorful
```

The default code highlight style is `colorful`, the full supported styles can be found from [the rouge repository][6]. Customized
style can be added to [./assets/gitbook/rouge/](./assets/gitbook/rouge/).

## How to generate TOC

The jekyll-gitbook theme leverages [jekyll-toc][4] to generate the *Contents* for the page.
The TOC feature is not enabled by default. To use the TOC feature, modify the TOC
configuration in `_config.yml`:

```yaml
toc:
    enabled: true
    h_min: 1
    h_max: 3
```

## Google Analytics, etc.

The jekyll-gitboook theme supports embedding the [Google Analytics][7], [CNZZ][8] and [Application Insights][9] website analytical tools with the following
minimal configuration in `_config.yaml`:

```yaml
tracker:
  google_analytics: "<YOUR GOOGLE ANALYTICS KEY, e.g, UA-xxxxxx-x>"
```

Similarly, CNZZ can be added with the following configuration in `_config.yaml
