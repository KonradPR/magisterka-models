# magisterka-models


to run jupyter with gpu form wsl:
 //Those were used when installing and I am not usre if must be run again:
 echo 'export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:$CONDA_PREFIX/lib/:$CUDNN_PATH/lib' >> $CONDA_PREFIX/etc/conda/activate.d/env_vars.sh
source $CONDA_PREFIX/etc/conda/activate.d/env_vars.sh

 export LD_LIBRARY_PATH=/usr/lib/wsl/lib:$LD_LIBRARY_PATH

conda activate tf
jupyter notebook --no-browser


Train time for CNN 10 epochs:
non sub Elapsed time: 487.69908261299133 seconds
sub Elapsed time: 461.02721667289734

train time for LSTM 10 epochs:
non sub Elapsed time:  2553.0696408748627 seconds
sub Elapsed time:  1634.3169915676117 seconds

Train time for Autoencoder 10 epochs:
non sub Elapsed time:  402.99103808403015 seconds
sub Elapsed time:  379.51816868782043 seconds