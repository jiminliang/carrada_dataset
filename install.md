# Re-implement CARRADA

conda create -n Carrada pip python=3.8

conda activate Carrada

conda install -c menpo opencv

pip install filterpy==1.4.5 matplotlib==3.1.2 numba==0.46.0 numpy==1.17.4 pandas==0.25.3 Pillow==6.2.1 pytest==5.3.1 scikit-image==0.16.2 scikit-learn==0.22 scipy==1.3.3 xmltodict==0.12.0 llvmlite==0.32.1 jupyter

pip install torch-1.10.1+cu113-cp38-cp38-linux_x86_64.whl 

pip install torchvision-0.11.2+cu113-cp38-cp38-linux_x86_64.whl 

cd carrada_dataset/

pip install -e .