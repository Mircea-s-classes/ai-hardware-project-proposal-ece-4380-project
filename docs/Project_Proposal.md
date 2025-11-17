# University of Virginia
## Department of Electrical and Computer Engineering

**Course:** ECE 4332 / ECE 6332 — AI Hardware Design and Implementation  
**Semester:** Fall 2025  
**Proposal Deadline:** November 5, 2025 — 11:59 PM  
**Submission:** Upload to Canvas (PDF) and to GitHub (`/docs` folder)

---

# AI Hardware Project Proposal Template

## 1. Project Title
ECE 4380 Project

Daniel Lee

Multimodal Models at the Edge: CPU vs. GPU vs. VPU vs. TPU

## 2. Platform Selection
Select one platform category and justify your choice.

**Undergraduates:** Edge-AI, TinyML, or Neuromorphic platforms  
**Graduates:** open-source AI accelerators (Ztachip, VTA, Gemmini, VeriGOOD-ML, NVDLA) or any of the above 

This project will aim to compare the NVIDIA Jetson, Google Coral Edge TPU, and Intel Movidius Myriad X VPU platforms, per availability.

## 3. Problem Definition
Describe the AI or hardware design problem you aim to address and its relevance to AI hardware (e.g., efficiency, latency, scalability).

Building off previous work on facial expression recognition, this work seeks to provide a similar framework to develop and optimize large multimodal CNNs for deployment at the edge.

## 4. Technical Objectives
List 3–5 measurable objectives with quantitative targets when possible.

- Achieve accuracy of at least 0.9 on various model sizes
- Achieve an accuracy/latency of at least 0.5 on various model sizes
- For at least one platform, achieve a power consumption < 1 W

## 5. Methodology
Describe your planned approach: hardware setup, software tools, model design, performance metrics, and validation strategy.

The approach will mirror the methodologies followed in the *Facial Expression Recognition at the Edge:
CPU vs GPU vs VPU vs TPU* paper, utilizing the Hyperopt Python library for hyperparameter tuning. For the general structure of the CNNs, the architecture outlined in *Learning Sparse Mixture of Experts for Visual Question Answering* will be utilized.

## 6. Expected Deliverables
List tangible outputs: working demo, GitHub repository, documentation, presentation slides, and final report.

- Comprehensive framework for developing and optimizing multimodal CNNS at the edge
- Accuracy, latency, and power consumption results across different model sizes and devices

## 7. Team Responsibilities
List each member’s main role.

| Name | Role | Responsibilities |
|------|------|------------------|
| Daniel | Team Lead | Hardware, Software, Evaluation |

## 8. Timeline and Milestones
Provide expected milestones:

| Week | Milestone | Deliverable |
|------|------------|-------------|
| 2 | Proposal | PDF + GitHub submission |
| 4 | Midterm presentation | Slides, preliminary results |
| 6 | Integration & testing | Working prototype |
| Dec. 18 | Final presentation | Report, demo, GitHub archive |

## 9. Resources Required
List special hardware, datasets, or compute access needed.

- Raspberry Pi
- Coral Dev Board
- Coral USB
- Intel Neural Compute Stick
- NVIDIA Jetson
- Multimeter

## 10. References
Include relevant papers, repositories, and documentation.

Mohammadi, M., Smith, H., Khan, L., & Zand, R. (2023). Facial Expression Recognition at the Edge: CPU vs GPU vs VPU vs TPU. In Proceedings of the Great Lakes Symposium on VLSI 2023 (pp. 243–248). ACM.

Vardaan Pahuja, Jie Fu, & Christopher J. Pal. (2019). Learning Sparse Mixture of Experts for Visual Question Answering.
