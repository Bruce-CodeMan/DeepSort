# Yolov5-DeepSort

## ==How to train Market-1501 Person dataSets==

```
1. Download Market-1501-v15.09.15, Then copy this folder to deep_sort/deep_sort
2. Run prepare_person.py, You will find a new folder named "pytorch" in Market-1501-v15.09.15
3. create a new folder named "Market" in deep_sort/deep_sort/deep And copy the /pytorch/train & test folders into the Market folder
4. python train.py --data-dir ./Market
5. You will get ckpt.t7 in the checkpoint
```

