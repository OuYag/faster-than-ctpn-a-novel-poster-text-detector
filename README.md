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
0.8768 fmeans. 

The opensource text detector like East/Textboxes++/pixel-link/ctpn all have very obvious shortage, which can't
meet the actual need in work. Now I have been modifying the framework, to detect any size and any orientation text. 
The framework is what I persue for so long time, wish me good luck. 

The CVPR2019 paper is submmited, our method named Pixel-Anchor. Now our framework can detect large angle long Chinese texts. We upload some new detect demo images. 

