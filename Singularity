Bootstrap:docker
From:centos:7.3.1611

%post
    # install other needed packages
    yum clean all
    yum -y update
    yum -y install epel-release
    yum -y install python-pip

    # install tensorflow
    pip install -U pip~=9.0
    pip install tensorflow==1.6
