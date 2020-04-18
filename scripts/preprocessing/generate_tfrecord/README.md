<<< Change the generate_tfrecord.py file --- inside chenge the row-labels texts and int numbers

in promt - go to C:\TensorFlow\scripts\preprocessing\generate_tfrecord - and execute as below

python generate_tfrecord.py --csv_input=C:/TensorFlow/workspace/training_demo/annotations/train_labels.csv --image_dir=C:/TensorFlow/workspace/training_demo/images/train --output_path=C:/TensorFlow/workspace/training_demo/annotations/train.record
python generate_tfrecord.py --csv_input=C:/TensorFlow/workspace/training_demo/annotations/test_labels.csv --image_dir=C:/TensorFlow/workspace/training_demo/images/test --output_path=C:/TensorFlow/workspace/training_demo/annotations/test.record