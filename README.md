# chinese_L-12_H-768_A-12
网上没找到，就自己传来用

缺个文件-在传

lfs上传代码

$ git init

$ ssh-keygen -t rsa -C "一个qq@qq.com"

$ ssh -T git@github.com

$ git clone git@github.com:ShinerayLu/chinese_L-12_H-768_A-12.git

$ cd chinese_L-12_H-768_A-12

$ git lfs install

$ git lfs track "*.data-00000-of-00001"

$ git add .gitattributes

$ git add bert_model.ckpt.data-00000-of-00001

$ git commit -m "bert_model.ckpt.data-00000-of-00001"

$ git push -u origin main

