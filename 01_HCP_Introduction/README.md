# 01 - HCP Introduction

## 🎯 Objectives

The goal of this section is to understand the Human Connectome Project (HCP) and become familiar with its datasets, imaging modalities, and overall organization.

By the end of this section, I should be able to:

- Explain what the Human Connectome Project is
- Understand the HCP Young Adult dataset
- Identify the major neuroimaging modalities
- Understand basic HCP terminology
- Navigate the organization of HCP data
- Understand the difference between structural, functional, and diffusion MRI

---

## 🧠 What is the Human Connectome Project?

The Human Connectome Project (HCP) is a large-scale neuroimaging project designed to study the structural and functional connectivity of the human brain.

The project provides multimodal neuroimaging, behavioral, and demographic data that can be used to investigate how brain organization relates to cognition and behavior.

---

## 👥 HCP Young Adult Dataset

The HCP Young Adult dataset contains multimodal neuroimaging and behavioral data collected from healthy young adults.

The dataset includes several types of information, including:

- Structural MRI
- Functional MRI
- Diffusion MRI
- Behavioral measurements
- Demographic information

---

## 🧲 Major MRI Modalities

### T1-weighted MRI

T1w MRI provides high-resolution anatomical information about the brain.

It can be used to study:

- Brain anatomy
- Cortical structure
- Gray matter
- White matter
- Cortical thickness

### T2-weighted MRI

T2w MRI provides additional anatomical information and can be used together with T1w images for structural analysis.

### Resting-State fMRI

Resting-state fMRI measures spontaneous changes in blood oxygenation while participants are not performing a specific task.

It can be used to study:

- Functional connectivity
- Brain networks
- Resting-state networks
- Network organization

### Task fMRI

Task fMRI measures brain activity while participants perform specific cognitive or behavioral tasks.

Examples include:

- Working memory
- Language
- Motor tasks
- Social cognition
- Emotion processing
- Decision making

### Diffusion MRI

Diffusion MRI provides information about the movement of water molecules in brain tissue and can be used to investigate white-matter pathways.

It is commonly used for:

- Structural connectivity
- Tractography
- White-matter analysis

---

## 📊 HCP Data Types

The HCP dataset can contain several categories of information:

| Data Type | Purpose |
|---|---|
| T1w | Structural anatomy |
| T2w | Structural anatomy |
| fMRI | Functional brain activity |
| dMRI | White-matter structure |
| Behavioral data | Cognition and behavior |
| Demographic data | Participant information |

---

## 🔑 Important Terminology

### Participant

An individual whose data are included in the dataset.

### Subject ID

A unique identifier assigned to a participant.

### Structural MRI

MRI data describing anatomical brain structure.

### Functional MRI

MRI data used to study changes associated with brain activity.

### Diffusion MRI

MRI data used to investigate white-matter organization and structural connectivity.

### Functional Connectivity

A statistical relationship between activity patterns in different brain regions.

### Structural Connectivity

Physical connections between brain regions, primarily through white-matter pathways.

---

## 📁 HCP Data Organization

HCP datasets are organized into folders containing different types of imaging and participant-level information.

A typical subject may have data organized into categories such as:

```text
Subject/
│
├── T1w/
├── MNINonLinear/
├── MNINonLinear/
├── Results/
└── diffusion/

## 🛠️ Tools

The main tools and technologies I will use throughout this project include:

- 🐍 Python
- 📓 Jupyter Notebook
- 🧠 NiBabel
- 🔬 Nilearn
- 🖥️ HCP Workbench
- 🧪 FSL
- 🌐 Git & GitHub

---

## 📚 Learning Tasks

- [ ] Read about the Human Connectome Project
- [ ] Understand the HCP Young Adult dataset
- [ ] Learn the major MRI modalities
- [ ] Understand structural vs functional connectivity
- [ ] Explore HCP dataset organization
- [ ] Download a sample of HCP data
- [ ] Inspect a participant's data

---

## 🧪 Practical Exercise

After learning the basic concepts, I will download a small sample of HCP data and inspect:

- File names
- File formats
- Directory structure
- Imaging modalities
- Participant metadata

The goal is to understand the dataset before performing any analysis.

---

## 📈 Progress

### Status

🟡 In Progress

### Completed

- [ ] HCP overview
- [ ] HCP Young Adult dataset
- [ ] MRI modalities
- [ ] HCP terminology
- [ ] HCP data organization
- [ ] First dataset exploration

---

## ➡️ Next Step

After completing this section, the next step will be:

### 02 - Neuroimaging Data Formats

Topics:

- NIfTI
- GIfTI
- CIFTI
- Grayordinates
- Volumetric vs Surface Data
