## <center>实验十三 弦上驻波实验 实验报告</center>
#### <div align="right">田宜耕 2500011522</div>

### 一、测量弦线线密度
测量得到$d\approx1.088\mathrm{mm}$.匹配对应样品，测得$l=87.2\mathrm{cm},m=5.38\mathrm{g}$,则<br>$\rho_l=\frac{m}{l}=6.17*10^{-3}\mathrm{kg/m}$.
由于测量时样品无法完全拉直，因而长度误差和线密度不确定度无法准确计算。由$\sigma_m=\sqrt{3}*0.01\mathrm{g}$,估计$\sigma_l=1\mathrm{cm}$,则
<center>$\sigma_{\rho}=\sqrt{(\frac{\sigma_m}{l})^2+(\frac{m\sigma_l}{l^2})^2}=0.38\mathrm{m/s^2}=2*10^{-4}\mathrm{kg/m}$.</center>

### 二、共振频率与驻波波腹个数的关系
#### 1.共振的实验现象和判据
当驱动频率逐渐增大接近共振频率约$\mathrm{1Hz}$以内时，弦线振动显著增大，随后快速减小。频率逐渐减小时也有此现象。接近共振时，波形扭曲和变化都逐渐减弱。在这两个极大值以内，用手使弦线停止振动，如果弦线振动能够迅速增大恢复，不出现亚稳态现象（即振动先增大，随后缓慢减小并逐渐稳定）而是增大并稳定，且稳定位置振幅最大、波形稳定时即为共振点。
#### 2.实验数据的分析
控制弦线振动有效长度$L=50.00\mathrm{cm}$,重物位于$2mg$位置，张力约为$19.628\mathrm{N}$,改变共振时驻波波腹的数目，对实验数据作图如下：
<div style="text-align:center">
    <img src="13_1_p1.png" width="550px">
    <figcaption>fig1 共振频率与驻波波腹个数的关系</figcaption>
</div>
进行线性拟合，得到斜率$k=\frac{v}{2L}=(64.9\pm0.2)\mathrm{Hz}$.<br>
长度测量的允差为$0.1\mathrm{cm}$,因此不确定度$\sigma_L=\sqrt{2*3}*0.1\approx0.25\mathrm{cm}$.我们有
$$\begin{align*}
    &v=64.9*2L=64.9\mathrm{m/s^2}\\
    &\sigma_v=\sqrt{(2k\sigma_L)^2+(2L\sigma_k)^2}=0.38\mathrm{m/s^2}
\end{align*}$$
因此弦上波速
<center>$v=64.9\pm0.3 \mathrm{m/s^2}$.</center>
由线密度计算$v=\sqrt{\frac{F_T}{\rho_l}}=56.4\mathrm{m/s}$,误差在20%以内。

### 三、共振频率（基频）与弦线张力的关系
对式$f_1=\frac{1}{2L}\sqrt{\frac{F_T}{\rho_l}}$两端平方，得到$f_1^2=cF_T$，其中$c=\frac{1}{4L^2\rho_l}$.
对$f_1^2-F_T$作图并线性拟合，得到
<div style="text-align:center">
    <img src="13_3_p1.png", width="500px">
    <figcaption>fig2 $f_1^2-F_T$图像</figcaption>
</div>
<br>
相关系数$r^2=0.99825$,说明$f_1^2$与$F_T$有良好的线性关系，从而
<center>$f\propto{F_T}^{0.5}$.</center>

### 四、共振频率（基频）与有效长度的关系
对式$f_1=\frac{1}{2L}\sqrt{\frac{F_T}{\rho_l}}$同样可以得到$f_1=cL^{-1}
$，其中$c=\frac{1}{2}\sqrt{\frac{F_T}{\rho_l}}$.
对$f_1-L^{-1}$作图并线性拟合，得到
<div style="text-align:center">
    <img src="13_4_p1.png", width="500px">
    <figcaption>fig2 $f_1^2-F_T$图像</figcaption>
</div>
<br>
相关系数$r^2=0.99506$,说明$f_1$与$L^{-1}$有良好的线性关系，从而
<center>$f\propto L^{-1}$.</center>