## Automatic Page Turing with Sheet Music Images

This repository contains the corresponding code for our extended abstract

>[Henkel F.](https://www.jku.at/en/institute-of-computational-perception/about-us/people/florian-henkel/),
>[Schwaiger S.](https://github.com/SchwaigerStephanie)  and 
>[Widmer G.](https://www.jku.at/en/institute-of-computational-perception/about-us/people/gerhard-widmer/) <br>
"[Fully Automatic Page Turning on Real Scores]()".<br>
*In Extended Abstracts for the Late-Breaking Demo Session of the 22nd International Society for Music Information Retrieval Conference*, 2021

### Videos
In the folder [`videos`](https://github.com/fhenkel/page_turner/tree/master/videos) 
you will find two pieces from the test set, where our best performing model follows an incoming musical performance.

## Getting Started
If you want to try our code, please follow the instructions below.

### Setup and Requirements

First, clone the project from GitHub:

`git clone https://github.com/fhenkel/page_turner.git`

Move to the cloned folder:

`cd page_turner`

In the cloned folder you will find an anaconda environment file which you should install using the following command:

`conda env create -f environment.yml`

This will also install the score following system from `https://github.com/CPJKU/cyolo_score_following`

Activate the environment:

`conda activate page_turner`

Finally, install the project in the activated environment:

`python setup.py develop --user`

 ## Acknowledgements

We would like to thank Jan Hajič Jr. and 
Carlos Eduardo Cancino Chacón for performing and recording the test pieces for us.

This project has received funding from the European Research Council (ERC) 
under the European Union's Horizon 2020 research and innovation program
(grant agreement number 670035, project "Con Espressione"). 

<img src="https://erc.europa.eu/sites/default/files/LOGO_ERC-FLAG_EU_.jpg" width="35%" height="35%">