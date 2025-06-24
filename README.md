# GRS workshop: Modelling spiking neural networks
This repository provides all code and pre-trained BRIAN networks for the workshop "Modelling the effect of inhibition on synchronicity and regularity in spiking network" and "De-correlating activity via inhibitory plasticity during memory recall". The second Jupyter notebook *Background knowledge about simulation-based network neuroscience* is a complementary notebook explaining the Euler Method and giving a bit of background knowledge about the problem of complexity in network models. 

The runtime of the plastic networks' training can take up to 90 minutes. So, we'd like to suggest opting in to load the network states provided in */stored_networks*.

You can execute the code in two different ways: 

- Run the Jupyter notebook as provided here
- Run the code in Collab

Run the Jupyter notebook as provided in the Repo
-
The notebook was written using the following packages(version): 

- python (3.10.12)
- jupyter (IPython 8.10.0, ipykernel 6.21.2, ipywidgets 8.0.4)
- numpy (1.23.5)
- scipy (1.10.1)
- matplotlib (3.8.4)
- brian2 (2.5.1)
- brian2tools (0.3)

Using Google Collab
-
The notebooks can be accessed using the following links: 

*Background knowledge about simulation-based network neuroscience*
https://colab.research.google.com/drive/1bLCmvkFGSgaTFICeKT1YhNuamhT0eEeo?usp=sharing

*Spiking EI Networks*
https://colab.research.google.com/drive/1kxLGdxPe02DVZ11LYnN1wqEvVjEMhpwF?usp=sharing

Before running the notebook, you need to upload the three files in *\stored_networks* **network_after_500s**, **trained_network** and **untrained_network** to the runspace of the collab. Select the *Files* tap of the lefthand-side menu. Select to upload files and select the three network state files.
