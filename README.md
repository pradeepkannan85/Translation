# Translation
Translation


Step 1: Download deu.txt file from Git to Local device.
Step 2: Change the path_to_file to downloaded file location ex:"path_to_file = "C:/Users/Pradeep/Downloads/deu-eng/deu.txt".
Step 3: Execute the program and train model - it will take around 5 min to train the model.
Step 4: Second time execution comment the training part code, so it will restore the latest checkpoint and give you the translated test.

Issue :
Second time execution it is taking around 45 second to get the translated test because i am preparing dataset encoder decoder and checkpoint every time of execution. I need some solution like use the trained checkpoint every time.

