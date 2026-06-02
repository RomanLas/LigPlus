# LigPlus
LigPlot<SUP>+</SUP> is a Java application for the automatic generation and onscreen editing of 2D ligand-protein interaction diagrams for a given PDB file.

It is a Java application that allows on-screen editing of the plots via mouse click-and-drag operations.

Additionally, the program includes several major enhancements over the old version:

<OL>
<LI><B>Superposition of related diagrams</B>. When two or more ligand-protein complexes are sufficiently similar, LigPlot<SUP>+</SUP> can automatically display their interaction diagrams either superposed or side by side. Any conserved interactions are highlighted.

<LI><B>Improved DIMPLOT program</B>. The LigPlot+ suite also now includes an update of the original DIMPLOT program for plotting protein-protein or domain-domain interactions. Users can flexibly select the interface of interest and DIMPLOT will then generate a diagram showing the residue-residue interactions across the interface. To assist in interpretation, the residues in one of the interfaces can be optionally displayed in sequence order. Note that the DIMPLOT module does not yet allow multiple plots of related interfaces.

<LI><B>Links to PyMOL and RasMol</B>. The 3D representation of any LIGPLOT diagram can be viewed in either PyMOL or RasMol with all the interactions indicated.
</OL>

To install, download the following files:

<UL>
  <LI><B>LigPlus.zip</B> - Program files
  <LI><B>docs.tar.gz</B> - documentation
</UL>

Extract all the files from <B>docs.tar.gz</B> and then follow the instructions in <B>install.html</B> (from the extracted <B>docs.tar.gz</B> file).



<H4>Reference</H4>

Laskowski R A, Swindells M B (2011). LigPlot+: multiple ligand-protein interaction diagrams for drug discovery. <I>J. Chem. Inf. Model.</I>, <B>51</B>, 2778-2786. [PubMed id: 21919503]

