---
title: Neural & ML Group
permalink: /research/
---

### Brain-wide credit assignment

We are at an exciting turning point in neuroscience. New technologies now allow us to measure and control neural activity and behaviour with unprecedented detail (Landhuis et al. 2017, Lauer et al. 2021). At the same time new theoretical frameworks are starting to reveal how rich behaviours arise from synaptic, circuit and systems computations (Richards et al. 2019). In our group we are contributing directly to the latter by aiming to understand how animals learn. To this end we are developing a new generation of computational models of brain function inspired by machine learning. We focus on understanding how a given behavioural outcome ultimately leads to credit being assigned to trillions of synapses across multiple brain areas – credit assignment problem (Fig. 1a). We believe that in order to have an unified understanding of how we learn to produce adaptible behaviours it is important to jointly study the contribution of (at least) three different systems (Fig. 1b): (i) cortical circuits, (ii) neuromodulation and (iii) subcortical facilitation.

<div class="list-item-people" style="width: 70%">
    <p class="list-post-title">
      <center>
        <span style="display: block; margin-bottom: 0em; margin-top: 0em"><img class='img-responsive center-block' src="/images/research/brainwideCA.png" width="95%" height="95%"/></span>
        <b>Figure 1: Three key dimensions for credit assignment in the cortex.</b> (a) Learning requires the sensory stimuli to be associated with specific behaviours. For successful learning the brain should assign credit to trillions of synapses given behavioural outcomes – synaptic credit assignment problem. (b) We propose that it is critical to jointly study how (i) neocortical circuits (gray), (ii) subcortical systems (green) and (iii) neuromodulation (orange) shape credit assignment to make substantial progress in our understanding of how animals learn naturalistic and complex tasks. This research program is closely guided by both machine learning and experimental findings.
        </center>      
      </p>    
   </div>

<hr>

#### `Cortical circuits for efficient credit assignment`
<div class="content list people" style="text-align: left;">
  
   <div class="list-item-people" style="width: 80%" >
      <p class="list-post-title" markdown="1">
         	My previous work proposed that synapses themselves do credit assignment to reach a desired target response (*Costa et al. 2015, *Costa et al. 2017a, **Llera-Montero et al. 2019).  However, it remained unclear how these synaptic modifications may be linked to behaviour. Growing evidence suggests that deep learning (a branch of AI) can be used as a framework to understand how behaviour ultimately leads to synaptic credit assignment across the cortex (*Richards et al. 2019). We have proposed that specific cortical circuits motifs can implement common deep learning algorithms important for credit assignment (*Costa et al. 2017b, *Sacramento et al. 2018). We introduced a biologically plausible computational model of how excitatory and a subtype of inhibitory neurons jointly approximate the error backpropagation algorithm across multiple cortical areas (*Sacramento et al. 2018). However, this model provides a poor approximation of the backprop algorithm. Recently, we have started developing the first backprop-like model that is highly efficient at learning while being consistent with existing experimental observations of cortical excitatory-inhibitory circuits (Greedy et al. 2022).
          <br>
          However, fundamental issues remain open. For example, current backprop-like models still rely on a supervisory teaching signal and do not consider other important elements of cortical circuits. Building on our work and inspired by recent deep learning developments (Burda et al. 2019) we are developing a novel unsupervised cortical credit assignment theory in which pyramidal cells across different cortical layers are jointly optimised (Fig. 1b). This framework will be tested in unsupervised tasks and contrasted with recent experimental observations (Attinger et al. 2017, Jordan and Keller 2020).
       </p>
    </div>
</div>
<br>

#### `Neuromodulation of cortical credit assignment`
<div class="content list people" style="text-align: left;">
  
   <div class="list-item-people" style="width: 80%" >
      <p class="list-post-title" markdown="1">
          Neuromodulation of cortical circuits is crucial for establishing the link with behavioural outcomes needed for credit assignment. Dopaminergic neuromodulation (Fig. 1b) is the natural candidate for the reward teaching signals needed for cortical credit assignment. In order to better compare our cortical credit assignment models with experimental observations we will extend the model with reward prediction errors (e.g. using Q-learning) as commonly used in deep reinforcement learning (Mnih et al. 2015).
          <br>
          Cholinergic neuromodulation is also critical for learning (Fig. 1b). Cholinergic fibres project widely across the brain, which makes them well-placed to control credit assignment throughout the brain. We are currently developing a computational theory in which the cholinergic system adapts to the statistics of learning in cortical circuits closely mimicking adaptive deep learning rules (Filipovica, Nejad et al. Cosyne 2022,2023). This line of work raises several exciting observations. It not only proposes how the cholinergic system speeds up credit assignment efficiently throughout the cortex, but it also increases neural network robustness to perturbations. These two properties provide the first theoretical explanation for why cholinergic deficits have been widely implicated in cognitive decline in a range of conditions such as dementia, aging and more recently injury (Filipovica, Nejad et al. Cosyne 2022,2023). We will build on these insights to help develop strategies with which to rescue the brain during cholinergic malfunction.
       </p>
    </div>
</div>
<br>


#### `Subcortical regions as facilitators of cortical credit assignment`
<div class="content list people" style="text-align: left;">
  
   <div class="list-item-people" style="width: 80%" >
      <p class="list-post-title" markdown="1">
          The big brain (cerebral cortex) is massively expanded in humans relative to other mammals but intriguingly the mini brain (cerebellum) has kept pace with this expansion, suggesting that the two structures might work in tandem to effectively drive behaviour. Growing evidence in both animal and human literature highlights the importance of cerebro-cerebellar interactions for motor and cognitive tasks. Yet, we do not know what the underlying principles of these interactions may be. Recently, we have introduced a novel deep learning-inspired theory (Jaderberg et al. 2017): the cerebellum provides the cerebrum with task-specific feedback estimations which facilitates cerebral credit assignment, and therefore behaviour (**Pemberton et al. 2021). This model proposes an explanation for behavioural and learning deficits observed in cerebellar patients across a range of sensorimotor and cognitive tasks (**Boven et al. 2022). 
          Another alternative for cortico-cerebellar interactions is for the cerebellum to drive cortical dynamics directly, which explains a wide range of recent experimental findings with interesting functional (**Pemberton et al. 2022). Our work raises exciting research directions. We have so far focused on a model that closely resembles AI algorithms. Next, we will incorporate into the model additional biological constraints, which will allow us to study their computational purpose and make further predictions to be tested experimentally.
          <br>
          The hippocampus is another brain region that is fundamental for learning (Fig. 1b). In collaboration with the Ciocchi lab we have used data science methods (Kobak et al. 2016) to analyse hippocampal neuronal activity, revealing how the hippocampus is involved in learning of continually interleaved tasks, a process critical for lifelong credit assignment (Ciocchi et al. 2015, **Mohinta et al. in prep.). Currently we are using deep reinforcement learning models inspired by the hippocampal circuitry to demonstrate that: (i) these algorithms can capture hippocampal mediated- behaviour and neuronal representations and (ii) that hippocampal circuitry supports continual learning which (iii) generalises to novel situations. In the long-term we aim to adapt this modelling frameworks developed for studying how the hippocampus might support neocortical credit assignment by providing long-term predictions (Miller et al. 2017 and Olafsdottir et al. 2018).
       </p>
    </div>
</div>
<br>




<hr>
{% include footer.html %}