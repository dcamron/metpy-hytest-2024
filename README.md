<div align="center">

<a href="https://www.unidata.ucar.edu/">
<img src="logos/NSF-Unidata_lockup_horizontal_2023.png" width=65% alt="NSF & Unidata logos">
</a>

</div>

# MetPy for Analysis and Visualization of Weather Data in Python
*NSF Unidata, USGS HyTEST, May 2024*

### :keyboard: Getting set up
For this workshop, we have two separate ways you can live code, work ahead, and follow along.
If you've registered to attend, you will be given access to Unidata's Science Gateway to do your work on NSF's Jetstream Cloud.
If you prefer or require doing the work on your own computer, you are welcome to do so as well!

#### :cloud: Using [Science Gateway](https://science-gateway.unidata.ucar.edu/)
If you've registered for this workshop, you can do all of this work on our very own _gateway_ to the NSF Jetstream Cloud!
After you are given access, you can sign in to Science Gateway with your provided temporary username and password at [pyaos-workshop.unidata.ucar.edu](https://pyaos-workshop.unidata.ucar.edu).

When you first sign in, it may take a few seconds for your personal workspace to populate and your coding environment to be fully set up.
From here you will discover a Jupyter Lab interface pre-populated with these materials and a few tools to enable you to update the materials if needed.
Once you are given access, you will be able to download materials and notebooks from your workspace if you'd like, up until a brief time after the end of the workshop.

#### :computer: Using your computer
**Note that we at Unidata are not able to plan for any hardware limitations your personal computer might have, and we will not have time during the workshop to diagnose issues on personal computers.**
Please plan to use Science Gateway if this is a concern for you.
We will be using and supporting [Conda](https://docs.conda.io/en/latest/) for installing and managing a Python environment from your computer's command line.
Please have this environment prepared ahead of time if you'll be using your own computer.

> 1. [Install Miniconda](https://docs.conda.io/en/latest/miniconda.html#installing) if you don't already have command-line access to `conda`.
> 1. Get a copy of this code!
> You have a few options from the green button above,  
> a. `git clone https://github.com/dcamron/metpy-hytest-2024.git` from your command line, within some directory on your computer.
> [Install git](https://github.com/git-guides/install-git) if necessary.
> If you're comfortable with `git`, we recommend this approach as it will let you keep this code regularly up to date.  
> b. [`Open with GitHub Desktop`](https://desktop.github.com/) if you have and prefer this graphically-focused software.  
> c. [`Download ZIP`]((https://github.com/dcamron/metpy-hytest-2024/releases/refs/heads/main.zip)) if you prefer to get a single snapshot of the code right here and now.
> 1. Wherever you have this code saved, set up your Python environment with `conda env create -f environment.yml` from your command line.  
> 1. Give this some time.
> Once it's done, activate this new environment with `conda activate metpy-hytest-2024`.
> Always do this before starting on work for this workshop!
> 1. Launch Jupyter and get to coding with `jupyter lab`.
> Don't forget to activate your environment first!

### :speech_balloon: Acknowledgements
The JupyterHub for this workshop is part of the [U.S. National Science Foundation](https://www.nsf.gov/) (NSF) funded [Unidata Science Gateway](https://doi.org/10.5065/688s-2w73) (doi:10.5065/688s-2w73) (under NSF Award [1901712](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1901712)).
We thank Andrea Zonca (San Diego Supercomputing Center), Jeremy Fischer (Indiana University), the NSF funded [Jetstream](https://dx.doi.org/10.1145/2792745.2792774) team, and the NSF funded XSEDE [Extended Collaborative Support Service](https://doi.org/10.1007/978-3-319-32243-8_1) (ECSS) program for assistance with this JupyterHub.
