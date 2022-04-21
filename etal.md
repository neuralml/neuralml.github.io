---
title: Neural & ML Group
permalink: /etal/
---

### Videos


<div class="content list people" style="text-align: center;">
  <div class="list-item-people" style="width: 49%">
    <p class="list-post-title">
      <center>
        Reorganising cortical learning (<a href="https://www.cosyne.org/">Cosyne'22</a>):
          <style>.embed-container { position: relative; margin-bottom: 0px; padding-bottom: 50%; height: 0; overflow: hidden; max-width: 75%; max-height: 85%;} .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 80%; height: 55%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/jnYJBJ2kndA' frameborder='0' allowfullscreen></iframe></div>
        </center>      
      </p>    
   </div><br>
</div>

<div class="content list people" style="text-align: left;">
  <div class="list-item-people" style="width: 49%">
    <p class="list-post-title">
      <center>
      	Ode to the brain:
          <style>.embed-container { position: relative; margin-bottom: 0px; padding-bottom: 50%; height: 0; overflow: hidden; max-width: 75%; max-height: 85%;} .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 80%; height: 55%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/JB7jSFeVz1U' frameborder='0' allowfullscreen></iframe></div>
        </center>      
      </p>    
   </div>
   <div class="list-item-people" style="width: 49%">
      <p class="list-post-title">
         <center>
         	On <a href="http://www.cell.com/neuron/fulltext/S0896-6273(17)30861-9">Costa et al. Neuron 2017</a>:
         	<style>.embed-container { position: relative; margin-bottom: 0px; padding-bottom: 50%; height: 0; overflow: hidden; max-width: 80%; max-height: 90%;} .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://player.vimeo.com/video/249505102' width="320" height="200" frameborder='0' allowfullscreen></iframe></div>
        </center>
       </p>
    </div><br>    
</div>

<hr>

### Code & Data


<br>
#### `Github account`
We share the code of (mostly) finished projects on our <b>[Github account](https://github.com/neuralml/)</b>.
<br><br>

#### `Fire together, optimise together: Statistical long-term synaptic plasticity`
<div class="content list people" style="text-align: left;">
  <div class="list-item-people" style="width: 29%">
    <p class="list-post-title">
      <center>
      	<span style="display: block; margin-bottom: 0em; margin-top: 0em"><img class='img-responsive center-block' src="/images/code_data/statltsp-flow.png" width="95%" height="95%"/></span>
        </center>      
      </p>    
   </div>
   <div class="list-item-people" style="width: 70%" >
      <p class="list-post-title" markdown="1">
         	Matlab code to play with our statistical theory of pre/post synaptic plasticity ([Costa et al. 2017](http://www.cell.com/neuron/fulltext/S0896-6273(17)30861-9)) and compare it with data can be downloaded [here](http://modeldb.yale.edu/232096). The multiple datasets used are available through the Mendeley Data sharing system ([hippocampus LTP](http://dx.doi.org/10.17632/m5865cj7dd.2), [hippocampus SLP](http://dx.doi.org/10.17632/x8n3yfzrzc.2), [visual cortex STDP](http://dx.doi.org/10.17632/7wvf2yw4jn.1), [visual cortex LTP](http://dx.doi.org/10.17632/7wvf2yw4jn.1) and [auditory cortex inh. plasticity](http://dx.doi.org/10.17632/gx7r43hm8h.1)). Thanks to [P. Jesper Sjöström](http://plasticity.muhc.mcgill.ca/) and [Robert C. Froemke](http://froemkelab.med.nyu.edu/) for sharing their data, and Alan Larkman for pointing me to the PhD thesis of Hannay with the data from Larkman et al. 1992.        
       </p>
    </div>
</div>
<br>

#### `Cortical microcircuits as gated-RNNs`
<div class="content list people" style="text-align: left;">
  <div class="list-item-people" style="width: 29%">
    <p class="list-post-title">
      <center>
      	<span style="display: block; margin-bottom: -1em; margin-top: 0em"><img class='img-responsive center-block' src="/images/code_data/net-struc-wgating-v15_orig.png" width="95%" height="95%"/></span>
        </center>      
      </p>    
   </div>
   <div class="list-item-people" style="width: 70%" >
      <p class="list-post-title" markdown="1">
         	We proposed a biological view of gated-RNNs, namely LSTMs ([Costa et al. 2017 NeurIPS](https://arxiv.org/abs/1711.02448)). This led to a new model (subLSTM) that only requires a simple modification to existing LSTM implementations, in that the gates become subtractive instead of multiplicative. However, you can find a PyTorch implementation by Russi Chatterjee [here](https://github.com/ixaxaar/pytorch-sublstm).
       </p>
    </div>
</div>
<br>


#### `Synaptic plasticity theory of memory savings`
<div class="content list people" style="text-align: left;">
  <div class="list-item-people" style="width: 29%">
    <p class="list-post-title">
      <center>
      	<span style="display: block; margin-bottom: -2em; margin-top: 0em"><img class='img-responsive center-block' src="/images/code_data/7417349_orig.png" width="95%" height="95%"/></span>
        </center>      
      </p>    
   </div>
   <div class="list-item-people" style="width: 70%" >
      <p class="list-post-title" markdown="1">
         	Python/Matlab code to simulate our cortical learning rule with pre- and postsynaptic components can be downloaded [here](http://modeldb.yale.edu/184487). In this particular simulation we demonstrate its memory savings behaviour as described in [Costa et al. 2015](http://dx.doi.org/10.7554/eLife.09457). And, [here](http://dx.doi.org/10.5061/dryad.p286g) you can get the long-term synaptic plasticity data used to fit the model.
       </p>
    </div>
</div>
<br>


#### `P(STP|data): Probabilistic inference of short-term synaptic plasticity`
<div class="content list people" style="text-align: left;">
  <div class="list-item-people" style="width: 29%">
    <p class="list-post-title">
      <center>
      	<span style="display: block; margin-bottom: -2em; margin-top: 0em"><img class='img-responsive center-block' src="/images/code_data/8527342_orig.png" width="95%" height="95%"/></span>
        </center>      
      </p>    
   </div>
   <div class="list-item-people" style="width: 70%" >
      <p class="list-post-title" markdown="1">
         	You can download [here](http://modeldb.yale.edu/149914) the Matlab code to infer short-term synaptic plasticity parameters given data using a Bayesian framework (and MCMC: Slice Sampling) as described in [Costa et al. 2013](http://www.frontiersin.org/computational_neuroscience/10.3389/fncom.2013.00075/abstract).
       </p>
    </div>
</div>
<br>


#### `Epilab: Epilepsy prediction toolbox`
<div class="content list people" style="text-align: left;">
  <div class="list-item-people" style="width: 29%">
    <p class="list-post-title">
      <center>
      	<span style="display: block; margin-bottom: -2em; margin-top: 0em"><img class='img-responsive center-block' src="/images/code_data/3414592_orig.png" width="70%" height="70%"/></span>
        </center>      
      </p>    
   </div>
   <div class="list-item-people" style="width: 70%" >
      <p class="list-post-title" markdown="1">
         	In the past we collaborated with [EPILEPSIAE](http://www.epilepsiae.eu/), a european research project about epilepsy seizure prediction. I co-authored [Epilab](http://www.epilepsiae.eu/project_outputs/epilab_software), a Matlab toolbox for epilepsy prediction ([Teixeira et al. 2011](http://www.sciencedirect.com/science/article/pii/S0165027011003888) and Direito et al. 2011) and implemented several machine learning techniques ([Teixeira et al. 2011](http://www.sciencedirect.com/science/article/pii/S0165027011003888) and [Costa et al. 2008](http://student.dei.uc.pt/~racosta/publications/papers/RCosta2008_Epileptic%20Seizure%20Classification%20Using%20Neural%20Networks%20With%2014%20Features.pdf)). (Nominated for 2012 Brain Computer Interface research award)
       </p>
    </div>
</div>
<br>


<hr>

### Talks

- TBD, Neuroinformatics Institute, ETH Zurich, June 2022 [by Rui]
- TBD, Dept of Bioengineering, Imperial College London, May 2022 [by Rui]
- Unlocking efficient credit assignment in the brain, [Donders Institute for Brain, Cognition and Behaviour](https://www.ru.nl/donders/), April 2022 [by Rui]
- Cerebro-cerebellar networks as brain-wide decoupling machines, [MIT K. Lisa Yang ICoN Center](https://yangtan.mit.edu/k-lisa-yang-integrative-computational-neuroscience-icon-center/), April 2022 [by Joe]
- Reorganizing cortical learning: a cholinergic adaptive credit assignment model, Filipovica M, Zhu HW, Greedy W, Mellor J and Costa RP, Computational and Systems Neuroscience Meeting (CoSyNe), Lisbon, Mar 2022 [selected talk by Maija]
- Cerebro-cerebellar networks as brain-wide decoupling machines, [Wagner Lab, National Institutes of Health](http://markwagnerlab.com/), Oct 2021 [by Ellen]
- Cortico-cerebellar networks as brain-wide decoupling machines, 1st Symposium on Artificial Intelligence & Neuroscience (ACAIN), October 2021 [by Joe and Ellen]
- Hippocampal encoding of continual reinforcement learning features, 1st Symposium on Artificial Intelligence & Neuroscience (ACAIN), October 2021 [by Dabal and Samia]
- Neuroscience through the lens of machine learning, Bristol SCEEM Research Conference, Online, April 2021
- What else is out there?, CAG Workshop on Dimensionality and flexibility of learning in biological recurrent neural networks, Cognitive Computational Neuroscience Conference, Online, October 2020
- Cerebellum as a brain-wide decoupling machine, Neuromatch'2020, Online, October 2020 [by Joe, Ellen]
- Deep generative models as perceptual front-ends for decision-making, Virtual MATHPSYCH/ICCM 2020, Online, July 2020 [by Milton]
- Cerebellum as a brain-wide decoupling machine, Alergic (Artificial life seminars), University of Sussex, June 2020
- Invited talk, UK Neural Computation Meeting, University of Sheffield, June 2020 [moved to 2021]
- Towards powerful learning in cortical circuits, Computational Neuroscience meeting, Claudia Clopath lab, Imperial College London, May 2019
- Powerful learning in cortical circuits, Brain and Machine Seminar/Neural Dynamics Seminar/CS Seminar, University of Bristol, Mar 2019
- Local and global synaptic credit assignment, Computational Neuroscience Seminar, CBL, University of Cambridge, Jan 2019
- Learning probabilistic synapses: where and when, Computational Neuroscience Seminar, EPFL, Jun 2018
- Computational modelling of synaptic plasticity (talk + tutorial), International PhD module on Synapses, neuronal circuits and behavior (supported by FENS/IBRO-PERC), University of Coimbra, Portugal, April 2018
- Cortical microcircuits as gated-recurrent neural networks, Neuro-Mittagsseminar, Computer Science Dept, ETH Zurich, Switzerland, Jan 2018
- Cortical microcircuits as gated-recurrent neural networks, Machine Learning Seminar, University of Sheffield, UK, Nov 2017
- From machine to neuronal learning (and back again), University of Sheffield, UK, Sept 2017
- From machine to neuronal learning (and back again), University of Bristol, UK, August 2017
- Statistical excitatory and inhibitory long-term synaptic plasticity, Technische Universität Berlin, Berlin, Germany, May 2017
- Statistical excitatory and inhibitory long-term synaptic plasticity, University of Bern, Bern, Switzerland, Mar 2017
- Statistical excitatory and inhibitory long-term synaptic plasticity, New York University, New York, USA, Feb 2017
- Principles of synaptic plasticity loci in cortical circuits, Institute of Experimental Medicine, Hungarian Academy of Sciences, Budapest, Hungary, Oct 2016
- Statistical long-term synaptic plasticity (talk + tutorial), Junior Scientist Workshop on Theoretical Neuroscience, Janelia Farm, USA, Sept 2016
- Long-term synaptic statistical learning. Gatsby Unit, Sainsbury Wellcome Centre for Neural Circuits and Behaviour, University College London, London, UK, March 2016
- Long-term statistical synaptic learning. FENS-KAVLI Scholars annual meeting, Chicheley Hall, Royal Society, UK, March 2016
- Why does the brain need both pre- and postsynaptic long-term plasticity? Forschungszentrum, Julich, Germany, Sept 2015
- Why does the brain need both pre- and postsynaptic long-term plasticity? Computational Neuroscience Seminars, EPFL, Lausanne, Switzerland, Sept 2015
- A multi-scale unified model of synaptic plasticity. Workshop on Analysis of Cortical Circuits, Meon Springs, UK, May 2014
- Pre and postsynaptic plasticity in local cortical circuits. NeuroTheory Forum, University of Oxford, UK, January 2014
- Modelling memory traces of chronic pain. Computational Biology Seminar, IBM T. J. Watson Research Center, NY, USA, August 2013
- Building activity-dependent neocortical routes: from short to long-term synaptic plasticity. Workshop on Activity-dependent Synaptic Plasticity, CNS’2013, Paris, July 2013
- Towards a unified functional description of layer-5 microcircuits. Institute for Theoretical Computer Science, Graz University of Technology, Graz, Austria, May 2012
- Modelling synaptic plasticity in local circuit motifs of the neocortex. Brain-i-Nets Workshop, Leysin, Switzerland, March 2012
- Neuroinformatics & Computational Neuroscience. Molecular and Cellular Neurobiology Course, University of Coimbra, Portugal, November 2008
- Multi-Agent based simulation of Axon Guidance. Cognitive Media Systems Winter Meeting, University of Coimbra, Portugal, February 2008
- Web log mining and human cognition walking together. Artificial Intelligence Lab Winter Meeting, University of Coimbra, Portugal, December 2006

<!--<center>
  <style>.embed-container { position: relative; margin-bottom: -50px; padding-bottom: 50%; height: 0; overflow: hidden; max-width: 75%; max-height: 85%;} .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 85%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/JB7jSFeVz1U' frameborder='0' allowfullscreen></iframe></div>
<iframe width="75%" height="315" src="https://www.youtube.com/embed/7SXjI7zrluA" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</center> -->


<hr>
{% include footer.html %}