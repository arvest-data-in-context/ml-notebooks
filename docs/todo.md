Windows version needs something like this ?

!{sys.executable} -m pip install -q --disable-pip-version-check git+https://github.com/arvest-data-in-context/arvest-api.git > /dev/null 2>&1

!pip cache purge > /dev/null 2>&1 # Purge pip's cache so that everything installs correctly.
!pip uninstall -y gcu > /dev/null 2>&1 # Uninstall gcu if it was previously installed. 


!pip cache purge > /dev/null 2>&1 # Purge pip's cache so that everything installs correctly.
!pip uninstall -y gcu > /dev/null 2>&1 # Uninstall gcu if it was previously installed.
!pip install -q git+https://github.com/arvest-data-in-context/gcu > /dev/null 2>&1 # Install the gcu package.
!conda install -y -c conda-forge ffmpeg > /dev/null 2>&1 # Install ffmpeg for file conversion. TODO: check this is necessary for this notebook.
!pip install -q git+https://github.com/iiif-prezi/iiif-prezi3.git # Install the iiif-prezi3 package.