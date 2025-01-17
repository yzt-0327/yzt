# yzt
这是中山大学人工智能专业的大三机器学习大作业项目





  
## 安装与运行
由于数据处理程序不同，ML-1M 上的结果与 CODIGEM 中报告的结果不同
python main.py --cuda --dataset=$1 --data_path=../datasets/$1/ --emb_path=../datasets/ --lr1=$2 --lr2=$3 --wd1=$4 --wd2=$5 --batch_size=$6 --n_cate=$7 --in_dims=$8 --out_dims=$9 --lamda=${10} --mlp_dims=${11} --emb_size=${12} --mean_type=${13} --steps=${14} --noise_scale=${15} --noise_min=${16} --noise_max=${17} --sampling_steps=${18} --reweight=${19} --log_name=${20} --round=${21} --gpu=${22}
python main.py --cuda --dataset=$1 --data_path=../datasets/$1/ --lr=$2 --weight_decay=$3 --batch_size=$4 --dims=$5 --emb_size=$6 --mean_type=$7 --steps=$8 --noise_scale=$9 --noise_min=${10} --noise_max=${11} --sampling_steps=${12} --reweight=${13} --w_min=${14} --w_max=${15} --log_name=${16} --round=${17} --gpu=${18}
python main.py --cuda --dataset=$1 --data_path=../datasets/$1/ --emb_path=../datasets/ --lr1=$2 --lr2=$3 --wd1=$4 --wd2=$5 --batch_size=$6 --n_cate=$7 --in_dims=$8 --out_dims=$9 --lamda=${10} --mlp_dims=${11} --emb_size=${12} --mean_type=${13} --steps=${14} --noise_scale=${15} --noise_min=${16} --noise_max=${17} --sampling_steps=${18} --reweight=${19} --w_min=${20} --w_max=${21} --log_name=${22} --round=${23} --gpu=${24}

### 依赖要求
框架：rechorus
numpy==1.26.4
pandas==2.2.2
scipy==1.13.1
matplotlib==3.9.2
seaborn==0.13.2
torch==2.5.0
torchvision==0.20.1
torchaudio==2.5.1
python==3.12.7
jupyter==1.0.0
pyyaml==6.0.1

## 致谢

该项目建立在其他几个存储库的工作基础上。我们对以下项目的贡献表示感谢：

- [ReChorus](https://github.com/THUwangcy/ReChorus): 
- [DiffRec](https://github.com/YiyanXu/DiffRec?tab=readme-ov-file):
- [DiffRec_on_ReChorus](https://github.com/pangy9/DiffRec_on_ReChorus):
- [How-Diffusion-Models-Work](https://github.com/woshiwangzihao/How-Diffusion-Models-Work):
---

## 许可证

本项目基于 [ReChorus](https://github.com/THUwangcy/ReChorus)，原始项目使用 MIT 许可证。 
机器学习
