# ML_Algorithms

once you run the first cell the yolov5 fle is updated in the folder section 
Go to yolov5/data/coc128.yaml
Make the below changes to /content/yolov5/data/coco128.yaml:

    train: /content/train_data/images/train  # train images (relative to 'path') 128 images
    val: /content/train_data/images/val # val images (relative to 'path') 128 images

    nc: 1  # number of classes
    names: ['car']  # class name

then rename the file to new_project.yaml

then continue 

Hope this makes it easy for few who are starting out 
i followed this Youtube video : https://www.youtube.com/watch?v=GRtgLlwxpc4&t=946s
