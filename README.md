# SAGE: An AI Co-pilot for ETABS (A Research Preview)

This repository contains a demonstration of SAGE (Structural Analysis Generation Engine), a novel AI co-pilot designed to automate structural engineering workflows in ETABS through natural language.

This tool is the implementation of a framework developed as part of an ongoing research project at the Stevens Institute of Technology. The core innovation is a multi-agent system grounded by a curated Knowledge Graph, which enables the reliable translation of engineering commands into executable, error-free API code, solving the critical problem of LLM hallucination in specialized domains.

## Live Demonstration

The following animation shows the end-to-end workflow of the co-pilot integrated directly into Visual Studio Code. The process demonstrates a user initiating a task with a natural language command, the framework generating factually-grounded code, and the final script being executed to retrieve results from ETABS.

![ETABS Co-pilot Demo](etabs-demo.gif)
*Note: Replace `etabs-demo.gif` with the exact filename you uploaded.*

## Core Features

-   **Natural Language to Code:** Translates plain English commands into executable Python scripts for the ETABS API.
-   **Knowledge Graph Grounding:** Utilizes a curated Knowledge Graph to ensure the generated code is accurate and free of hallucinations.
-   **IDE Integration:** Works directly within VS Code for a seamless and professional user experience.
-   **Synergistic Workflow:** Generates "just-in-time" context that enhances the capabilities of general-purpose AI assistants like GitHub Copilot for code refinement.

## Research Context

This work is part of a forthcoming research paper to be submitted to the journal *Automation in Construction*.

**Authors:** Jinxin Chen, Yi Bao
**Institution:** Department of Civil, Environmental and Ocean Engineering, Stevens Institute of Technology, Hoboken, NJ
**Contact:** yi.bao@stevens.edu
