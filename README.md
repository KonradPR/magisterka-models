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

Train time for Transformer 10 epochs:
non sub Elapsed time: 951.6299428939819 seconds
sub Elapsed time: 731.0645015239716 seconds

Train time for svm:
non sub Elapsed time:  7288.655417919159 seconds
sub Elapsed time:  2652.528799057007 seconds

211600
180000


Model sub predictions: 21.249239444732666 seconds
Suma trenowalnych parametrów: 192545
Suma trenowalnych parametrów sub: 160161
Running predictions for transformer
Model predictions: 22.944324016571045 seconds
Model sub predictions: 22.16677451133728 seconds
Suma trenowalnych parametrów: 71777
Suma trenowalnych parametrów sub: 67681
Running predictions for lstm
Model predictions: 49.38928747177124 seconds
Model sub predictions: 32.75259304046631 seconds
Suma trenowalnych parametrów: 620321
Suma trenowalnych parametrów sub: 604321
Running predictions for autoencoder
Model predictions: 22.603391885757446 seconds
Model sub predictions: 21.303611516952515 seconds
Suma trenowalnych parametrów: 148288
Suma trenowalnych parametrów sub: 37280
Running predictions for svm
Model predictions: 2187.1206471920013 seconds
Model sub predictions: 1154.9324202537537 seconds

117899