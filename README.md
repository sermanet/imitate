Pierre Sermanet<sup>1</sup>\*, Corey Lynch<sup>1</sup>\*†, Yevgen Chebotar<sup>2</sup>\*, Jasmine Hsu<sup>1</sup>, Eric Jang<sup>1</sup>, Stephan Schaal<sup>2</sup>, Sergey Levine<sup>1</sup><br>
<sup>1</sup> Google Brain, <sup>2</sup> University of Southern California<br>
(* equal contribution, † Google Brain Residency program [g.co/brainresidency](https://research.google.com/teams/brain/residency/))

This project is part of the larger [Unsupervised Imitation Learning](https://sermanet.github.io/imitation/) project.
It extends the [TCN project](https://sermanet.github.io/tcn/) with Reinforcement Learning and more real robots.

### [[ Paper ]](https://arxiv.org/abs/1704.06888) [[ Video ]](https://www.youtube.com/watch?v=b1UTUQpxPSY) [[ Dataset ]](https://sites.google.com/site/brainrobotdata/home/multiview-pouring)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=b1UTUQpxPSY" target="_blank">
 <img src="docs/figs/tcn2_youtube_thumbnail.png" alt="TCN" width="480">
</a>

### Self-supervised imitation
<img src='docs/figs/kuka_pouring.mov.gif'>

<img src='docs/figs/kuka_dishrack.mov.gif'>

<img src='docs/figs/pose_all.mov.gif'>

### Learning control

<img src='docs/figs/kuka_pouring_control.mov.gif'>

<img src='docs/figs/kuka_dishrack_control.mov.gif'>

##### Abstract
# Citation

```
@article{TCN2017,
  title={Time-Contrastive Networks: Self-Supervised Learning from Video},
  author={Sermanet, Pierre and Lynch, Corey and Chebotar, Yevgen and Hsu, Jasmine and Jang, Eric and Schaal, Stefan and Levine, Sergey},
  journal={arXiv preprint arXiv:1704.06888},
  year={2017}
}
```

# Acknowledgments

We thank Mohi Khansari, Yunfei Bai and Erwin Coumans for help with VR simulations, Jonathan Tompson, James Davidson and Vincent Vanhoucke for helpful discussions and feedback. We thank everyone who provided imitations for this project: Phing Lee, Alexander Toshev, Anna Goldie, Deanna Chen, Deirdre Quillen, Dieterich Lawson, Eric Langlois, Ethan Holly, Irwan Bello, Jasmine Collins, Jeff Dean, Julian Ibarz, Ken Oslund, Laura Downs, Leslie Phillips, Luke Metz, Mike Schuster, Ryan Dahl, Sam Schoenholz and Yifei Feng.
