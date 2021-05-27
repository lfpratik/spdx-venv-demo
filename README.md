# spdx-venv-demo

### Steps to follow

###### Clone Project

    https client: 
    <your_workspace_dir>$ git clone https://github.com/lfpratik/spdx-venv-demo.git
    
    ssh client: 
    <your_workspace_dir>$ git clone git@github.com:lfpratik/spdx-venv-demo.git

###### Goto project dir
    <your_workspace_dir>$ cd spdx-venv-demo

###### Create a virtul env for project
    spdx-venv-demo$ python -m venv venv     # for python2
    spdx-venv-demo$ python3 -m venv venv    # for python3

###### Activate the virtul env
    spdx-venv-demo$ source venv/bin/active

##### Activate the virtul env
    (venv) spdx-venv-demo$ pip install -r requirements     # for python2
    (venv) spdx-venv-demo$ pip3 install -r requirements    # for python3

###### Deactivate
    (venv) spdx-venv-demo$ deactivate
