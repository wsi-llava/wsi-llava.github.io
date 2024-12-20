---
layout: project_page
permalink: /
title: WSI-LLaVA：A Multimodal Large Language Model for Whole Slide Image
authors:
    Yuci Liang*¹'², Xinheng Lyu*², Meidan Ding¹, Wenting Chen³'⁵, Jipeng Zhang⁹, Yuexiang Ren⁶'⁷, Xiangjian He², Song Wu¹'⁸, Sen Yang⁴, Xiyue Wang⁴, Xiaohan Xing⁴, Linlin Shen†'¹
affiliations:
    ¹Shenzhen University
    ²University of Nottingham Ningbo China
    ³City University of Hong Kong
    ⁴Stanford University
    ⁵Massachusetts General Hospital and Harvard Medical School
    ⁶Nanchang University
    ⁷The First Affiliated Hospital of Nanchang University
    ⁸South China Hospital affiliated to Shenzhen University
    ⁹Hong Kong University of Science and Technology
    <br>
    *Equal Contributors<br>
    # †Corresponding to: your-email@domain.com
paper: https://arxiv.org/abs/2412.02141
video: https://www.youtube.com/results?search_query=turing+machine
code: https://github.com/XinhengLyu/WSI-LLaVA
data: https://huggingface.co/
# title: >
#   <img src="../static/image/wsi-logo.png" alt="WSI Logo" style="height: 45px; vertical-align: middle; margin-right: 10px;">
#   WSI-LLaVA: A Multimodal Large Language Model for Whole Slide Image

# authors:
#     A. M. Turing
# affiliations:
#     King's College, Cambridge
# paper: https://www.cs.virginia.edu/~robins/Turing_Paper_1936.pdf
# zhihu: https://www.youtube.com/results?search_query=turing+machine
# code: https://github.com/topics/turing-machines
# data: https://huggingface.co/docs/datasets
---

<style>
    .center-box {
        display: flex;
        flex-direction: column;
        align-items: center; /* 水平居中 */
        justify-content: center; /* 垂直居中 */
        text-align: center;
        border: 2px solid #ccc; /* 边框 */
        padding: 20px; /* 内边距 */
        margin: 20px auto; /* 外边距，使其水平居中 */
        width: fit-content; /* 根据内容自适应宽度 */
        background-color: #ffffff; /* 背景颜色设置为白色 */
        border-radius: 8px; /* 圆角 */
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* 阴影 */
    }
    .center-box img {
        max-width: 100%; /* 图片最大宽度 */
        height: auto; /* 保持图片比例 */
    }
    .key-point {
    color: #007BFF; /* 设置圆点的颜色，蓝色为例 */
    font-size: 1.2rem; /* 圆点的大小 */
    margin-right: 10px; /* 圆点与文本的间距 */
    vertical-align: middle; /* 对齐文本中心 */
    }
    .description {
        margin-top: 15px;
        font-size: 16px; /* 文本字体大小 */
        line-height: 1.6;
        color: #333; /* 深灰色字体 */
        text-align: justify; /* 文字两端对齐 */
        text-indent: 2em; /* 首行缩进两格 */
    }
    .description-not-margin {
        
        font-size: 16px; /* 文本字体大小 */
        line-height: 1.6;
        color: #333; /* 深灰色字体 */
        text-align: justify; /* 文字两端对齐 */
        text-indent: 2em; /* 首行缩进两格 */
    }
        .description-not-margin-indent {
        
        font-size: 16px; /* 文本字体大小 */
        line-height: 1.6;
        color: #333; /* 深灰色字体 */
        text-align: justify; /* 文字两端对齐 */
        text-indent: 2em; /* 首行缩进两格 */
    }

    .bold-text {
        font-weight: bold; /* 加粗样式 */
    }
    /* 在 "WSI-LLaVA" 前加图标，图标大小匹配文本 */
    .description span.wsi-lava::before {
        content: ''; /* 不需要直接使用 URL，使用 background-image */
        background-image: url('./static/image/wsi-logo.png'); /* 图标路径 */
        background-size: 20px 20px; /* 设置背景图标大小为 40px */
        height: 20px; /* 设置高度为 40px */
        width: 20px; /* 设置宽度为 40px */
        display: inline-block; /* 让其表现为行内块元素 */
        margin-right: 0px; /* 图标与文本之间的间距 */
        vertical-align: middle; /* 确保与文本垂直对齐 */
    }
     .image-container {
            display: flex;
            justify-content: space-around; /* 调整间距，可以改为 center、flex-start 等 */
            align-items: center;
        }
        .image-container img {
            width:150px; /* 统一宽度 */
            height: 200px; /* 统一高度 */
            object-fit: contain; /* 保持图片比例且填充整个框 */
            margin: 0 10px; /* 设置图片之间的间距 */
        }
