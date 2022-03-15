# asr_correction

```
python run_correction.py     --model_name_or_path moussaKam/barthez     --do_train  --do_eval    --source_lang HYPOTHESE     --target_lang REFERENCE     --dataset_name wmt16     --dataset_config_name ro-en     --output_dir tmp/bart-ocr-summarization-french     --per_device_train_batch_size=16     --per_device_eval_batch_size=16     --overwrite_output_dir     --predict_with_generate --num_train_epochs 25 --logging_steps 100000000
```
```
python run_correction.py     --model_name_or_path moussaKam/barthez     --do_predict    --source_lang HYPOTHESE     --target_lang REFERENCE     --dataset_name wmt16     --dataset_config_name ro-en     --output_dir tmp/bart-ocr-summarization-french     --per_device_train_batch_size=16     --per_device_eval_batch_size=16     --overwrite_output_dir     --predict_with_generate --num_train_epochs 25 --logging_steps 100000000
```
