

# Music AI


```
bash python encode.py --files_path folder_of_audio_files --save_path folder_of_encodings
```

```bash
python train.py --train_path folder_of_encodings
```












<!-- 
```bash
python train.py --train_path folder_of_encodings --load_path checkpoints/-x/-xk_losses-x-x-x-x
``` -->

### 


```bash
python train.py --train_path folder_of_encodings --load_path checkpoints/misc --lr 0.00004
```




```bash
python train.py --train_path folder_of_encodings --load_path checkpoints/techno --lr 0.00004
```


```bash
python train.py --train_path folder_of_encodings --load_path checkpoints/misc_small --small True --lr 0.00004
```




## Extras

```bash
python decode.py --files_path folder_of_encodings --save_path folder_of_audio_files
```



