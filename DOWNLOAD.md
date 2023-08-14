Dataset **Road Sign Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/g/g/04/RnnI4MnIA09YwQfGIN6nqpBshYXx9sFS1e8WPT9n97Hisy8Y0jeMISNTuun0VYBjr1L0B1HBJes7lGPF62vimnBpZ7mFOItLD4l7jvgxKcRGujgVldCZniKkW0Jb.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Road Sign Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/andrewmvd/road-sign-detection/download?datasetVersionNumber=1).