# poster-text-detector

We have develop a text detector for poster. 
here is some detected samples. 

### what problem we have solve:
- conv kernel receptive field limitation problem. 
- detect long chinese text. 
- detect very dense long chinese text. 
	
The method is much faster than ctpn, and we have cpu edition and gpu edition. 
mean while, we can detect oriented text. 

we have tested in the icdar15 benchmark dataset, With a single scale, we can achieve
0.8768 fmeans. With multi-scale, we can achieve 89.54 fmeans. 

The opensource text detector like East/Textboxes++/pixel-link/ctpn all have very obvious shortage, which can't
meet the actual need in work. Now I have been modifying the framework, to detect any size and any orientation text. 
The framework is what I persue for so long time, wish me good luck. 

Now our framework can detect large angle long Chinese texts. We upload some new detect demo images. 

Our method is fast, single shot, and can be really used in practice. 

Our framework named Pixel-Anchor, The arXiv paper:
https://arxiv.org/abs/1811.07432

Recently, we develop a text detector for fapiao, we have upload some detect samples. 

工作满一年，写了一些总结，https://github.com/Yuanhang8605/text-detector-experience.git，都是干货，分享一下，
愿不再有人趟坑，算法保佑大家。
