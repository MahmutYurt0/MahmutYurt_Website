+++
title = "Image Synthesis in Multi-Contrast MRI with Generative Adversarial Networks"
date = 2019-01-01
authors = ["Salman Ul Hassan Dar", "Mahmut Yurt", "Levent Karacan", "Aykut Erdem", "Erkut Erdem", "Tolga Cukur" ]
publication_types = ["2"]
abstract = "Acquiring images of the same anatomy with multiple different contrasts increases the diversity of diagnostic information available in an MR exam. Yet, the scan time limitations may prohibit the acquisition of certain contrasts, and some contrasts may be corrupted by noise and artifacts. In such cases, the ability to synthesize unacquired or corrupted contrasts can improve diagnostic utility. For multi-contrast synthesis, the current methods learn a nonlinear intensity transformation between the source and target images, either via nonlinear regression or deterministic neural networks. These methods can, in turn, suffer from the loss of structural details in synthesized images. Here, in this paper, we propose a new approach for multi-contrast MRI synthesis based on conditional generative adversarial networks. The proposed approach preserves intermediate-to-high frequency details via an adversarial loss, and it offers enhanced synthesis performance via pixel-wise and perceptual losses for registered multi-contrast images and a cycle-consistency loss for unregistered images. Information from neighboring cross-sections are utilized to further improve synthesis quality. Demonstrations on T1- and T2- weighted images from healthy subjects and patients clearly indicate the superior performance of the proposed approach compared to the previous state-of-the-art methods. Our synthesis approach can help improve the quality and versatility of the multi-contrast MRI exams without the need for prolonged or repeated examinations."
selected = true
publication = "In *IEEE Transactions on Medical Imaging*."
publication_short = "In *Tran. Med. Im.*"
url_code = "https://github.com/MahmutYurt0/pGAN-cGAN"
+++
