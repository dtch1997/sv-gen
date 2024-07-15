---
title: 'Home'
date: 2023-10-24
type: landing

sections:
  - block: markdown
    content:
      title: Analyzing the Generalization and Reliability of Steering Vectors
      text: We find that steering vectors can often fail to work in- and out-of-distribution. We propose "steerability", a new metric for steering vectors, and extensively evaluate it across 40 datasets. We find that steerability is highly variable across different inputs. Depending on the concept, spurious biases can substantially contribute to how effective steering is for each input. Overall, our findings show that while steering can work well in the right circumstances, there remain mnany technical difficulties of applying steering vectors to guide models' behaviour at scale, and higher standards of evidence are required when applying steering vectors to models on novel tasks. 
    design:
      css_class: dark
      background:
        color: black
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Read our paper
          icon: academicons/arxiv
          url: https://drive.google.com/file/d/10DDi0wPFlw9yItmTaY03LPJptuFyTG8P/view?usp=sharing
        - text: View our poster
          icon: brands/google
          url: https://drive.google.com/file/d/1xCMGCExBfyGivAhTV3-piU8CxVVPkC_5/view?usp=sharing 
        - text: Use our steering-vectors library
          icon: brands/github
          url: https://github.com/steering-vectors/steering-vectors/  
        - text: Reproduce our experiments
          icon: brands/github
          url: https://github.com/dtch1997/repepo
    design:
      css_class: dark
      background:
        color: black

---