</style>

<div class="center-box">
    <img src="./static/image/radar6.png" alt="Radar Chart">
    <p class="description">
        In the radar chart displaying <strong>WSI-Precision metrics</strong>, <span class="wsi-lava">WSI-LLaVA</span> (our model) dominates with broader coverage and higher peaks in most diagnostic categories, <strong>particularly excelling in “Specific Feature Description,” “Staging," and “Prognosis."</strong> This suggests an excellent ability to accurately identify and describe critical pathological features and outcomes. Meanwhile, models like GPT-4o show considerably lower precision, particularly in detailed descriptions, which may limit their utility in nuanced diagnostic scenarios.
    </p>
    <p class="description-not-margin">
        <strong>WSI-Relevance radar</strong> reveals that <span class="wsi-lava">WSI-LLaVA</span> also leads in relevance, with <strong>outstanding performance in “Staging” and “Treatment Recommendations,” </strong>underscoring its capability to deliver clinically pertinent information that aids in treatment planning and prognosis estimation. In contrast, while GPT-4o and WSI-VQA provide valuable insights in specific areas such as “Prognosis” and “Regional Structure Description,” they exhibit a balanced but generally lower relevance compared to our model, indicating a need for targeted improvements to enhance their practical application in clinical settings.
    </p>
</div>






<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-full" style="margin-top: 20px;">
        <h2 style="font-size: 1.8rem; font-weight: bold; margin-bottom: 20px; text-align: center; color: black;">Key contributions</h2>
        <div class="content has-text-justified" style="text-indent: 2em;">
                <p class="description">
                <span class="key-point">•</span> We introduce <strong>WSI-Bench</strong>, <strong>the first large-scale morphology-aware benchmark</strong> for gigapixel WSI understanding and evaluation, encompassing <strong>180k VQA pairs</strong> from <strong>9,850 WSIs</strong> across <strong>30 cancer types</strong>. This benchmark uniquely emphasizes morphological observations in evaluating WSI-level MLLMs.
            </p>
            <p class="description">
                <span class="key-point">•</span> We propose <span class="wsi-lava"></span><strong>WSI-LLaVA</strong>, a novel framework for gigapixel WSI analysis that bridges the cross-modal gap between WSIs and textual descriptions. The framework introduces a <strong>three-stage training approach</strong>: WSI-text alignment, feature space alignment, and task-specific instruction tuning.
            </p>
            <p class="description">
                <span class="key-point">•</span> We develop <strong>WSI-specific evaluation metrics</strong> (<strong>WSI-Precision</strong> and <strong>WSI-Relevance</strong>) that provide a more accurate assessment of model performance in pathological contexts, addressing the limitations of traditional NLU metrics by verifying claim accuracy and response relevance.
            </p>
            <p class="description">
                <span class="key-point">•</span> Through comprehensive experiments, we demonstrate <strong>WSI-LLaVA’s superior performance</strong> compared to existing models, establishing a clear correlation between morphological capabilities and diagnostic accuracy.
            </p>
        </div>
    </div>
</div>

<h2 style="font-size: 1.8rem; font-weight: bold; margin-bottom: 20px; text-align: center; color: black;">WSI-Bench</h2>

<div class="center-box">

  <img src="./static/image/wsi-beach.png" alt="wsi-beach">
    <p class="description" style="margin-bottom: 10px;">
        In <strong>clinical practice, pathologists rely heavily on morphological features</strong>, particularly tissue and cellular structural abnormalities, for diagnosis. <strong>Current WSI models overlook these critical details</strong>, impacting diagnostic accuracy.
    </p>
    <p class="description" style="margin-top: 0; margin-bottom: 10px;">
        We introduce <strong>WSI-Bench</strong>, a <strong>morphology-aware</strong> benchmark for gigapixel WSI evaluation across <strong>3 pathological capabilities</strong> and <strong>11 tasks</strong>, which encompasses about <strong>180k VQA pairs</strong> from <strong>9,850 WSIs</strong> across <strong>30 cancer types</strong>, sourced from <strong>8,368 patients</strong>.
    </p>

</div>

