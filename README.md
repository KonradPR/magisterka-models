# magisterka-models


to run jupyter with gpu form wsl:
 //Those were used when installing and I am not usre if must be run again:
 echo 'export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:$CONDA_PREFIX/lib/:$CUDNN_PATH/lib' >> $CONDA_PREFIX/etc/conda/activate.d/env_vars.sh
source $CONDA_PREFIX/etc/conda/activate.d/env_vars.sh

conda activate tf
jupyter notebook --no-browser