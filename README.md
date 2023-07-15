# MixerFormer-CovaMnet-A-New-Few-shot-Learning-Model-for-Bearing-Fault-Diagnosis
CWRU Dataset: [CWRU][https://onedrive.live.com/?authkey=%21ABjTfwuf9JDxJGg&id=C42A7BAEE78840DE%21421&cid=C42A7BAEE78840DE&parId=root&parQt=sharedby&o=OneUp]
HUST-Bearing Dataset: [HUST-Bearing][https://data.mendeley.com/datasets/cbv7jyx4p9/2]
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
![image](https://github.com/VuManhHung307201/MixerFormer-CovaMnet-A-New-Few-shot-Learning-Model-for-Bearing-Fault-Diagnosis/assets/106971509/97786db3-b46b-4f08-9c15-96cd3bc987a9)
![image](https://github.com/VuManhHung307201/MixerFormer-CovaMnet-A-New-Few-shot-Learning-Model-for-Bearing-Fault-Diagnosis/assets/106971509/a3d714bf-3cbe-4268-a435-f447b95dd835)
![image](https://github.com/VuManhHung307201/MixerFormer-CovaMnet-A-New-Few-shot-Learning-Model-for-Bearing-Fault-Diagnosis/assets/106971509/cfb433c6-aa06-44fd-8cce-108805664729)



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
![image](https://github.com/VuManhHung307201/MixerFormer-CovaMnet-A-New-Few-shot-Learning-Model-for-Bearing-Fault-Diagnosis/assets/106971509/a582ec98-5e45-4b71-9d58-56065644fa15)

Table I has demonstrated the suggested model’s accuracy
advantage over competing models. When the amount of
training data is poor, WDCNN [26] and Conv-Mixer [12],
two well-known conventional end-to-end models, practically
fall and lack of the requisite accuracy when identifying
failures. While there are only 60 training samples, 64.93%
and 70.14%). Meanwhile, few-shot models show better
performance when training with small data, which is also
shown in [14]. However, although Siamese model [27]
achieves 86.12% accuracy (5 shots), it is complicated when
it requires 2 stages to diagnose. Our proposed model both
improves the accuracy when reaching 95.61% (5 shots) and
solves the problem of Siamese when our proposed model is
an end-to-end model, improved from CovaMnet (93,44% in
5 shots) and better than it

![image](https://github.com/VuManhHung307201/MixerFormer-CovaMnet-A-New-Few-shot-Learning-Model-for-Bearing-Fault-Diagnosis/assets/106971509/4fb25d76-5189-4e62-9fd6-ba20cb5aebcf)

  Table II shows the superiority of the proposed model
under different training data conditions. With only 1% of
the training samples, the proposed model gave an accuracy
of 80.01% (higher than Lenet, only 70.30%). Even with
only 5% of the total training samples, Our Mixer-former
CovaMNet outperformed all the training models with 100%
of the samples reported in the table. The suggested model
achieves 100% accuracy for all training data, something no
other model has been documented to be able to do. Thus,
the Few-shot end-to-end model has solved the problem of
data limitation in modern deep learning models. With good
results on both CWRU and HUST-Bearing data sets, the
proposed model has demonstrated outstanding performance
in low data conditions, which is consistent with reality in
diagnosing bearing failure. In addition, to demonstrate the
effectiveness of using the Multi-head self-attention mech-
anism (MHSA) as presented in III-C, Table III shows the
comparison in the ablation study in both CWRU and HUST-
Bearing.

![image](https://github.com/VuManhHung307201/MixerFormer-CovaMnet-A-New-Few-shot-Learning-Model-for-Bearing-Fault-Diagnosis/assets/106971509/4181d152-218e-4eaf-9ee3-eff339fba8ad)

  The results in Table III show the effectiveness of using
the proposed MHSA structure in low data conditions. With
CWRU, the results show that when training with 5 shots,
the accuracy in 60 training samples is 94.12%, which is
not as good as when having MHSA with 95.61%. Same
with HUST-Bearing in training condition with 1% of total
training samples. The result with MHSA is 80.10%, better
than 78.26% without. This shows the effectiveness of the
MHSA mechanism in the condition of little data, helping
the model focus on special and distinctive features, helping
the model increase the accuracy of classification.

# Citation
