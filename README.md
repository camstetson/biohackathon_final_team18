# Biohackathon Technical Report - Team 18

# Task B and C 
Angelman syndrome (AS) is a rare neurodevelopmental disorder characterized by a severe developmental delay, intellectual disability, and a unique behavioral phenotype. Symptoms of AS generally become apparent when the child is 6-12 months of age, and severity and type of symptoms change with age. The current diagnostic criteria includes developmental delay, movement disorders including gait ataxia, unique behavior including happy demeanor, frequent smiling, hypermotoric behavior, and later seizure onset. The primary organ involved in the expression of Angelman syndrome is the brain. More specifically, studies have demonstrated abnormalities in the cerebral cortex, hippocampus, and the cerebellum.

The primary gene involved in AS is UBE3A that encodes an E3 ubiquitin ligase, which plays a crucial role in protein degradation and synaptic function. UBE3A is first expressed in early embryonic development and continues into adulthood, but there is a shift from biallelic expression to maternal expression in the neurons. High expression of UBE3A is seen in the hippocampus, purkinje neurons, cerebral cortex, and hypothalamus. There are four different genotypes resulting in the expression of AS where the most common is deletion of the mother's copy of UBE3A. The less common genotypes include a mutation in the 15th chromosome inherited from the mother which prevents expression of UBE3A, imprinting defects on human chromosome 15, and the extremely rare case of Paternal Uniparental Disomy, where both copies of UBE3A are silenced.

Current frontline treatments include managing symptoms by controlling seizures, addressing sleep disturbances, and behavioral interventions. There are many clinical trials currently ongoing, with significant studies including gene therapy aimed at either turning on the paternal chromosome’s gene or replacing the maternal gene, and utilizing antisense oligonucleotides to unsilence the paternal gene.

# Task F

**Hypothesis**: Mutations or deletions in the maternally inherited UBE3A gene on chromosome 15 lead to the loss of functional UBE3A protein expression in neurons, resulting in the characteristic clinical features of Angelman syndrome.


**Experimental Design**:

**Title**: “Investigating the Relationship Between UBE3A Gene Mutations and Angelman Syndrome Phenotypes”

**Objective**: To determine if selective inhibition of the maternally inherited UBE3A gene leads to the development of phenotypes of Angelman syndrome. 

**Methods**:
Animal Model Generation:
a) Create a conditional knockout mouse model using the Cre-loxP system (this entails loxP sites flanking a target gene, in this case UBE3A, which directs Cre-mediated recombination).
b) Engineer the mice with loxP sites flanking critical exons of the target UBE3A gene.
c) Cross the mice with a line expressing Cre recombinase under a neuron-specific promoter. 

Experimental Groups:
Group A: WT mice (control)
Group B: Heterozygous maternal UBE3A knockout mice (UBE3A m-/p+)
Group C: Heterozygous paternal UBE3A knockout mice (UBE3A m+/p-)

Molecular Confirmation:
a) Perform genotyping via PCR to confirm the knockout allele is present. 
b) Use a Western blot to verify the absence of the UBE3A protein in the knockout mice neurons. 

Behavioral Assessments:
Conduct behavioral tests in the mice to analyze the Angelman syndrome phenotypes:
a) Motor function: Rotarod test, gait analysis
b) Learning and memory: Morris water maze, stimuli conditioning
c) Social: Three-chamber social interaction test
d) Seizure susceptibility: Electroencephalography (EEG) and induced seizure tests
e) Anxiety: Elevated plus maze
f) Repetitive behaviors: Marble burying test

Neurophysiological Analyses:
a) Conduct electrophysiological recordings in hippocampus sections to analyze synaptic capacity.
b) Conduct EEG recording in vivo to analyze the sleep patterns and seizure activity of the mice. 

Molecular and Cellular Analyses:
a) Analyze morphology and density of dendritic spines in neurons. 
b) Perform RNA-seq to identify genes that are differentially expressed in knockout mice brains. 
c) Identify accumulated UBE3A proteins in neuronal tissues. 

Rescue Experiment:
a) Develop an AAV (adeno-associated virus) vector that expresses WT-UBE3A.
b) Inject this vector into a subset of Group B mice.
c) Repeat the behavior and molecular analysis tests to assess the rescue of the phenotype. 

**Data Analysis**:
Use statistical tests (ANOVA, t-tests) to compare the outcomes of the behavioral, neurophysiological, and molecular analyses between groups. 
Perform a correlation test between UBE3A expression and the phenotype severity. 

Expected results: 
Group B (maternal UBE3A knockout; UBE3A m-/p+) will display Angelman syndrome phenotypes, including motor, cognitive, and social behavior impairments, along with increased seizure susceptibility. 
Group C (paternal UBE3A knockout; UBE3A m+/p-) will not display Angelman syndrome phenotypes, comparable to the WT mice, due to the regular expression of the maternal allele. 
Molecular analyses will reveal UBE3A protein accumulation and changes in the synaptic capacity in Group B, but not Group C. 
The rescue experiment will show improvement in Angelman syndrome phenotypes in Group B mice treated with the AAV vector. 

Controls and Validation:
Control group: WT mice
Heterozygous paternal knockouts are included to confirm the phenotypic effects are due to the loss of maternal UBE3A. 
Rescue experiment to demonstrate reversibility and specificity of UBE3A-related phenotypes.

This experimental design provides an approach to testing the causal relationship between a mutation in UBE3A and Angelman syndrome phenotypes. Combination of genetic mutations, behavioral, neurophysiological, and molecular analyses help establish a strong correlation between the maternal UBE3A allele and Angelman syndrome, potentially supporting further research for therapeutics. 


## Prometheus Prompts
