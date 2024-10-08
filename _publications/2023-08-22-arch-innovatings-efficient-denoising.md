---
title: "Pushing Joint Image Denoising and Classification to the Edge"
collection: publications
permalink: /publication/2024-09-29-dcnas
excerpt: 'In this paper, we jointly combine image classification and image denoising, aiming to enhance human perception of noisy images captured by edge devices, like low-light security cameras. In such settings, it is important to retain the ability of humans to verify the automatic classification decision and thus jointly denoise the image to enhance human perception. Since edge devices have little computational power...'
date: 2024-09-29
venue: 'ECCV Workshop'
paperurl: 'https://arxiv.org/abs/2409.08943'
citation: 'Thomas C. Markhorst, Jan C. van Gemert, Osman S. Kayhan. (2024). &quot;Pushing Joint Image Denoising and Classification to the Edge&quot; <i>ECCV-W</i>.'
---

In this paper, we jointly combine image classification and image denoising, aiming to enhance human perception of noisy images captured by edge devices, like low-light security cameras. In such settings, it is important to retain the ability of humans to verify the automatic classification decision and thus jointly denoise the image to enhance human perception. Since edge devices have little computational power, we explicitly optimize for efficiency by proposing a novel architecture that integrates the two tasks. Additionally, we alter a Neural Architecture Search (NAS) method, which searches for classifiers to search for the integrated model while optimizing for a target latency, classification accuracy, and denoising performance. The NAS architectures outperform our manually designed alternatives in both denoising and classification, offering a significant improvement to human perception. Our approach empowers users to construct architectures tailored to domains like medical imaging, surveillance systems, and industrial inspections.