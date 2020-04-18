# Create train data:
python xml_to_csv.py -i [PATH_TO_IMAGES_FOLDER]/train -o [PATH_TO_ANNOTATIONS_FOLDER]/train_labels.csv

# Create test data:
python xml_to_csv.py -i [PATH_TO_IMAGES_FOLDER]/test -o [PATH_TO_ANNOTATIONS_FOLDER]/test_labels.csv

# For example
# python xml_to_csv.py -i C:\TensorFlow\workspace\training_demo\images\train -o C:\TensorFlow\workspace\training_demo\annotations\train_labels.csv
# python xml_to_csv.py -i C:\TensorFlow\workspace\training_demo\images\test -o C:\TensorFlow\workspace\training_demo\annotations\test_labels.csv