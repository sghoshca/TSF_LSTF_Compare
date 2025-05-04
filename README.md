# TSF_LSTF_Compare
Time series forecasting especially in LSTF compare，include Informer, Autoformer, Reformer, Pyraformer, FEDformer, Transformer, MTGNN, LSTNet, Graph WaveNet
Waiting for updates. Please looking forward to

usage: run.py [-h] --is_training IS_TRAINING --model_id MODEL_ID --model MODEL --data DATA
              [--root_path ROOT_PATH] [--data_path DATA_PATH] [--features FEATURES] [--target TARGET]
              [--freq FREQ] [--checkpoints CHECKPOINTS] [--seq_len SEQ_LEN] [--label_len LABEL_LEN]
              [--pred_len PRED_LEN] [--bucket_size BUCKET_SIZE] [--n_hashes N_HASHES] [--enc_in ENC_IN]
              [--dec_in DEC_IN] [--c_out C_OUT] [--d_model D_MODEL] [--n_heads N_HEADS] [--e_layers E_LAYERS]      
              [--d_layers D_LAYERS] [--d_ff D_FF] [--moving_avg MOVING_AVG] [--factor FACTOR] [--distil]
              [--dropout DROPOUT] [--embed EMBED] [--activation ACTIVATION] [--output_attention] [--do_predict]    
              [--clip CLIP] [--hidCNN HIDCNN] [--hidRNN HIDRNN] [--CNN_kernel CNN_KERNEL]
              [--highway_window HIGHWAY_WINDOW] [--skip SKIP] [--hidSkip HIDSKIP] [--output_fun OUTPUT_FUN]        
              [--num_workers NUM_WORKERS] [--itr ITR] [--train_epochs TRAIN_EPOCHS] [--batch_size BATCH_SIZE]      
              [--patience PATIENCE] [--learning_rate LEARNING_RATE] [--des DES] [--loss LOSS] [--lradj LRADJ]      
              [--use_amp] [--use_gpu USE_GPU] [--gpu GPU] [--use_multi_gpu] [--devices DEVICES]
run.py: error: the following arguments are required: --is_training, --model_id, --model, --data
