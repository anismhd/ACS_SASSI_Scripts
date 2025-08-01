# Pre and Post Processing for ACS SASSI
Prepared by : Anis M Vengassseri

## Introduction
This is a brief note decribing the process of preparing a model for seismic analysis of surface mounted and embeded structure in ACS SASSI.
This document provides step by step guide in preparing a model, excecute a run and post processing of results.
Please note that this document is not a suppliment for ACS SASSI manual. The user is strongly advised to read following documents to get a theoretical knowledge on SASSI and ACS SASSI.

1. Wolf, John P. "Dynamic soil-structure interaction." (1985)
2. Theoretical Manual for SASSI2000
3. Phd Thesis associated with SASSI Develepment

## Model Preparations
In it is ideal and practiced to develop seismic analysis model for ACS SASSI in other FEA softwares and convert to SASSI model.
In this document transfer of model from ABAQUS to ACS SASSI are described in detail.
While prepariing the model in ABAQUS for ACS SASSI, please note that, no constrain equations or springs are not allowed as part of the model. 
The model needs to in in single part and consists of following types of elements only.

1. All beam and truss elements
2. All types of shell element including triangulal
3. All types of solid element excluding tetrahedron elements

### Step 1 : Prepare the model in ABAQUS

