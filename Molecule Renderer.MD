## Molecule Renderer
![Screenshot from image](docs/MoleculeRenderer-screenshot-01.png)
### Purpose - Display a molecule in 3d from different perspectives

### Intro
For this question, you are to complete a program that draws 3D representations of molecules drawing the atoms in a molecule as colored circles on the graphics pane. To help the user see the 3D shape of the molecule, the program can draw the molecule from six different directions.

The program involves Maps, Lists, and Sorting.

### Details

The shape of molecules can be very important for understanding their function, especially for large biological molecules. Using X-ray crystallography and other techniques, chemists or biochemists can identify the structure of a molecule by identifying the (x, y, z) coordinates of each atom in the molecule. However, tables of values are hard to make sense of, and it is better to be able to visualise the molecule by presenting a graphical rendering of the atoms. Because molecules are 3D shapes, is is hard to make sense of them with just one viewpoint – a good visualisation will allow a user to view the molecule from different directions.

The MoleculeRenderer program produces a simple visualisation that draws each atom in a molecule as a coloured circle. To ensure a correct 3D visualisation, the atoms that are further from the viewer are drawn first, and then the atoms that are closer to the viewer, so atoms in front will cover atoms behind. The MoleculeRenderer program also lets the user view the molecule from the front, back, left, right, top, and bottom.

The MoleculeRenderer program reads a specification of the atoms in a molecule and then renders the molecule on the screen, allowing the user to view the molecule from different directions. There are several molecule files including acetone, a small part of the hemoglobin protein, a buckyball (an unusual form of Carbon), and curcumin (a critical component of Turmeric).

