* This is example project that contains gRPC server and gRPC client Example
* To run it, create a virtual env and install gRPC package
    * $ python -m pip install virtualenv
    * $ virtualenv venv
    * $ source venv/bin/activate
    * $ python -m pip install --upgrade pip
    * $ pip install grpcio

* Once package is installed, run following command to run server and client stub
    * $ python greeter_server.py
    * $ python greeter_client.py
    
* Update the proto file according to your use case and run the following command
    * $ python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. helloworld.proto

* Override the method in Greeter class that resides in greeting_server.py
* Later update the client stub as well to call the new service.

* Happy Coding :)