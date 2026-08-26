## Selected Projects

<h3 style="padding-bottom:0; margin-bottom:0.3em;">Foundation Model Transfer Learning for Whole Slide Image Screening</h3>
<p style="margin-top:0; color:#555; font-size:0.93em;"><em>Seoul National University Hospital, BMI Lab · Nov. 2025 – Feb. 2026</em></p>

Developed a screening model that automatically filters out normal cases in large-scale slide review, based on transfer learning from pathology foundation models. Used the **TANGLE** (CVPR 2024) pan-cancer pretrained encoder (UNI + ABMIL) as a frozen feature extractor with a lightweight MLP classifier, demonstrating that high-sensitivity screening is achievable from a small fraction of the training data.

---

<h3 style="padding-bottom:0; margin-bottom:0.3em;">ROI Segmentation in IHC Whole Slide Images</h3>
<p style="margin-top:0; color:#555; font-size:0.93em;"><em>Seoul National University Hospital, BMI Lab · Sep. 2025 – Nov. 2025</em></p>

Developed an ROI segmentation model for IHC-stained WSIs as a preprocessing step for downstream quantitative analysis. Found that a U-Net baseline (WSI Dice 0.78) relied on staining color rather than morphological features. Applied transfer learning with **HEST-1k** (NeurIPS 2024) fine-tuned DeepLabV3 weights, combined with Stratified K-Fold and a 4-level color augmentation ablation study, achieving a final **WSI Dice of 0.95**.

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
