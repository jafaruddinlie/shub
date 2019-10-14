## Installation README

* Website:  
            https://github.com/pinellolab/haystack_bio

* Source:   
            https://github.com/pinellolab/haystack_bio

* Licence:  
            GNU AFFERO License - https://github.com/pinellolab/haystack_bio/blob/master/LICENSE

* Run:      
            singularity exec -B $HOME/genomes:/opt/miniconda2/lib/python2.7/site-packages/haystack/haystack_data/genomes imageFileName.sif haystack_run_test

* Notes:
            Haystack Bio downloads the genome files into $PYTHONHOME/haystack/haystack_data/genomes. Since this folder is read-only in the container, it needs to be mounted to a folder with read-write permision. The example in the Run section binds the genomes folder under user home folder to $PYTHONHOME/haystack/haystack_data/genomes.
