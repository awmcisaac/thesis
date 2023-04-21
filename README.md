# LCT Thesis - Temporal Reasoning in Language and Vision Models

---

Title: Temporal Reasoning in Vision and Language Models

Abstract: This thesis will evaluate the performance of vision and language
models on the task of video question answering, with a particular focus on the
ability to reason across time. We will start by inspecting the STAR dataset
[1], which consists of carefully controlled sequences of frames and questions
automatically generated with the purpose of evaluating models' ability to
perform temporal reasoning. We will analyse one state of the art model, Merlot
Reserve [2], to understand the results reported by the authors with particular
focus on questions which require temporal reasoning, using data perturbation
methods. Current models may not be sufficiently incentivised to learn temporal
reasoning, with previous studies able to obtain strong performance on video
tasks from single frames [3]. We hypothesise that this comes in part from the
contrastive pretraining objective, as has been shown in vision and language
models for verb understanding [4] and compositional relationships [5]. To test
this, we plan to train a model with hard negatives for temporal understanding
and evaluate performance on temporal-aware video question answering datasets
[1,6].

References:
[1] Wu, B., Yu, S., Chen, Z., Tenenbaum, J. B., and Gan, C. (2021). Star: A
benchmark for situated reasoning in real-world videos. In NeurIPS. 
[2] Zellers, R., Lu, J., Lu, X., Yu, Y., Zhao, Y., Salehi, M., Kusupati, A.,
Hessel, J., Farhadi, A., and Choi, Y. (2022). Merlot reserve: Neural script
knowledge through vision and language and sound. In CVPR. 
[3] Shyamal Buch, Cristóbal Eyzaguirre, Adrien Gaidon, Jiajun Wu, Li Fei-Fei,
Juan Carlos Niebles (2022). Revisiting the "Video" in Video-Language
Understanding. In Proceedings of the IEEE/CVF Conference on Computer Vision and
Pattern Recognition (CVPR), 2917-2927 
[4] Momeni, L., Caron, M., Nagrani, A., Zisserman, A., & Schmid, C. (2023).
Verbs in Action: Improving verb understanding in video-language models. arXiv
preprint arXiv:2304.06708.
[5] Yuksekgonul, M., Bianchi, F., Kalluri, P., Jurafsky, D., & Zou, J. (2022).
When and why vision-language models behave like bag-of-words models, and what
to do about it?. arXiv preprint arXiv:2210.01936.
[6] Xiao, J., Shang, X., Yao, A., & Chua, T. (2021). NExT-QA: Next Phase of
Question-Answering to Explaining Temporal Actions. 2021 IEEE/CVF Conference on
Computer Vision and Pattern Recognition (CVPR), 9772-9781.
