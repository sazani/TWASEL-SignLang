# TWASEL-SignLang
Adaptive Multi-Stream Pose Fusion for Continuous Sign Language Recognition
# Abstract
Continuous Sign Language Recognition (CSLR) remains challenging due to complex spatio-temporal dependencies across multiple articulators such as the body, hands, and facial expressions. In this paper, we propose a region-aware multi-stream architecture that explicitly models these components through dedicated encoders for body, left-hand, right-hand, and face keypoints. Each stream captures region-specific motion dynamics and is integrated using a learned gating fusion mechanism that adaptively combines complementary cues across modalities. To effectively model long-range temporal dependencies, the fused representations are processed using a six-block Conformer encoder, enabling joint modeling of local and global temporal context.
The model is trained using a hybrid CTC/attention objective. Evaluated on the Isharah signer-independent split, it achieves a validation Word Error Rate (WER) of 20.42\% under CTC-greedy decoding. Furthermore, autoregressive beam search decoding substantially improves recognition performance, yielding a final WER of 11.85\% on the Dev set and 16.62\% on the Test set. These results demonstrate that region-aware pose representations, combined with hybrid sequence-level supervision, provide an effective and robust framework for CSLR.
# Paper
Title: TWASEL at SignEval 2026: Adaptive Multi-Stream Pose Fusion for Continuous Sign Language Recognition
https://openaccess.thecvf.com/content/CVPR2026W/MSLR/papers/Al-Azani_TWASEL_at_SignEval_2026_Adaptive_Multi-Stream_Pose_Fusion_for_Continuous_CVPRW_2026_paper.pdf
# Cite
```bibtex
@inproceedings{al2026twasel,
  title={TWASEL at SignEval 2026: Adaptive Multi-Stream Pose Fusion for Continuous Sign Language Recognition},
  author={Al-Azani, Sadam and Nabeel, Safwan and Al Mahfood, Qasim and Mohamed, Mohanad},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  pages={10473--10480},
  year={2026}
}
```
