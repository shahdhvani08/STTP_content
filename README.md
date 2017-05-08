# STTP_content
This project predicts the the requirement of trains for Mumbai suburbs. train.csv is the dummy set that been created on assumption that total crowd is 400 and the source station is Virar.
traincasting.ipynb is the notebook which contains the code as well as its corresponding output.
For predictive analytics on titanic dataset the titanic3.xlsx is the dataset and titanic.ipynb is the python notebook that predicts whether the given human woulh have been survivied on the day of that diaster.
BasicsOfPython.rar includes documents with basic syntax of python along with many examples
Handouts for Raspberry Pi is also included.
The interfacing of RPi and rfid along with its python code is also attached.
The code to send the rfid data to aws iot is included in file rpitoaws.py
Libraries needed for machine learning section:
            apt-get install  -y python-pip
            apt-get install -y python-dev
            apt-get install -y python-virtualenv
            virtualenv env
            source env/bin/activate
            pip install --upgrade pip
            pip install Jupyter
            pip install numpy
            pip install pandas
            pip install scikit-learn
            pip install openpyxl
            pip install statsmodels
            pip install scipy
            pip install xlrd
            pip install matplotlib
Libraries for rfid on RPi:
      pip install pi-rc522
    Or get source code from Github:

      git clone https://github.com/ondryaso/pi-rc522.git
      cd pi-rc522
      python setup.py install
Libraries for AWS IoT on RPi:
      pip install AWSIoTPythonSDK
    Steps to configure AWS IoT:
    1. Go to AWS management console
    2. Click on AWS IoT
    3. Under Registry, create a Thing
    4. Under Security, create certificates and download them too.
    5. Create policies for the Thing and attach the policies with the Thing created.
