## Who Am I ?
I am a Computational Chemist with over 8 years of research experience in Cheminformatics, Machine Learning, DFT, and Molecular Dynamics, backed by a Ph.D. in Chemistry. My analytical mindset leads me to explore various perspectives, igniting my curiosity and creativity when it comes to problem-solving. Beyond work, I am an avid traveler, and a photpgrapher embracing the joy and adventure that come with exploring new horizons.



### Education
- Ph.D., Chemistry | University of Connecticut, Storrs, CT (2019)
- BSc., Chemistry | University of Peradeniya, Sri Lanka (2010)

### Work Experience
#### Postdoctoral Research Associate | Ames National Laboratory, Ames, IA (2022 - present)
- Organized and curated large datasets, selected relevant features using python, scikitlearn and trained and validated neural network models using Chemprop software to predict binding affinities of metal-ligand complexes with 86% accuracy
- Used chemometric techniques such as PCA and partial least squares (PLS) multivariate regression to predict metal-ligand binding affinities using spectroscopic data

#### Postdoctoral Research Associate | University of Connecticut, Storrs, CT (2019 - 2022)
- Collaborated with a team of multidisciplinary researchers to build a computational model via molecular simulations and cheminformatics techniques to facilitate the identification of unknown metabolites in biofluids using Mass and IR spectral data which resulted in the correct identification of 59%


#### Research Assistant | University of Connecticut, Storrs, CT (2012 - 2018)
- Collaborated with multidisciplinary researchers to design flavin-C60 (FC60) molecule. Calculated its conformational and electronic space and demonstrated the charge transfer characteristics of FC60 self-assembly around single-walled carbon nanotubes (SWNTs), which has profound importance in nanostructured optoelectronic devices
- Deciphered the preferential C60 localization around flavin-wrapped nanotubes via molecular dynamics and DFT calculations, demonstrating site-specific molecular recognition of flavin helices
- Characterized the XRD pattern of SWNT nucleated FMN (flavin mononucleotide) crystals and simulated its crystal packing. Interpreted the underlying notion of selective flavin assemblies on specific chiral nanotubes 
- Validated the stability and organizational pattern of different flavin derivatives around SWNTs through spectroscopic techniques and computational modeling 
- Developed new methodology to control porosity in monolayer surfactant coatings around carbon nanotubes 
- Mentored undergraduate students and high-school students in their research projects, which resulted in poster presentations at research symposiums



### Projects

![Chemistry Tools](/assets/images/chem_tools.jpg)
#### ChemTools: Python tools for Analysis of Chemical compounds
Chemtools is a set of python scripts intended to help with calculations related to chemical structures such as descriptor calculation, sub structure searching, functional group modifications etc. using Rdkit, numpy and pandas libraries. <a href="url">https://github.com/Erandi44/Chemistry_Tools</a>

#### Novel AI Driven Methods for Improved Metal Separations
The determination of metal-ligand stability constants, represented as log K values, is a critical aspect in various fields such as drug design, chelation therapy, catalysis, MRI imaging, and solvent extraction of metal ions. Although ab-initio calculations are typically used in predicting these values, the associated computational cost and reduced accuracy render them impractical. As a result, data-driven approaches such as machine-learning (ML) have been used and show great promise for estimating metal-ligand log K values. To address this the directed message passing neural network (D-MPNN) machine learning in Chemprop software was employed in predicting logK1 binding affinities for all metal ions in the periodic table with different types of molecular ligands. The ML models were trained on data extracted from the IUPAC Stability Constants Database (SC-database), which contains metal-complex stability constants and related information published in scientific literature. Data preparation and cleaning was done with the use of different python libraries such as numpy, pandas and RDKit. <a href="url">https://github.com/Critical-Materials-Institute/LOGKPREDICT</a>

### Chemical Structutre identification by Experimental and Computational IR and Mass Spectra
The inability to identify the structures of most metabolites detected in environmental or biological samples limits the utility of nontargeted metabolomics. The most widely used analytical approaches combine mass spectrometry and machine learning methods to rank candidate structures contained in large chemical databases. Given the large chemical space typically searched, the use of additional orthogonal data may improve the identification rates and reliability.Here, we present results of combining experimental and computational mass and IR spectral data for high-throughput nontargeted chemical structure identification. Experimental MS/MS and gas-phase IR data for 148 test compounds were obtained from NIST. Candidate structures for each of the test compounds were obtained from PubChem (mean = 4444 candidate structures per test compound). Our workflow used CSI:FingerID to initially score and rank the  candidate structures. The top 1000 ranked candidates were subsequently used for IR spectra prediction, scoring, and ranking using density functional theory (DFT-IR). Final ranking of the candidates was based on a composite score calculated as the average of the CSI:FingerID and DFT-IR rankings. This approach resulted in the correct identification of 88 of the 148 test compounds (59%). 129 of the 148 test compounds (87%) were ranked within the top 20 candidates. These identification rates are the highest yet reported when candidate structures are used from PubChem. Combining experimental and computational MS/MS and IR spectral data is a potentially powerful option for prioritizing candidates for final structure verification.
publication: <a href="url">https://doi.org/10.1021/acs.analchem.3c00937</a>
publication: <a href="url">https://doi.org/10.1021/acs.analchem.1c02244</a>





### Publications
- Karunaratne E; Hill D W, Dührkopb K; Böckerb S; Grant D F, Combining experimental with computational infrared and mass spectra for high throughput non-targeted chemical structure identification, Anal Chem 95, 32, 11901–11907 (2023) 
<a href="url">https://doi.org/10.1021/acs.analchem.3c00937</a>


- Karunaratne E; Hill D W, Pracht P; Gascón J A; Grimme S; Grant D F, High-Throughput Non-targeted Chemical Structure Identification Using Gas-Phase Infrared Spectroscopy. Anal Chem 93, 10688-10696 (2021) 
<a href="url">https://doi.org/10.1021/acs.analchem.1c02244</a>


- Mollahosseini M; Karunaratne E; Gibson G N; Gascón J A; Papadimitrakopoulos F, Fullerene-Assisted Photoinduced Charge Transfer of Single-Walled Carbon Nanotubes through a Flavin Helix. J. Am. Chem. Soc 138, 5904-5915 (2016)
<a href="url">https://doi.org/10.1021/jacs.5b13496</a>

