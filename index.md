# Giuseppe Marco Randazzo, PhD

### Staff Computational Scientist | Cheminformatics, AI Drug Discovery & High-Performance Computing
**Lugano, Switzerland**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-gmrandazzo-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/gmrandazzo/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Citations-4285F4?style=flat&logo=googlescholar)](https://scholar.google.com/citations?user=wVq-c3IAAAAJ&hl=en)
[![GitHub](https://img.shields.io/badge/GitHub-gmrandazzo-181717?style=flat&logo=github)](https://github.com/gmrandazzo)
[![Email](https://img.shields.io/badge/Email-gmrandazzo%40gmail.com-D14836?style=flat&logo=gmail)](mailto:gmrandazzo@gmail.com)

> I take drug discovery programs from computational design to the clinic. Over the past 15+ years, I have designed and shipped production cheminformatics software, physics-based simulations, and machine learning systems in C, C++, CUDA, and Python.
>
> The computational discovery pipelines I led at Endogena Therapeutics helped advance **one small-molecule candidate into human clinical trials and a second to IND approval**. At Chemify, I lead the computational architecture across **6+ commercial discovery programs** for global pharma and biotech partners, combining trillion-scale chemical space search, biomolecular cofolding, and free-energy methods.

---

## Key Industry Outcomes

* **From In Silico to Human Clinical Trials (Endogena Therapeutics)**: Led the machine learning and structure-based design pipelines behind **1 small-molecule candidate in human clinical trials and a 2nd compound advanced to IND**, co-authoring core composition-of-matter patents.
* **Trillion-Scale Chemical Space Search (Chemify Ltd.)**: Built de novo generation and synthon-space indexing algorithms that query **multi-trillion virtual compound spaces in under 180 ms** to drive automated robotic synthesis for the **Gates Foundation**, **Dewpoint Therapeutics**, and confidential biopharma partners.
* **Commercial Pipeline Delivery (Chemify Ltd.)**: Led computational design across 6+ target portfolios with a **100% project progression rate** (zero early terminations), delivering potency-enhanced lead series and building foundational computational tools that supported a new automated synthesis facility and a **$50M Series B financing**.
* **Core Open-Source Machine Learning (CatBoost / Hoffmann-La Roche)**: Authored native multi-task regression with missing-value support in Yandex's **[CatBoost](https://github.com/catboost/catboost/pull/1680)** (PR #1680), solving the sparse experimental bioassay matrix problem common in industrial screening.

---

## Experience

* **Staff Computational Scientist** | **Chemify Ltd.** *(Glasgow, UK & Lugano, Switzerland)* | `2023 - Present`  
  Lead computational architect for trillion-scale de novo molecular generation, biomolecular cofolding (Boltz-2 fine-tuning), autonomous agentic DMTA workflows, and multi-parameter lead optimization across commercial programs.

* **Head of AI and Cheminformatics** | **Endogena Therapeutics** *(Zurich, Switzerland)* | `2021 - 2023`  
  Directed AI, QSAR/QSPR, and structure-based discovery for regenerative medicine and fibrosis; architected the company's multi-GPU compute infrastructure and scientific data platforms.

* **Postdoctoral Research Scientist** | **Hoffmann-La Roche** *(Basel, Switzerland)* | `2019 - 2021`  
  Developed multi-task deep learning and gradient boosting methods for on-target potency and off-target safety profiling across sparse screening matrices.

* **Research Scientist** | **Dalle Molle Institute for Artificial Intelligence (IDSIA)** *(Lugano, Switzerland)* | `2017 - 2019`  
  Pioneered 3D geometric deep learning on voxelized quantum and electrostatic molecular fields for early-stage drug discovery (Innosuisse ARCADIA project).

* **Postdoctoral Researcher & External CADD Consultant** | **University of Geneva & Firmenich** *(Geneva, Switzerland)* | `2014 - 2017`  
  Independently discovered novel LIM Kinase inhibitors via structure-based modeling; built physicochemical property prediction platforms with the Swiss Institute of Bioinformatics (Vital-IT).

---

## Core Capabilities & Stack

* **Structure, Physics & Target Modalities**: Boltz-2 and AlphaFold cofolding, Relative Binding Free Energy (OpenFE RBFE, AMBER-TI), Molecular Dynamics, QM/MM, docking (GOLD, AutoDock, DiffDock). Applied across **Ion Channels, Protein-Protein Interactions (PPIs), Peptidomimetics, Small Molecules, Kinases, HDACs, Sirtuins, and Epigenetics** *(Oncology, Regenerative Medicine, Fibrosis/IPF, CNS, Infectious Disease)*.
* **Cheminformatics, Machine Learning & Agentic AI**: Production cheminformatics (RDKit, synthon indexing, QSAR/QSPR, NIPALS PCA, PLS, Consensus PCA), Multi-Task Learning, 3D Voxel CNNs, GNNs, PyTorch, CatBoost, and autonomous LLM/agentic workflows (RAG and multi-agent tool orchestration connecting literature/patent data to simulation pipelines).
* **High-Performance Engineering & MLOps**: Modern C++ (C++20), ANSI C (C99), CUDA, Python (ctypes/C-API/FFI), Go, Rust; Apache Airflow, Dagster, MLflow, Kubernetes, Docker, and multi-GPU Linux HPC clusters.

---

## Selected Open-Source Systems & Scientific Platforms

<table width="100%">
  <tr>
    <td width="260" align="center">
      <img src="./assets/img/joss_badge.svg" width="210" alt="libscientific JOSS"/>
    </td>
    <td align="left">
      <a href="https://github.com/gmrandazzo/libscientific"><b>libscientific: Zero-Dependency C Numerical Engine</b></a><br/>
      High-performance C99 library for multivariate statistical analysis, numerical optimization, and chemometrics with full Python FFI bindings. Designed for speed, reproducibility, and zero external dependencies.<br/><br/>
      <a href="https://doi.org/10.21105/joss.05420">
        <img src="https://img.shields.io/badge/Paper-JOSS%20(2023)-blue?style=flat-square" />
      </a>
      <img src="https://img.shields.io/badge/C99-A8B9CC?logo=c&logoColor=black&style=flat-square" />
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square" />
      <img src="https://img.shields.io/badge/License-GPL_v3-green?style=flat-square" />
    </td>
  </tr>

  <tr>
    <td width="260" align="center">
      <a href="https://github.com/catboost/catboost/pull/1680">
        <img src="./assets/img/catboost_logo.png" width="180" alt="CatBoost Logo"/>
      </a>
    </td>
    <td align="left">
      <a href="https://github.com/catboost/catboost/pull/1680"><b>CatBoost: Multi-Task Learning on Sparse Bioassay Matrices</b></a><br/>
      Engineered core C++/Python support in Yandex's CatBoost for multi-task regression with missing target labels, enabling simultaneous modeling of correlated biological endpoints across incomplete screening matrices.<br/><br/>
      <a href="https://github.com/catboost/catboost/pull/1680">
        <img src="https://img.shields.io/badge/PR-CatBoost%20%231680%20(Merged)-purple?style=flat-square" />
      </a>
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?logo=c%2B%2B&logoColor=white&style=flat-square" />
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square" />
      <img src="https://img.shields.io/badge/Multi--Task_ML-Sparse_Targets-orange?style=flat-square" />
    </td>
  </tr>

  <tr>
    <td width="260" align="center">
      <img src="./assets/img/qsmgui.png" width="230" alt="QStudioMetrics GUI"/>
    </td>
    <td align="left">
      <a href="https://github.com/gmrandazzo/QStudioMetrics"><b>QStudioMetrics: C++20 Multivariate & QSAR Suite</b></a><br/>
      Cross-platform C++20 desktop application for exploratory data analysis, PCA/PLS, MLR, and rigorous QSAR model validation (K-Fold cross-validation, Leave-One-Out, and Y-Scrambling).<br/><br/>
      <img src="https://img.shields.io/badge/C%2B%2B20-00599C?logo=c%2B%2B&logoColor=white&style=flat-square" />
      <img src="https://img.shields.io/badge/Qt-41CD52?logo=qt&logoColor=white&style=flat-square" />
      <img src="https://img.shields.io/badge/License-AGPL_v3-blue?style=flat-square" />
    </td>
  </tr>

  <tr>
    <td width="260" align="center">
      <img src="./assets/img/icp_conformer.gif" width="240" alt="ICP Conformer Alignment"/><br/>
      <img src="./assets/img/icp_vdwshape.gif" width="118" alt="VDW Shape Alignment"/>
      <img src="./assets/img/epotcalc.gif" width="118" alt="Electrostatic Potential"/>
    </td>
    <td align="left">
      <a href="https://github.com/gmrandazzo/MolecularFramework"><b>MolecularFramework: 3D Conformer & Electrostatic Field Engine</b></a><br/>
      C/C++ molecular modeling library implementing Iterative Closest Point (ICP) 3D conformer alignment, van der Waals surface shape similarity, and 3D molecular electrostatic potential field calculation.<br/><br/>
      <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?logo=c%2B%2B&logoColor=white&style=flat-square" />
      <img src="https://img.shields.io/badge/3D_Alignment-ICP_%26_VDW_Shape-informational?style=flat-square" />
      <img src="https://img.shields.io/badge/Electrostatic-3D_Fields-orange?style=flat-square" />
      <img src="https://img.shields.io/badge/License-GPL_v3-green?style=flat-square" />
    </td>
  </tr>

  <tr>
    <td width="260" align="center">
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S0021967319310830">
        <img src="./assets/img/3dcnn_showcase.png" width="240" alt="3D Electrostatic Potential Voxel Grid & 3D CNN Performance" title="3D Electrostatic Potential Voxel Grid & 3D CNN Accuracy"/>
      </a>
    </td>
    <td align="left">
      <a href="https://github.com/gmrandazzo/DeepMolecularNetwork"><b>DeepMolecularNetwork: 3D Quantum & Electrostatic Voxel CNNs</b></a><br/>
      Multi-modal deep learning framework utilizing 3D voxelized grids of quantum/force-field electrostatic potentials (B3LYP CHELPG, MMFF94, EEM) and electron density for physicochemical property prediction.<br/><br/>
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S0021967319310830">
        <img src="https://img.shields.io/badge/Paper-J.%20Chromatogr.%20A%20(2020)-b31b1b?style=flat-square" />
      </a>
      <a href="https://github.com/gmrandazzo/DeepMolecularNetwork">
        <img src="https://img.shields.io/badge/Code-DeepMolecularNetwork-black?logo=github&style=flat-square" />
      </a>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square" />
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=flat-square" />
    </td>
  </tr>

  <tr>
    <td width="260" align="center">
      <a href="https://dynasti.vital-it.ch/">
        <img src="./assets/img/dynasti.png" width="240" alt="DynaStI Vital-IT Platform Screenshot"/>
      </a>
    </td>
    <td align="left">
      <a href="https://dynasti.vital-it.ch/"><b>DynaStI & PyLSS: Physicochemical Property & Retention Modeling</b></a><br/>
      Predictive physicochemical modeling platform deployed at the Swiss Institute of Bioinformatics (Vital-IT) alongside <a href="https://github.com/gmrandazzo/PyLSS"><b>PyLSS</b></a> (Linear Solvent Strength simulation) for automated structure annotation and biomarker discovery.<br/><br/>
      <a href="https://dynasti.vital-it.ch/">
        <img src="https://img.shields.io/badge/Web_Platform-dynasti.vital--it.ch-007ACC?style=flat-square" />
      </a>
      <a href="https://doi.org/10.3390/metabo9120291">
        <img src="https://img.shields.io/badge/Paper-Metabolites%202019-b31b1b?style=flat-square" />
      </a>
      <a href="https://github.com/gmrandazzo/PyLSS">
        <img src="https://img.shields.io/badge/Code-PyLSS-black?logo=github&style=flat-square" />
      </a>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square" />
    </td>
  </tr>
</table>

---

## Selected Publications

- **libscientific: A Powerful C Library for Multivariate Analysis**  
  *G. M. Randazzo* - *The Journal of Open Source Software (JOSS)*, 8(87), 5420 (2023). [DOI: 10.21105/joss.05420](https://doi.org/10.21105/joss.05420)
- **Steroid identification via deep learning retention time predictions and two-dimensional gas chromatography-high resolution mass spectrometry**  
  *G. M. Randazzo, A. Bileck, A. Danani, B. Vogt, M. Groessl* - *Journal of Chromatography A*, 1612, 460661 (2020). [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0021967319310830) / [DOI: 10.1016/j.chroma.2019.460661](https://doi.org/10.1016/j.chroma.2019.460661)
- **DynaStI: A Dynamic Retention Time Database for Steroidomics**  
  *S. Codesido, G. M. Randazzo, F. Lehmann, et al.* - *Metabolites*, 9(12), 291 (2019). [DOI: 10.3390/metabo9120291](https://doi.org/10.3390/metabo9120291)
- **A Rational Approach for the Identification of Non-Hydroxamate HDAC6-Selective Inhibitors**  
  *L. Goracci, N. Deschamps, G. M. Randazzo, et al.* - *Scientific Reports*, 6, 29086 (2016). [DOI: 10.1038/srep29086](https://doi.org/10.1038/srep29086)
- **Discovery of Novel, Potent, and Specific Cell-Death Inducers in the Jurkat Acute Lymphoblastic Leukemia Cell Line**  
  *E. Carosati, N. van den Hofel, M. Reif, G. M. Randazzo, et al.* - *ChemMedChem*, 10(9), 1541-1554 (2015). [DOI: 10.1002/cmdc.201500222](https://doi.org/10.1002/cmdc.201500222)

*Complete list of 20+ peer-reviewed articles available on [Google Scholar](https://scholar.google.com/citations?user=wVq-c3IAAAAJ&hl=en).*

---

## Education

* **PhD in Chemical Science** | *University of Perugia, Italy* (2010 - 2013)  
  *Quantitative Structure-Property/Retention Relationships, physicochemical modeling, and metabolomics.*
* **Master of Science in Organic Chemistry** | *University of Perugia, Italy* (2008 - 2010)  
  *Computational selection and organic synthesis of biologically active compounds.*
* **Bachelor of Science in Chemistry** | *University of Catania, Italy* (2004 - 2008)  
  *Microwave-assisted organic synthesis of therapeutic candidates.*

---

## Beyond the Lab

I have been writing scientific and cheminformatics software from first principles since 2008, long before modern AI assistants, and today I combine that mathematical and systems foundation with generative and agentic tools to move faster at scale.

At heart, I am a lifelong Linux/Unix enthusiast (Gentoo, Debian, Fedora with KDE Plasma) and open-source builder. Outside of drug discovery, my projects include **[CheapSecurity](https://github.com/gmrandazzo/CheapSecurity)** (self-hosted CCTV for Linux single-board computers, 220+ stars), **[DeepMatrixInversion](https://github.com/gmrandazzo/DeepMatrixInversion)**, **[TOO](https://github.com/gmrandazzo/TOO)** (TensorFlow on Odroid), upstream **[Linux Kernel](https://lore.kernel.org/linux-wireless/20200405220659.45621-1-chunkeey@gmail.com/#r)** patches, and **[Mindguard](https://github.com/asbestomolesto/mindguard)**.

When I am away from a terminal, I am an avid distance runner with a **[1h 14m Half Marathon (21.1 km) personal best](https://apiah.endu.net/events/99979/result/259/diploma)** *(70th of 10,806 overall; 9th of 640 in SM40)*, and I enjoy spending time with my family, playing the French horn, inline skating, and restoring vintage computers.

---

## Contact

Always happy to connect with fellow scientists, founders, and R&D leaders on AI-driven drug discovery, biomolecular simulation, and high-performance cheminformatics.

- **Email**: [gmrandazzo@gmail.com](mailto:gmrandazzo@gmail.com)
- **LinkedIn**: [linkedin.com/in/gmrandazzo](https://www.linkedin.com/in/gmrandazzo/)
- **GitHub**: [github.com/gmrandazzo](https://github.com/gmrandazzo)
- **Google Scholar**: [Giuseppe Marco Randazzo](https://scholar.google.com/citations?user=wVq-c3IAAAAJ&hl=en)
- **Location**: Lugano, Switzerland
