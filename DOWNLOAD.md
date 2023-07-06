Dataset **Road Sign Detection** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/Q/J/Z2/0DKhAdvx2jBLaSKrhguvqVLq6AOY3BEm09m16DESXamcA9wSkk1fUwi3rjcwegKZCT3mpSUnCbpo6rgtuM7aEmQFphhedVuMZGiXuYLz89J4s9DnsMxeqigGMBoZ.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Road Sign Detection', dst_path='~/dtools/datasets/Road Sign Detection.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/andrewmvd/road-sign-detection/download?datasetVersionNumber=1)