srun-1_dgx

cd /global/D1/homes/sushant/Assignments/AI_9560

conda activate ai_assignment_oslomet
jupyter lab --no-browser --ip 0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --collaborative


echo $CUDA_VISIBLE_DEVICES
export CUDA_VISIBLE_DEVICES=13
