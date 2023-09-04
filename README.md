# Diffusion-Models

Learning for Diffusion Models

**为了能够离线编辑，我们使用githubdesktop软件，并且使用分支进行管理，并且使用typora进行md文件的书写。详情请看githubdesktop.txt**

## 扩散模型

扩散模型：和其他生成模型一样，实现从噪声（采样自简单的分布）生成目标数据样本。

扩散模型包括两个过程：前向过程（forward process）和反向过程（reverse process），其中前向过程又称为扩散过程（diffusion process）。无论是前向过程还是反向过程都是一个参数化的马尔可夫链（Markov chain），其中反向过程可用于生成数据样本（它的作用类似GAN中的生成器，只不过GAN生成器会有维度变化，而DDPM的反向过程没有维度变化）。

### 马尔科夫链

| 文章名                                   | Link                                                         |
| :--------------------------------------- | ------------------------------------------------------------ |
| 马尔可夫链(Markov Chain)是什么？通俗易懂 | [https://blog.csdn.net/weixin_42509541/article/details/123332839](Linki) |