<h2 style="font-size: 1.8rem; font-weight: bold; margin-bottom: 20px; text-align: center; color: black;">How to Construct WSI-Bench</h2>
<div class="center-box">

  <img src="./static/image/build_dataset_new.png" alt="build_dataset">
    <p class="description" style="font-size: 1.1rem; line-height: 1.6; color: #333; text-align: justify; margin-bottom: 15px;">
    <strong>Two-step process for constructing WSI-Bench:</strong> <br>
      <span style="display: inline-block; margin-left:35px;">Step 1: <strong>Remove gross descriptions and IHC results</strong> from pathology reports, retaining morphological descriptions and diagnostic conclusions, then generate enriched descriptions through <strong>reverse engineering.</strong></span> <br>
      <span style="display: inline-block; margin-left: 35px;">Step&nbsp;2: Construct VQA pairs from the <strong>refined reports</strong> to support comprehensive pathological tasks, enabling diverse analytical capabilities.</span>

</p>
   
</div>

<div style="text-align: center; display: flex; align-items: center; justify-content: center; margin-bottom: 20px;">
  <img src="./static/image/wsi-logo.png" alt="WSI Logo" style="height: 40px; margin-right: 10px;">
  <h2 style="font-size: 1.8rem; font-weight: bold; color: black; margin: 0;">WSI-LLaVA</h2>
</div>


<div class="center-box">
  <img src="./static/image/architecture_new4.png" alt="WSI-LLaVA">
<p class="description" style="margin-bottom: 10px;">
        <strong>a. Model Architecture:</strong> The framework comprises three key components: <strong>the WSI Encoder</strong>, a projection layer, and a large language model.
    </p>
    <p class="description" style="margin-top: 0; margin-bottom: 10px;">
        <strong>b. Training Strategy:</strong> <span class="wsi-lava">WSI-LLaVA </span>adopts an innovative <strong>three-stage training approach</strong> for gigapixel WSI analysis, which includes:
        <ol style="margin: 0; margin-left: 40px; padding-left: 20px; text-align: left;">
            <li style="margin: 0; padding: 0; text-align: left;">
                <strong>WSI-Text Alignment:</strong> Capturing pathology-relevant image features.
            </li>
            <li style="margin: 0; padding: 0; text-align: left;">
                <strong>Feature Space Alignment:</strong> Mapping visual features of pathology images to the same feature space as pathology report text.
            </li>
            <li style="margin: 0; padding: 0; text-align: left;">
                <strong>Task-Specific Instruction Tuning:</strong> Vision instruction fine-tuning in the pathology domain.
            </li>
</ol>
  </p>

   
</div>

<h2 style="font-size: 1.8rem; font-weight: bold; margin-bottom: 20px; text-align: center; color: black;">WSI-Metric</h2>
<div class="center-box">

  <img src="./static/image/metric.png" alt="metric">
    <p class="description" style="font-size: 1.1rem; line-height: 1.6; color: #333; text-align: justify; margin-bottom: 15px;">
    While Natural Language Understanding (NLU) metrics are commonly used to evaluate medical language tasks, they fall short in accurately assessing performance due to pathology’s complex and often similar terminology. To address this limitation, we introduce <strong>two specialized WSI metrics</strong>: 
    <ul style="margin: 0; margin-left: 40px; padding-left: 20px; text-align: left;">
            <li style="margin: 0; padding: 0; text-align: left;">
                 <strong>WSI-Precision</strong>, which verifies the accuracy of each claim derived from the ground truth against the model’s answers.
            </li>
            <li style="margin: 0; padding: 0; text-align: left;">
                <strong>WSI-Relevance</strong>, which assesses the alignment of each claim in the model’s responses with the ground truth to ensure their relevance.
            </li>
           
</ul>
   

</p>
   <img src="./static/image/fruit.png" alt="fruit">
   <p class="description" style="font-size: 1.1rem; line-height: 1.6; color: #333; text-align: justify; margin-bottom: 15px;">
       We hope this example using fruit can help you understand what WSI-Precision and WSI-Relevance are.
    </p>
</div>

<h2 style="font-size: 1.8rem; font-weight: bold; margin-bottom: 20px; text-align: center; color: black;">Experiment</h2>
<div class="center-box">
  <img src="./static/image/results.png" alt="results">
  <br>
   <img src="./static/image/table.png" alt="table">
   <img src="./static/image/example1.png" alt="example1">
    <p class="description" style="font-size: 1.1rem; line-height: 1.6; color: #333; text-align: justify; margin-bottom: 15px;">
     We collect various WSI MLLMs to evaluate on our WSIBench dataset. These include <strong>specialized models for WSI report generation</strong>, such as <strong>MI-Gen</strong> and<strong> Hist-Gen</strong>, as well as models <strong>designed for pathological VQA tasks</strong>, like <strong>Quilt-LLaVA</strong> and <strong>WSI-VQA</strong>. Additionally, we assess GPT-4o’s performance to evaluate a general-purpose MLLM. For models with input size constraints (e.g., QuiltLLaVA and GPT-4o), we resize the WSIs to <strong>1024 × 1024 pixels</strong> to fit within their input processing capabilities. To ensure a fair comparison, all WSI MLLMs are trained on WSI-Bench’s training set and evaluated on its test set.
