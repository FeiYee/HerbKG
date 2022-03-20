# Herbal entity extraction based on BioBERT

# Additional DataSet：
Link：https://pan.baidu.com/s/1pK7edbDEcQ5AjwWczaJxHg 

PassWord：herb

# Pretrained model:
Link：https://pan.baidu.com/s/1hO__P44XxzgUsqKQvrzcFg 

PassWord：herb

# Demo
https://adventurous-production-58c.notion.site/HerbKG-Documentation-b0e82bbcc29f4754950d701f2397e832

# Trainning demo:
  ->pip install -r requirements.txt
  
  ->python run_classifier.py --task_name=mrpc --do_train=True --do_eval=True --do_predict=True do_train_and_eval=True --save_checkpoint_max=10000 --num_train_epochs=1 --max_seq_length=512 --train_batch_size=16 --data_dir=DiseaseData --vocab_file=pretrained/vocab.txt --bert_config_file=pretrained/config.json --init_checkpoint=pretrained/model.ckpt --output_dir=outputs
