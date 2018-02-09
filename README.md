# AgBot2018_VidStream

`git clone https://github.com/tensorflow/models.git`


OR click the green "clone or download" button on the https://github.com/tensorflow/models page, download the .zip, and extract it.


For CPU TensorFlow, you can just do: `pip3 install tensorflow`


`pip3 install pillow`


`pip3 install lxml`


`pip3 install matplotlib`


`pip3 install opencv-python`


go to: models/research :`protoc object_detection/protos/*.proto --python_out=.`


And...


`export PYTHONPATH=$PYTHONPATH:`pwd`:`pwd`/slim`

go to:models/research/object_detection/:

`python3 DNNvid.py`
