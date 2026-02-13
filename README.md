# Trieste_Workshop

Welcome to this workshop! Hope you find it interesting 😁😁😁

It is recommended that you have an editor like VS Code or Pycharm installed in your computer.

1)	Download this Github Repository.
2)	Extract the folder.
3)	Open your PowerShell and move into the folder Trieste_Workshop.
4)	Execute the command: pip install -r requirements.txt (This installs the required libraries).
5)	Run the command: python workshop.py --n [number_of_images_for_testing]

   number_of_images_for_testing=5 ->inference in 5 images
   
   number_of_images_for_testing=20 ->inference in 20 images
   
After that, you can check the results in runs folder.
Moreover, you can see the subset_test txt file, the images that were used for inference and in subset_data xml file the location of subset_test txt file. This is a failsafe measure in order to ensure that the results that you see are correct. 

Additionally, you can observe different inference results in folder runs/detect/ after you execute the program.

*Important notice: In dataset/train and dataset/valid, you will find 2 blank txt files named blank.txt. Do not remove them, because this might occur to an error.

Thank you so much for your time!

If you require any other information, please do not hesitate to contact me in csarantidis@ionio.gr.
