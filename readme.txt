The MNIST_data_download.py is used to download MNIST dataset.(To train our module)

The mnistdeep.py is used to create a deep module,train the module and save the best module.

The test.py is used to classify a handwrite number.

在使用flask运行upload_file.py文件时，会出现can not find tensorflow的错误，这是因为flask采用的交互式默认环境为不是conda设置的虚拟环境，我们需要使用conda activate <environment_name>后在利用flask运行upload_file.py文件。



