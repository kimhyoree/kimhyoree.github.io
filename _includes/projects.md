## Selected Projects

<h3 style="padding-bottom:0; margin-bottom:0.3em;">Few-Shot Hepatotoxicity Classification for Toxicologic Screening</h3>
<p style="margin-top:0; color:#555; font-size:0.93em;"><em>Seoul National University Hospital, BMI Lab · Nov. 2025 – Feb. 2026</em></p>

Led an industry–academia collaboration with medical AI company SPASS. In drug development, ~90% of rat liver tissue slides are normal, yet all require exhaustive manual review. Developed a negative screening model to automatically filter normal slides. Leveraged **TANGLE** (CVPR 2024) Pan-Cancer pretrained encoder (UNI + ABMIL) as a frozen feature extractor, training only an MLP classifier for hepatotoxicity classification. Achieved **AUROC 0.909** and **Recall 0.963** using only 15% of training data (935 slides), outperforming fully trained ABMIL from scratch.

---

<h3 style="padding-bottom:0; margin-bottom:0.3em;">Endometrium ROI Segmentation in IHC Whole Slide Images</h3>
<p style="margin-top:0; color:#555; font-size:0.93em;"><em>Seoul National University Hospital, BMI Lab · Sep. 2025 – Nov. 2025</em></p>

Developed an endometrium ROI segmentation model in IHC-stained WSIs for automated immune cell counting. Identified that U-Net baseline (WSI Dice 0.78) relied on staining color rather than morphological features. Applied transfer learning with **HEST-1k** (NeurIPS 2024) fine-tuned DeepLabV3 weights, combined with Stratified K-Fold and a 4-level Color Augmentation ablation study, achieving a final **WSI Dice of 0.95**.

---

<h3 style="padding-bottom:0; margin-bottom:0.3em;">Zero-Shot Health Insight Generation from Tongue Images using MedGemma</h3>
<p style="margin-top:0; color:#555; font-size:0.93em;"><em>Feb. 2025 – Jun. 2025</em></p>

Built a prototype using the public TongueDx dataset with **MedGemma-4B-IT** in a zero-shot setting to test whether a pretrained multimodal model can infer health-related cues from minimal inputs. Combined tongue images, age/sex, and brief captions to generate template-conformant reports.

---

<h3 style="padding-bottom:0; margin-bottom:0.3em;">Breast Cancer Classification Enhancement Using Protein Markers</h3>
<p style="margin-top:0; color:#555; font-size:0.93em;"><em>Korea Institute of Science and Technology (KIST) · Sep. 2023 – Dec. 2023</em></p>

Improved breast cancer classification in MRI images through a **Vision Transformer** model incorporating multi-marker labels (ER, PR, HER2, Ki-67) alongside cancer presence. Demonstrated the feasibility of non-invasively identifying protein markers using MRI.

---

<h3 style="padding-bottom:0; margin-bottom:0.3em;">Improving HCC Diagnostic Precision in CT Using the UNETR Model</h3>
<p style="margin-top:0; color:#555; font-size:0.93em;"><em>Korea Institute of Science and Technology (KIST) · Jun. 2023 – Aug. 2023</em></p>

Enhanced detection performance of HCC in CT scans by adjusting HCC contrast through aorta contrast referencing with the transformer-based **UNETR** model, enabling more precise HCC detection.
