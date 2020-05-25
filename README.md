# UDK_library

Hi, in this repository we collect the code to turn UDK's database drop into
vectors and visualize them. This is the readme, Johannes you can put everything
in here what you think is relevant. A couple of suggestions

## Project description


Today's research practices can no longer be reconciled with the representative modes of existing libraries. Colloborative fields connect formerly institutionally and epistemologically separated scientific areas more and more seamlessly. Even if the operational success of scientific disciplines point to the scientific and technical upheavals of modernity, transdisciplinary ways of thinking  in scientific production demonstrate the departure from disciplinary-hierarchical forms of order of knowledge. However, this dynamic emergence of new connections and fields of knowledge can no longer be countered by common means of library classification.
The aim is therefore to propose an alternative variant for structuring / organizing knowledge for the Volkswagen University Library. In a first step a homogeneous dataset of the library's entities (publications containing an abstract) are after cleaning the data analysed by a NLP-algorithm (Doc2Vec). After reducing the dimensionality of the result the aim is to experiment with visualizing the data.  

## Code usage

to be updated when there is some code to use

## Organization

You can create issues to keep track of your to do's. See right side of 
repository.

## Structure

The repository will contain the following folder sturcture
*  data: this folder contains all kind of data *.csv, *.pkl, *....
*  src: contains the source code, probably only python
*  util: contains code that can be reused, e.g. filtering functions with regex
*  misc: in case there is something else to save

The top layer may contain additional bash scripts that allow us to chain 
together the different python scripts.

## Get the code

1.  Install [Git](https://git-scm.com/downloads) on your computer
2.  Open your command line (windows + R, type "cmd", enter)
3.  Navigate to the place where you want to save the repository 
(`cd path/to/whereIwant/toPutTheRepository`, enter)
4.  type `git clone https://gitlab.lrz.de/ga37gap/udk_library.git`

## Contributing

For the project, we will have two protected Git branches:
*  `master`: only the final program which is fully working
*  `develop`: here we will collect intermediate stages and slowly build the full 
software, also fully working but not containting all the functionalities

Protected means that you cannot directly commit to this brach. You will have to
create a third brach on which you develop a certain feature. If you want to 
develop a visualization for TSNE data, call the branch `develop_tsne_viz.` 
Generally, use the naming convention `develop_feature`.
If you have successfully developed a certain feature, you can send a merge 
request, e.g. request that the code is merged into the development branch.
Merge request is only accepted when everything works properls

## Styleguide

For python programming, we always follow the 
[PEP8 styleguide](https://www.python.org/dev/peps/pep-0008/).