# ResNet-18-PyTorch-Transfer-Learning-Cats-and-Dogs-breed-classification
A Transfer Learning model based on ResNet-18 to classify cats and dogs beetween 38 different breeds with a small dataset.


#### Dataset: Training was done with around 200 images per breed and test around 50. Cats and dogs weren't splitted during the training.
Albumentations not implemented.
### Cats Classification:
| Cat Breed | Accuracy |                                                             Training lại:     Training complete in 90m 2s;   Best val Acc: 0.917722
|----------|:----------:|                                                            Tác giả:          Training complete in 58m 14s;  Best val Acc: 0.787447
| Abyssinian | 26.83% |41.46%
| Bengal | 42.00% |26.00%
| Birman | 58.00% |42.00%
| Bombay | 71.74% |80.43%
| British Shothair | 59.46% |56.76%
| Egyptian Mau | 88.64% |68.18%
| Maine Coon | 30.95% |16.67%
| Persian | 88.64% |97.73%
| Ragdoll| 45.95% |43.24
| Russian Blue| 67.65% |50%
| Siamese | 55.56% |55.56%
| Sphynx | 100.00% |100.00%


### Dogs Classification:
| Dog Breed | Accuracy |
|----------|:----------:|
| American Bulldog | 89.36% | 85.11%
| American Pit Bull Terrier | 35.42% | 35.42%
| Basset Hound | 64.00% | 68.00%
| Beagle | 75.51% | 77.55%
| Boxer | 60.00% | 70%
| Chihuahua | 78.00% | 80%
| English Cocker Spaniel | 88.00% | 82.00%
| English Setter | 82.00% | 66%
| German Shorthaired | 96.00% | 94.00%
| Great Pyrenees | 86.00% | 90.00%
| Havanese | 74.00% | 60.00%
| Japanese Chin | 78.00% | 76.00%
| Keeshond |34.00% | 8.00%
| Leonberger |26.00% | 22.00%
| Miniature Pinscher |54.00% | 52.00%
| Newfoundland |78.00% |  82.00%
| Pomeranian |40.00% | 60.00%
| Pug |62.00% | 66.00%
| Saint Bernard| 46.00% | 56.00%
| Samoyed | 100.00% | 100.00%
| Scottish Terrier | 98.00% | 96.00 %
| Shiba Inu | 89.58% | 82.25%
| Staffordshire Bull Terrier | 33.33% | 14.58%
| Wheaten Terrier | 76.00% | 80.00%
| Yorkshire Terrier | 28.00% | 36.00%


## Overall Accuracy: 78.74% 

![cats_dogs](https://user-images.githubusercontent.com/56324869/101435413-0f4b5f80-38eb-11eb-8244-00a351a497df.png)

![cats_dogs2](https://user-images.githubusercontent.com/56324869/101435422-170b0400-38eb-11eb-9de3-c243fd2032b4.png)

Feel free to learn from it or make it better!
You can download the model and the dataset right 
[there](https://drive.google.com/drive/folders/1dD2-FC1051nHMZzhx1UQmKfDiCGcuXKQ?usp=sharing).
Phân biệt chó mẻo:
|Lr = 0,001; batch_size = 8; numwoker = 4|
|Epoch 0/9
----------
train Loss: 0.3711 Acc: 0.8716
val Loss: 0.0454 Acc: 0.9895

Epoch 1/9
----------
train Loss: 0.1919 Acc: 0.9194
val Loss: 0.0307 Acc: 0.9916

Epoch 2/9
----------
train Loss: 0.1739 Acc: 0.9305
val Loss: 0.0272 Acc: 0.9916

Epoch 3/9
----------
train Loss: 0.1901 Acc: 0.9206
val Loss: 0.0230 Acc: 0.9947

Epoch 4/9
----------
train Loss: 0.1617 Acc: 0.9327
val Loss: 0.0226 Acc: 0.9937

Epoch 5/9
----------
train Loss: 0.1730 Acc: 0.9315
val Loss: 0.0217 Acc: 0.9937

Epoch 6/9
----------
train Loss: 0.1515 Acc: 0.9361
val Loss: 0.0210 Acc: 0.9947

Epoch 7/9
----------
train Loss: 0.1335 Acc: 0.9478
val Loss: 0.0319 Acc: 0.9895

Epoch 8/9
----------
train Loss: 0.1423 Acc: 0.9399
val Loss: 0.0276 Acc: 0.9916

Epoch 9/9
----------
train Loss: 0.1445 Acc: 0.9417
val Loss: 0.0172 Acc: 0.9953

Training complete in 81m 17s
Best val Acc: 0.995253
|Lr = 0,001; batch_size = 4; numwoker = 4|
Epoch 0/9
----------
train Loss: 0.3715 Acc: 0.8521
val Loss: 0.0391 Acc: 0.9889

Epoch 1/9
----------
train Loss: 0.2730 Acc: 0.8876
val Loss: 0.0361 Acc: 0.9921

Epoch 2/9
----------
train Loss: 0.2490 Acc: 0.9011
val Loss: 0.0281 Acc: 0.9926

Epoch 3/9
----------
train Loss: 0.2547 Acc: 0.9002
val Loss: 0.0269 Acc: 0.9921

Epoch 4/9
----------
train Loss: 0.2193 Acc: 0.9104
val Loss: 0.0229 Acc: 0.9958

Epoch 5/9
----------
train Loss: 0.2222 Acc: 0.9150
val Loss: 0.0249 Acc: 0.9937

Epoch 6/9
----------
train Loss: 0.2290 Acc: 0.9099
val Loss: 0.0273 Acc: 0.9931

Epoch 7/9
----------
train Loss: 0.1984 Acc: 0.9250
val Loss: 0.0336 Acc: 0.9916

Epoch 8/9
----------
train Loss: 0.2026 Acc: 0.9247
val Loss: 0.0405 Acc: 0.9895

Epoch 9/9
----------
train Loss: 0.2048 Acc: 0.9243
val Loss: 0.0349 Acc: 0.9937

Training complete in 397m 48s
Best val Acc: 0.995781