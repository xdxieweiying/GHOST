# Guided Hybrid Quantization for Object detection in Multimodal Remote Sensing Imagery via One-to-one Self-teaching
**Abstract：** <br />
Considering the computation complexity, we propose a Guided Hybrid Quantization with One-to-one Self-Teaching (GHOST}) framework. More concretely, we first design a structure called guided quantization self-distillation (GQSD), which is an innovative idea for realizing lightweight through the synergy of quantization and distillation. The training process of the quantization model is guided by its full-precision model, which is time-saving and cost-saving without preparing a huge pre-trained model in advance. Second, we put forward a hybrid quantization (HQ) module to obtain the optimal bit width automatically under a constrained condition where a threshold for distribution distance between the center and samples is applied in the weight value search space. Third, in order to improve information transformation, we propose a one-to-one self-teaching (OST) module to give the student network a ability of self-judgment. A switch control machine (SCM) builds a bridge between the student network and teacher network in the same location to help the teacher to reduce wrong guidance and impart vital knowledge to the student. This distillation method allows a model to learn from itself and gain substantial improvement without any additional supervision. Extensive experiments on a multimodal dataset (VEDAI) and single-modality datasets (DOTA, NWPU, and DIOR) show that object detection based on GHOST outperforms the existing detectors. The tiny parameters (<9.7 MB) and Bit-Operations (BOPs) (<2158 G) compared with any remote sensing-based, lightweight or distillation-based algorithms demonstrate the superiority in the lightweight design domain. Our code and model will be released at this https URL. <br />
**Code & Model:** https://github.com/icey-zhang/GHOST <br />
**Paper:** https://doi.org/10.48550/arXiv.2301.00131
<br />
If our code is helpful to you, please cite:
```
@misc{zhang2022guided,
      title={Guided Hybrid Quantization for Object detection in Multimodal Remote Sensing Imagery via One-to-one Self-teaching}, 
      author={Jiaqing Zhang and Jie Lei and Weiying Xie and Yunsong Li and Xiuping Jia},
      year={2022},
      eprint={2301.00131},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
