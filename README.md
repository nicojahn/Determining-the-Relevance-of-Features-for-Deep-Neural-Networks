# My take on evaluating ...
```"Determining the Relevance of Features for Deep Neural Networks", Reimers et al. (2020)```

* Each notebook should be rather self-contained (maybe 1-2 missing packages)
* At the end of each notebook are open questions

### Get the submodule (for the MS COCO example)
* ```git submodule update --init --recursive```

### Download all complementary data (for the MS COCO example)
* get the coco model: https://drive.google.com/open?id=1ivLi1Rc-dCUmN1ProcMk76zxF1DSvlIk
* put it into: ML_GCN/checkpoint/coco/coco_checkpoint.pth.tar

* get the valdiation data: http://images.cocodataset.org/zips/val2014.zip
* get the annotations: http://images.cocodataset.org/annotations/annotations_trainval2014.zip
* place both files into the directory: ML_GCN/data/coco/tmp/