# auto-youth-study-gd
Automatically and regularly execute versions of youth study scripts on github actions

## usage
```
git clone https://github.com/JimouChen/auto-youth-study-gd.git
```
- then```cd auto-youth-study-gd```

- install requirements
```shell
pip install -r requirements.txt
```
or
```shell
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
```

- run
```shell
python auto_youth_study.py your-mid-value
```

## github actions res
- set schedule time/每天下午13点运行一次
```yml
  schedule:
    - cron: '0 5 * * *'
```
- run successfully
![](https://img2022.cnblogs.com/blog/2134757/202209/2134757-20220930145558494-1416637048.png)
