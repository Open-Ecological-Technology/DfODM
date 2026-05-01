# DfODM

Design for Open Distributed Manufacturing

A methodology for reproducible, community-centered hardware design

## PREFACE

Traditional Design for Manufacturability (DFM) is optimized for centralized, capital-intensive production environments. DfODM is a structural inversion that optimizes for open publication and community reproduction. 

The goal is hardware that is not merely open-source in license, but genuinely reproducible -- by individuals, collectives, and communities operating outside centralized industrial infrastructure. 

## CORE PRINCIPLES

1. Design for Common Tools
   - Defines minimum tools required AKA capability tiers
   - Prefers geometries and tolerances achievable by widely available fabrication methods
3. Documentation is First-Class Artifact
   - Knowledge to required to reproduce it is as importan as product itself
   - Meets OSHWA Certification
   - We will achieve this using tools produced by the DOF initiative (WIP). 
4. Forkability over Optimization
   - Prefers modular assemblies over monolithic
   - Defines clear component interfaces
   - Avoids hidden dependencies
   - Structure design to allow for partial reproduction 
5. Local Materials over Imports
   - Identifies functional properties over brand names
   - Document alternatives
   - Where possible, ddesign for materials produced close to point of use (reclaimed materials, on-site extraction, fermentation, byproducts, etc.)
   - Flag single-source or import-dependent materials explicitly
6. Defines Skill Competencies
   - Document required competencies and assess where skills are learnable
   - Prefer designs where skills can build incrementally
7. Licensed to commons
   - Uses a license that doesn't restrict use
8. Considers Repairability and End-of-Life
   - Design for disassembly - fasteners over adhesives, accessible components over sealed
   - Documents maintenance procedures
   - Identfies consumable or wear components
   - Prioritizes recyclability or reclaimability of parts
