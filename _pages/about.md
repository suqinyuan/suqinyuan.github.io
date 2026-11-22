---
layout: homepage
permalink: /
redirect_from:
  - /about/
  - /about.html
bio: |-
  I am a postdoctoral researcher at the [University of Sydney](https://www.sydney.edu.au), where I also did my PhD with [Tongliang Liu](https://tongliang-liu.github.io). I was named an Outstanding Reviewer at ICLR, ICML, NeurIPS, and CVPR.

  I study overfitting in machine learning. My current work focuses on LLM pre- and post-training, particularly

research_questions:
  - AI that acts as a person rather than an assistant
  - When we run out of high-quality pretraining data
  - How a strong model can teach a weaker one

sections:
  - id: recent-work
    title: Recent Work
    papers:
      - title: Decoupling Token Roles in Autoregressive Pretraining
        other_authors: Runqi Lin, Kevin Qinghong Lin, Junchi Yu, Lei Feng, Chris Russell, Tongliang Liu
        image: tokens.png
        alt: Figure 3. GPT-2 validation loss during training with random versus predictable replacements under clean, standard, target-only and context-only conditions.
        summary: Making a corrupted token easier to predict makes it less harmful as a training target but more harmful as context for the next tokens.
        venues:
          - label: "arXiv:2609.33405"
            year: 2026
            links:
              - label: Paper
                url: https://arxiv.org/pdf/2609.33405

      - title: Are Human-Aligned LLMs Models of Humans? A Turing-Test Gap in Preference Alignment
        other_authors: Runqi Lin, Muyang Li, Guanzhe Hong, Jindong Gu, Lei Feng, Chris Russell, Tongliang Liu
        image: human.png
        image_scale: 0.8
        alt: Comparison of human response frequencies with the frequencies obtained after weighting responses by preference.
        summary: Optimizing for what people prefer can systematically make model responses less human-like.
        venues:
          - label: "arXiv:2609.23640"
            year: 2026
            links:
              - label: Paper
                url: https://arxiv.org/abs/2609.23640

      - title: Understanding Diversity Collapse in RLVR via the Lens of Overtraining
        other_authors: Jinkun Chen, Jiyang Zheng, Muyang Li, Lei Feng, Dadong Wang, Tao Xiang, Tongliang Liu, Bo An
        image: rlvr.png
        alt: Training updates allocated to different problems alongside the model’s Pass@256 score.
        summary: Much of the diversity collapse observed in RLVR can be explained by overtraining.
        venues:
          - label: "arXiv:2606.15455"
            year: 2026
            links:
              - label: Paper
                url: https://arxiv.org/pdf/2606.15455

  - id: publications
    title: Publications
    papers:
      - title: Mitigating Mismatch within Reference-based Preference Optimization
        other_authors: Xingrui Yu, Jiyang Zheng, Lei Feng, Dadong Wang, Ivor Tsang, Tongliang Liu
        image: hypo.webp
        compact_image: true
        alt: Gradient weights for HyPO across policy and reference preference margins.
        summary: DPO’s reference model can weaken learning when it favors the rejected response. We remove its contribution only for those preference pairs.
        venues:
          - label: ICLR
            url: https://iclr.cc/Conferences/2026
            year: 2026
            links:
              - label: Paper
                url: https://openreview.net/pdf?id=k79Un1LSXy
              - label: Code
                url: https://github.com/tmllab/2026_ICLR_HyPO

      - title: Instance-Dependent Early Stopping for Adaptive Data Pruning
        title_url: https://ieeexplore.ieee.org/document/11517544
        other_authors: Runqi Lin, Felix Azian, Lei Feng, Bo Han, Gang Niu, Masashi Sugiyama, Tongliang Liu
        image: ies.webp
        alt: Accuracy and fraction of training examples used on CIFAR-10 and ImageNet-1k.
        summary: If overfitting can be benign, we should decide when to stop training on each example individually.
        venues:
          - label: IEEE Transactions on Pattern Analysis and Machine Intelligence
            url: https://www.computer.org/csdl/journal/tp
            year: 2026
          - label: ICLR
            prefix: also at
            url: https://iclr.cc/Conferences/2025
            year: 2025
            note: Spotlight
            links:
              - label: Paper
                url: https://openreview.net/pdf?id=P42DbV2nuV
              - label: Code
                url: https://github.com/tmllab/2025_ICLR_IES

      - title: Early Stopping Without Validation Data in Weakly Supervised Learning
        title_url: https://ieeexplore.ieee.org/document/11604166
        other_authors: Muyang Li, Lei Feng, Bo Han, Gang Niu, Masashi Sugiyama, Tongliang Liu
        image: labelwave.webp
        alt: Changes in predicted labels during training plotted alongside test error.
        summary: We can track how well a model generalizes simply by monitoring how its predictions change on the training set.
        venues:
          - label: IEEE Transactions on Pattern Analysis and Machine Intelligence
            url: https://www.computer.org/csdl/journal/tp
            year: 2026
          - label: ICLR
            prefix: also at
            url: https://iclr.cc/Conferences/2024
            year: 2024
            links:
              - label: Paper
                url: https://openreview.net/pdf?id=CMzF2aOfqp
              - label: Code
                url: https://github.com/tmllab/2024_ICLR_LabelWave

      - title: Enhancing Sample Selection Against Label Noise by Cutting Mislabeled Easy Examples
        other_authors: Lei Feng, Bo Han, Tongliang Liu
        image: earlycutting.webp
        alt: Six CIFAR-10 images with incorrect labels that the model learns early in training.
        summary: Some mislabeled examples are easier for a model to learn than correctly labeled ones.
        venues:
          - label: NeurIPS
            url: https://neurips.cc/Conferences/2025
            year: 2025
            links:
              - label: Paper
                url: https://openreview.net/pdf?id=OfIUAlo2hJ
              - label: Code
                url: https://github.com/tmllab/2025_NeurIPS_MEE

      - title: "Late Stopping: Avoiding Confidently Learning from Mislabeled Examples"
        other_authors: Lei Feng, Tongliang Liu
        image: latestopping.webp
        compact_image: true
        alt: Distributions showing when a network first learns clean and mislabeled CIFAR-10 examples.
        summary: A larger initial set of examples can start a positive feedback loop for iterative sample selection.
        venues:
          - label: ICCV
            url: https://iccv2023.thecvf.com
            year: 2023
            links:
              - label: Paper
                url: https://openaccess.thecvf.com/content/ICCV2023/papers/Yuan_Late_Stopping_Avoiding_Confidently_Learning_from_Mislabeled_Examples_ICCV_2023_paper.pdf
              - label: Code
                url: https://github.com/tmllab/2023_ICCV_LateStopping

background:
  - title: Education
    entries:
      - institution: The University of Sydney
        dates: 2022–2026
        role: PhD in Computer Science
        detail: "Advisor: Tongliang Liu"
        url: https://tongliang-liu.github.io
      - institution: Chongqing University
        dates: 2018–2022
        role: BEng in Computer Science
        detail: "Advisor: Lei Feng"
        url: https://lfeng1995.github.io
  - title: Research Experience
    entries:
      - institution: University of Oxford
        dates: Mar–Sep 2026
        role: Student Visitor
        detail: Torr Vision Group
        url: https://torrvision.com/
      - institution: Nanyang Technological University
        dates: Dec 2025 – Feb 2026
        role: Visiting Student
        detail: AI-for-X Centre
        url: https://www.ntu.edu.sg/ai-x
      - institution: Agency for Science, Technology and Research (A*STAR)
        dates: Aug–Dec 2025
        role: Research Officer
        detail: Centre for Frontier AI Research
        url: https://www.a-star.edu.sg/cfar
---

## Honors and Awards

- USYD Faculty of Engineering Career Advancement Award, *2025*
- 12th China Youth Science and Technology Innovation Award, 100 recipients biennially, *2020* 
- 26th China High School Biology Olympiad, First Prize, ranked 12th, *2017*
