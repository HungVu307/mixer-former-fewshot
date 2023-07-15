# MixerFormer-CovaMnet-A-New-Few-shot-Learning-Model-for-Bearing-Fault-Diagnosis
CWRU Dataset:
HUST-Bearing Dataset:
## Abstract
  Deep inside the electrical machine, bearings are
a delicate and easily injured component. Consequently, identi-
fying bearing failures is a highly informative and crucial area.
Instead of using manual methods, deep learning models were
applied to diagnose bearing failures from abnormal signals
returned from electrical machines. However, the weakness
of modern end-to-end models is that they require a large
amount of data to train in order to give highly accurate
diagnostic results. Some studies have shown that Few-shot
models are very suitable for diagnosis under limited data
conditions, but few-shot models require many steps to make
the diagnosis. Therefore, to overcome those disadvantages,
the Mixer-former CovaMnet model is proposed. This is a
few-shot training model but only needs 1 stage to diagnose
the fault instead of more than 2 stages like other few-shot
models. On the Case Western Reverse University (CWRU)
and HUST-Bearing datasets, two open-access datasets, several
experiments and ablation investigations were performed. The
results demonstrate that the proposed model outperforms other
modern deep learning models when there is limited data
available. In addition, this model still satisfies the requirements
and produces excellent results when trained with a significant
quantity of data.
## Our contributions
  Proposing a new architecture for identifying bearing
faults. The end-to-end few-shot model that we’ve sug-
gested is one that uses a covariance matrix to as-
sess class correlation. When offering extremely high
accuracy in low data settings, our unique approach
has eliminated the drawbacks of contemporary deep
learning techniques. Additionally, it is an end-to-end
model, which eliminates the complexity issue with
previous few-shot models.
  We have used the multi-head self-attention (MHSA)
mechanism to diagnose bearing faults in electrical
machines after realizing its usefulness in the field of
natural language processing (NLP). Because images
that are converted to spectrum form frequently hold
a lot of information and the data is not diverse, it
is challenging to establish an appropriate diagnosis
after the input signal has been converted to spectral
form, especially in low data situations. By helping to
concentrate on the most crucial information, MHSA
improves the model’s effectiveness. Additionally, we
show this in the ablation trial.
  These results are excellent with testing on two datasets,
Case Western Reverse University and HUST-Bearing,
especially in the lack of data circumstance. With
CWRU, for instance, our model outperforms conven-
tional models with less than 93% accuracy and up to
95.61% percent accuracy with just 60 training samples.
## Results
# Citation
