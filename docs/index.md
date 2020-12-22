# BioExcel documentation space

{{ site.description }}

For further information, see the [https://bioexcel.eu](bioexcel.eu) website.

## BioExcel Knowledge Centre

* [Training resources](https://krc.bioexcel.eu/training)
* [Competencies](https://krc.bioexcel.eu/competencies)
* [BioExcel competency framework](https://competency.ebi.ac.uk/framework/bioexcel/2.0)

<!-- TODO: Integrate this page also into krc -->

## Best Practice Guides

These _best practice guides_ have been developed by BioExcel:

* [Biomolecular QM/MM with CP2K](https://docs.bioexcel.eu/qmmm_bpg/) [[suggest changes](https://github.com/bioexcel/qmmm_bpg)]
* [GROMACS Best Practice Guide](https://docs.bioexcel.eu/gromacs_bpg/)  [[suggest changes](https://github.com/bioexcel/gromacs_bpg)] 
  - incl. [GROMACS Performance Cookbook](https://docs.bioexcel.eu/gromacs_bpg/en/master/cookbook/cookbook.html)
* [Creating workflows with Common Workflow Language](/cwl-best-practice-guide/) [[suggest changes](https://github.com/bioexcel/cwl-best-practice-guide)]
* [HADDOCK best practice guide](https://www.bonvinlab.org/software/bpg/) [[suggest changes](https://github.com/haddocking/haddocking.github.io/tree/master/software/bpg)]
* [How to choose which CWL workflow engine to deploy](/cwl-engine-guide/) [[suggest changes](https://github.com/bioexcel/cwl-engine-guide)]
* [Packaging BioCompute Objects using RO-Crate](https://biocompute-objects.github.io/bco-ro-crate/) [[suggest changes](https://github.com/biocompute-objects/bco-ro-crate/)]

These guides are under development:
* [Primer on workflow packaging and metadata standards](https://docs.google.com/document/d/1XREgfYNi7l4HbdrnXBs7Uv1tMH2AiR435SKjisu4l30/edit#) [[suggest changes](https://docs.google.com/document/d/1XREgfYNi7l4HbdrnXBs7Uv1tMH2AiR435SKjisu4l30/edit)]
* _Alchemical free energy calculations based on non-equilibrium sampling_

In addition to general best practice guidance the guides reflect experience built up over time using the codes and workflow tools in specific application areas. Individual researchers may therefore need to tailor this guidance to find the best approach in light of their particular circumstances and use cases.  

### Contributing to guides

Most of these guides are developed openly as **living documents**, and we **welcome contributions** and suggestions for improvements. 

See _suggest changes_ links above where you can raise an _Issue_ or submit changes as a _Pull Request_ with a [GitHub](https://github.com/) account.

If you prefer, you can instead suggest changes to the guides by posting a question in the [BioExcel forum](https://ask.bioexcel.eu/). Please include the URL to the relevant page.

#### Editing with GitHub

Some of the pages are edited using [Github Pages](https://pages.github.com/), if you are new to GitHub or contributing to Open
Source you may appreciate the [GitHub guides](https://guides.github.com/) like
[Hello World](https://guides.github.com/activities/hello-world/),
[MarkDown](https://guides.github.com/features/mastering-markdown/) and [How to
contribute to open source](https://opensource.guide/how-to-contribute/).

In short:

* Register/log in to <http://github.com/>
* Open corresponding "suggest changes" repository link above.
  - Navigate to the `*.md` or `*.rst` file corresponding to the rendered HTML file. 
  - You may need to go into `docs/` subfolder.
* Click "🖉 Edit" to edit file within GitHub UI. GH will make a _branch_ in a _fork_ repository stored under your own account.
* Add/change text
  - Use the corresponding [MarkDown](https://guides.github.com/features/mastering-markdown/) or [reStructured Text](https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html) syntax
  - If not sure, just use **plain text**.
* Commit, briefly summarize your changes, e.g. _Fixed download link_
  - Commit often so changes are small!
  - For larger edits/reorganization, instead raise an _Issue_ to discuss best way forward
* Raise a _Pull Request_ (PR) to suggest we incorporate changes from your branch.
  - In the PR description, briefly summarize your changes.
  - Respond to comments/email notifications in case we have any questions
* Further unrelated changes? Make a new PR with a new branch.

Guides BPG1 and BPG2 are rendered using [Sphinx](https://www.sphinx-doc.org/en/master/) which uses the format [reStructured Text](https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html), similar to MarkDown.

To update _this_ documentation index page <https://docs.bioexcel.eu/>, edit [index.md](https://github.com/bioexcel/bioexcel.github.io/blob/main/docs/index.md) at <https://github.com/bioexcel/bioexcel.github.io>



### Asking BioExcel

If you have a question not answered by the guides or the code documentation, or you have suggestions for our best pratice guides, 
you may also contact us on the [BioExcel forum](https://ask.bioexcel.eu/).

You can also use the BioExcel forum to suggest changes to the guides.

## Code documentation

The individual [codes](https://bioexcel.eu/software/) and tools developed by, contributed by and used by BioExcel have their own documentation spaces:

* [GROMACS](http://www.gromacs.org/)
  - [GROMACS documentation](http://manual.gromacs.org/) [[suggest changes](https://github.com/gromacs/gromacs/tree/master/docs)]
  - [GROMACS user guide](http://manual.gromacs.org/current/user-guide/index.html)
  - [GROMACS HowTo guides](http://manual.gromacs.org/current/how-to/index.html)
  - [GROMACS reference manual](http://manual.gromacs.org/current/reference-manual/index.html)
  - [GROMACS: Getting good performance from mdrun](http://manual.gromacs.org/current/user-guide/mdrun-performance.html)
  - [GROMACS: From Proteins to Perturbed Hamiltonians: A Suite of Tutorials for the GROMACS-2018 Molecular Simulation Package](https://doi.org/10.33011/livecoms.1.1.5068)
* [HADDOCK](https://www.bonvinlab.org/software/#haddock)
  - [HADDOCK 2.2 Manual](https://www.bonvinlab.org/software/haddock2.2/manual/)
  - [HADDOCK 2.4 Manual](https://www.bonvinlab.org/software/haddock2.4/manual/)
* [PDB tools](https://www.bonvinlab.org/pdb-tools/)
* [PMX](http://pmx.mpibpc.mpg.de/)
  - [PMX instructions](http://pmx.mpibpc.mpg.de/instructions.html)
  - [PMX tutorials](http://pmx.mpibpc.mpg.de/tutorial.html)
* [CP2K](https://www.cp2k.org/)
  - [CP2K manual index](https://manual.cp2k.org/)  
  - [CP2k manual (7.1)](https://manual.cp2k.org/cp2k-7_1-branch/index.html)
  - [CP2k manual (development version)](https://manual.cp2k.org/trunk/index.html)
  - [CP2k Howto: QMMM for biochemical systems](https://www.cp2k.org/howto:biochem_qmmm)
* [CPMD](https://www.cpmd.org/)
  - [CPMD documentation](https://www.cpmd.org/wordpress/index.php/documentation/)
  - [CPMD manual (PDF)](https://www.cpmd.org/wordpress/CPMD/getFile.php?file=manual.pdf)
* [BioExcel Building Blocks (BioBB)](http://mmb.irbbarcelona.org/biobb/) 
  - [BioBB tutorials](http://mmb.irbbarcelona.org/biobb/availability/tutorials)
  - [BioBB workflows](http://mmb.irbbarcelona.org/biobb/workflows) (incl workflow tutorials)
  - [BioBB source/docs](http://mmb.irbbarcelona.org/biobb/availability/source) per building block
* [Common Workflow Language](https://www.commonwl.org/)
  - [Common Workflow Language User Guide](https://www.commonwl.org/user_guide/) [[suggest changes](https://github.com/common-workflow-language/user_guide/)]
  - [Common Workflow Language User Guide: Recommended Practices](https://www.commonwl.org/user_guide/rec-practices/)
  - [Dockstore: CWL Best Practices](https://docs.dockstore.org/en/develop/advanced-topics/best-practices/best-practices.html)
  - [Arvados: Best Practices for writing CWL](https://doc.arvados.org/v1.4/user/cwl/cwl-style.html)
  - [CWL 1.2 specification](https://www.commonwl.org/v1.2/)
  - [Common Workflow Language with BioExcel Building Blocks](https://mmb.irbbarcelona.org/biobb/availability/tutorials/cwl)
  
  
## White-papers and related publications

These publications and white-papers by BioExcel authors include aspects of best-practice guidance:

* Recommendations for BioExcel Training Programme (2016) <https://doi.org/10.5281/zenodo.263926>
* Competency framework, mapping to current training & initial training plan (2016) <https://doi.org/doi:10.5281/zenodo.264231>
* I'll take that to go: Big data bags and minimal identifiers for exchange of large, complex datasets <https://doi.org/10.1109/BigData.2016.7840618> [preprint](https://www.research.manchester.ac.uk/portal/files/45989205/bagminid.pdf)
* Robust Cross-Platform Workflows: How Technical and Scientific Communities Collaborate to Develop, Test and Share Best Practices for Data Analysis (2017) <https://doi.org/10.1007/s41019-017-0050-4>
* Identifiers for the 21st century: How to design, provision, and reuse persistent identifiers to maximize utility and impact of life science data (2017) <https://doi.org/10.1371/journal.pbio.2001414>
* Sharing interoperable workflow provenance: A review of best practices and their practical application in CWLProv (2019): <https://doi.org/10.1093/gigascience/giz095>
* Whitepaper on Scientific Software Development (2018) <https://doi.org/10.5281/zenodo.1194634>
* Defining distance restraints in HADDOCK (2018) <https://doi.org/10.1038/s41596-018-0017-6>
* Enabling precision medicine via standard communication of HTS provenance, analysis, and results <https://doi.org/10.1371/journal.pbio.3000099>
* An enhanced-sampling MD-based protocol for molecular docking (2018): <https://doi.org/10.1101/434092> (see also <https://doi.org/1.1021/acs.jcim.8b00730>)
* The role of metadata in reproducible computational research (2020): <https://arxiv.org/abs/2006.08589>
* BioExcel Building Blocks, a software library for interoperable biomolecular simulation workflows <https://doi.org/10.1038/s41597-019-0177-4>

See also [BioExcel publications](https://bioexcel.eu/category/publications/) and the individual [software project pages](https://bioexcel.eu/software/) for a complete list of publications.

## BioExcel website

The [bioexcel.eu](https://bioexcel.eu/) website includes several sections relevant for documentation and knowledge dissemination:

- [Software by BioExcel](https://bioexcel.eu/software/)
- [Publications by BioExcel](https://bioexcel.eu/category/publications/)
- [Webinars by BioExcel](https://bioexcel.eu/category/webinar/)
- [Training by BioExcel](https://bioexcel.eu/services/training/)
- [BioExcel Knowledge Resource Centre](https://krc.bioexcel.eu/)
- [ask.bioexcel.eu](https://ask.bioexcel.eu/) forum for HADDOCK, DISVIS, POWERFIT, PRODIGY, SPOTON, PDB-tools, pmx, MDWeb, BioBB, Workflows, QM/MM, etc.
- [Gromacs user forum](https://gromacs.bioexcel.eu/)