</p>
   
</div>




<h2 style="font-size: 1.8rem; font-weight: bold; margin-bottom: 20px; text-align: center; color: black;">Examples of 11 tasks</h2>
<div style="text-align: center; position: relative;; margin: 0 auto;">

<!-- 固定大小框 -->
<div class="center-box" style="height: 500px; overflow: hidden; padding: 0; border: 1px solid #ddd;">
    <!-- 图片显示区域 -->
    <img id="gallery-image" src="./static/image/table5.png" alt="vision-ex" style="width: 100%; height: 100%; object-fit: contain; cursor: pointer;" onclick="imageClick(event)">

    
    <!-- 左右点击区域 -->
    <div id="left-area" style="position: absolute; left: 0; top: 0; width: 50%; height: 100%; cursor: pointer;" onclick="prevImage()">
      <div style="position: absolute; left: 10px; top: 50%; transform: translateY(-50%);">
        <i class="fas fa-chevron-left" style="font-size: 24px; color: gray;"></i>
      </div>
    </div>
    <div id="right-area" style="position: absolute; right: 0; top: 0; width: 50%; height: 100%; cursor: pointer;" onclick="nextImage()">
      <div style="position: absolute; right: 10px; top: 50%; transform: translateY(-50%);">
        <i class="fas fa-chevron-right" style="font-size: 24px; color: gray;"></i>
      </div>
    </div>
  </div>

  <div style="margin-top: 20px;">
    <div id="message" style="margin-top: 10px; font-size: 16px; color: red;"></div>
  </div>
</div>

<script src="https://kit.fontawesome.com/a076d05399.js"></script>

<script>
  const images = [
    "./static/image/table5.png",
    "./static/image/table6.png",
    "./static/image/table7.png",
    "./static/image/table8.png",
    "./static/image/table9.png",
    "./static/image/table10.png",
    "./static/image/table11.png",
    "./static/image/table12.png",
    "./static/image/table13.png",
    "./static/image/table14.png",
    "./static/image/table15.png"
  ];

  let currentIndex = 0;

  function showImage(index) {
    const imgElement = document.getElementById('gallery-image');
    imgElement.src = images[index];
    updateButtons();
  }

  function nextImage() {
    if (currentIndex < images.length - 1) {
      currentIndex++;
      showImage(currentIndex);
    } else {
      document.getElementById('message').textContent = "No more images!";
    }
  }

  function prevImage() {
    if (currentIndex > 0) {
      currentIndex--;
      showImage(currentIndex);
    } else {
      document.getElementById('message').textContent = "You are at the first image!";
    }
  }

  function imageClick(event) {
    // If click is on the left side of the image, go to the previous image
    if (event.clientX < window.innerWidth / 2) {
      prevImage();
    } else {
      nextImage();
    }
  }

  function updateButtons() {
    const messageElement = document.getElementById('message');
    messageElement.textContent = "";  // Clear the message when updating the image

    // Hide or show left/right click areas based on the current index
    if (currentIndex === 0) {
      document.getElementById('left-area').style.display = 'none';  // Hide "Previous" click area
    } else {
      document.getElementById('left-area').style.display = 'block';  // Show "Previous" click area
    }

    if (currentIndex === images.length - 1) {
      document.getElementById('right-area').style.display = 'none';  // Hide "Next" click area
    } else {
      document.getElementById('right-area').style.display = 'block';  // Show "Next" click area
    }
  }

  // Initialize
  showImage(currentIndex);
</script>



## Citation
```
@article{liang2024wsi,
  title={WSI-LLaVA: A Multimodal Large Language Model for Whole Slide Image},
  author={Liang, Yuci and Lyu, Xinheng and Ding, Meidan and Chen, Wenting and Zhang, Jipeng and Ren, Yuexiang and He, Xiangjian and Wu, Song and Yang, Sen and Wang, Xiyue and others},
  journal={arXiv preprint arXiv:2412.02141},
  year={2024}
}
```

       


<div class="image-container">
        <img src="./static/image/shenzhen.png" alt="Shenzhen">
        <img src="./static/image/nuodinghan.png" alt="Nuodinghan">
        <img src="./static/image/city.png" alt="City">
        <img src="./static/image/stand.png" alt="Stand">
        <img src="./static/image/keji.png" alt="Keji">
    </div>



