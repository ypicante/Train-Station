# Train-Station
A tool for producing .h5 and .keras AI models for image classification for up to 6 classes. Epochs and Batch Size are customizable. Each class must be in the form of folders with images inside.


# Download Executable
[Dropbox Download](https://www.dropbox.com/scl/fi/bj94d8kmecmz2aatzeit4/TrainStation.exe?rlkey=2d0lgfrz69oon4gsmrtzhiycu&st=hma8uqh3&dl=0)

# Usage
1. Open the executable, a terminal window will open along with it to view the training process
2. In each class, add a folder with the images you wish to train that class with. However the folder is named will be its class name, so do not change the text in the input fields after you add a folder. Leave classes blank if you do not wish to use them.
3. Enter Epochs and Batch Size (overfitting can be reduced by lowering Epochs, but a diverse dataset is usually superior to reduce overfitting)
4. Click "TRAIN". This begins the training process, and information is constantly relayed through the terminal.
5. After training, two file paths appear in the terminal. These are the file paths to your .h5, and .keras models.

# Notes
CPU usage is not limited by this program, so it will use every resource it has access to. You may wish to limit resource usage by this program during training.

