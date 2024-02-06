#### Requirements

```bash
Platform: linux-64
GPU:
```


#### Prepare the Environment: 

```bash
conda create --name myenv python=3.7.16
conda activate myenv
```

#### Navigate to Your Project Directory: If you haven’t already, navigate to the directory containing unzipped "Anomaly_Submission" folder. For example:
#### cd path/to/your/Anomaly_Submission "e.g - "

```bash
cd Anomaly_Submission
```

#### then
```bash
pip install -r requirements.txt
```

#### then run 

```bash
time python test.py
```


#### if you want to train model for 10 epochs

```bash
time python main.py
```





## Citation
      @misc{chen2022mgfn,
      title={MGFN: Magnitude-Contrastive Glance-and-Focus Network for Weakly-Supervised Video Anomaly Detection}, 
      author={Yingxian Chen and Zhengzhe Liu and Baoheng Zhang and Wilton Fok and Xiaojuan Qi and Yik-Chung Wu},
      year={2022},
      eprint={2211.15098},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
      }
