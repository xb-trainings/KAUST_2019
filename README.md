# KAUST_2019

<br>
<br>



<!--  -->	
## Running Python notebooks on the cloud 
<br>

&nbsp;&nbsp;&nbsp; [click here]


[Click here]: https://mybinder.org/v2/gh/xb-trainings/KAUST_2019/master



<br>
<br>
<br>
<br>

## Running Python notebooks on your computer

### Installation
   ```sh
   # Conda installation
   curl -o ~/miniconda.sh -O https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh # Linux
   curl -o ~/miniconda.sh -O https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh # OSX
   chmod +x ~/miniconda.sh
   ./miniconda.sh
   source ~/.bashrc
   #install https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe # Windows

   # Clone GitHub repo
   git clone https://github.com/xb-trainings/KAUST_2019.git
   cd KAUST_2019

   # Install python libraries
   conda env create -f environment.yml
   source activate deeplearn_course

   # Run the notebooks
   jupyter notebook
   ```
<br>
