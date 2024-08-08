The suggested project seeks to address the issue of voice enhancement systems’ highly non-
stationary noise settings. Non-stationary noise is noise whose characteristics are continually

changing, making it challenging for conventional noise-estimation algorithms to efficiently
lessen its impact on speech signals.
The suggested technique uses time and frequency dependent smoothing parameters to update
the noise estimate depending on the likelihood of a signal in each frequency bin to address
this issue. This is done by calculating the noisy speech power spectrum’s ratio to its local

minimum. This ratio is updated continually by averaging previous noisy speech power spec-
trum values with a look-ahead factor. As a result, the local minimum estimation approach can

swiftly adapt to situations with extremely non-stationary noise.
Formal listening tests of the proposed approach have revealed that, when incorporated into
speech improvement systems, it outperforms alternative noise-estimation techniques. This

shows that the algorithm significantly improves speech signals in contexts with extremely non-
stationary noise, when conventional algorithms might not succeed in producing good results.

This project is significant because it deals with a pressing problem in voice augmentation sys-
tems. Real-world applications frequently involve non-stationary noise environments, and the

suggested technique effectively addresses this issue. The algorithm is particularly beneficial

in contexts where noise characteristics might fluctuate considerably over short time scales be-
cause of its ability to adapt fast to changing noise characteristics.

The suggested approach is also easily adaptable to different applications because it is founded
on sound signal processing concepts. It could be applied to a variety of systems, including
voice assistants, teleconferencing systems, and hearing aids, that need noise estimation and
speech amplification.
The suggested approach makes a substantial contribution to the fields of noise estimation and

voice enhancement overall. It is a useful tool for a variety of applications due to its effec-
tiveness in dealing with highly non-stationary noise conditions as well as its adaptability and
portability.
