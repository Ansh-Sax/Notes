# Notes
Notes and Writing

Each note / writing corresponds to a separate directory in this repository which will hopefully contain all assets related to the pdf (like latex document). The pdf is then pointed to via the Blog tab on the academic website -- for more on this read the README document in the Ansh-Sax.github.io repository.

1. The convention is for all assets to have the same name (not the file type, of course!) in a given directory. Since we'll be pointing to pdfs which will be hosted via jsDelivr, it is safer if the pdf name doesn't include crazy characters like "-", "'", or " ".
2. The convention extends to the name of the directory itself. Therefore the directory name itself should be quite simple (using underscores instead of blank spaces). For example, YM_Learning_Seminar_SSZ_Part_II.
3. The whole point of this repository is to reduce clutter in the Ansh-Sax.github.io repository so that it only needs to host the website itself (and not the resources like pdfs in the Blog tab). This is helpful also because this way we get to keep all the associated assets of each document together, which woudl have been unnecessary in the other repository. This repository is not published via GitHub pages. So, we get to manage all that goes on the website through a single repository. This is to ensure modularity. To read more about this see the README document in the Ansh-Sax.github.io repository.
4. The repository is available locally on my personal computer(s) via GitHub and editable there. Together with how the Blog tab in Ansh-Sax.github.io is setup, this makes it so that whatever changes I make locally and commit get reflected in the pdf available on the website directly!
5. The latex document on vscode is built using latexmk. This is important. 
