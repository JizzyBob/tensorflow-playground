takes about 40m to train

python .\train.py --image_dir=c:\tf_files\flower_photos

python .\test.py --graph=c:\tf_images\output_graph.pb  --labels=c:\tf_images\output_labels.txt --input_layer=Placeholder --output_layer=final_result--image=c:\tf_images\test-flower7.jpg