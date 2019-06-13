# test using pretrained model

## download image
- put in logs/images
- resize image using logs/resize.ipynb
- resized image (512x1042) in logs/images/image_pad.png

## download pretrained model
- download 'Noise sampling model'

## run testing
```
python compress.py -r pretrained/noiseMScsC8/noiseMScsC8_epoch15.ckpt-15 -i logs/images/image_pad.jpg
```
## results
- samples/cityscapes/image_pad_compressed.pdf (not successful)

