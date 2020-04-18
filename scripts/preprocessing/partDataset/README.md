To use the script, simply copy and paste the code above in a script named partition_dataset.py. Then, assuming you have all your images and *.xml files inside training_demo\images, just run the following command:

python partition_dataset.py -x -i training_demo\images -r 0.1

Once the script has finished, there should exist two new folders under training_demo\images, namely training_demo\images\train and training_demo\images\test, containing 90% and 10% of the images (and *.xml files), respectively. To avoid loss of any files, the script will not delete the images under training_demo\images. Once you have checked that your images have been safely copied over, you can delete the images under training_demo\images manually.