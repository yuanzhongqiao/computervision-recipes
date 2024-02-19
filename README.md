<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/microsoft/computervision-recipes/blob/staging/scenarios/media/logo_cvbp.png"><img src="https://github.com/microsoft/computervision-recipes/raw/staging/scenarios/media/logo_cvbp.png" align="right" alt="" width="300" style="max-width: 100%;"></a></p>
<div class="highlight highlight-source-diff notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-mi1"><span class="pl-mi1">+</span> Update July: Added support for action recognition and tracking</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>              in the new release v1.2.</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="+ Update July: Added support for action recognition and tracking
+              in the new release v1.2." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h1 tabindex="-1" dir="auto"><a id="user-content-computer-vision" class="anchor" aria-hidden="true" tabindex="-1" href="#computer-vision"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计算机视觉</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">近年来，我们看到计算机视觉领域取得了非凡的发展，在人脸识别、图像理解、搜索、无人机、测绘、半自动和自动驾驶汽车等领域都有应用。许多这些应用的关键部分是视觉识别任务，例如图像分类、对象检测和图像相似性。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库提供了构建计算机视觉系统的示例和最佳实践指南。该存储库的目标是构建一套全面的工具和示例，利用计算机视觉算法、神经架构和操作此类系统的最新进展。我们不是从头开始创建实现，而是借鉴现有的最先进的库，并围绕加载图像数据、优化和评估模型以及扩展到云构建其他实用程序。此外，我们在这个领域工作了多年，我们的目标是回答常见问题，指出经常观察到的陷阱，并展示如何使用云进行培训和部署。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们希望这些示例和实用程序能够显着缩短从定义业务问题到开发解决方案的体验，从而显着缩短“上市时间”。此外，示例笔记本将作为指南，并以多种语言展示最佳实践和工具的用法。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="/microsoft/computervision-recipes/blob/staging/scenarios"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些示例以Jupyter 笔记本</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和常见</font></font><a href="/microsoft/computervision-recipes/blob/staging/utils_cv"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实用函数的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">形式提供</font><font style="vertical-align: inherit;">。所有示例都使用 PyTorch 作为底层深度学习库。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-examples" class="anchor" aria-hidden="true" tabindex="-1" href="#examples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库支持各种计算机视觉场景，这些场景可以在单个图像上运行：</font></font></p>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/microsoft/computervision-recipes/blob/staging/scenarios/media/cv_overview.jpg"><img src="https://github.com/microsoft/computervision-recipes/raw/staging/scenarios/media/cv_overview.jpg" height="350" alt="一些支持的 CV 场景" style="max-width: 100%;"></a>
</p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以及以视频序列作为输入的动作识别等场景：</font></font></p>
<p align="center" dir="auto">
  <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/microsoft/computervision-recipes/blob/staging/scenarios/action_recognition/media/action_recognition2.gif" data-target="animated-image.originalLink"><img src="/microsoft/computervision-recipes/raw/staging/scenarios/action_recognition/media/action_recognition2.gif" action="" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/microsoft/computervision-recipes/blob/staging/scenarios/action_recognition/media/action_recognition2.gif" target="_blank">
          
     
</p>
<h2 tabindex="-1" dir="auto"><a id="user-content-target-audience" class="anchor" aria-hidden="true" tabindex="-1" href="#target-audience"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目标听众</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们此存储库的目标受众包括具有不同级别计算机视觉知识的数据科学家和机器学习工程师，因为我们的内容仅包含源代码并针对自定义机器学习建模。提供的实用程序和示例旨在成为现实世界视觉问题的解决方案加速器。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-getting-started" class="anchor" aria-hidden="true" tabindex="-1" href="#getting-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，导航至</font></font><a href="/microsoft/computervision-recipes/blob/staging/SETUP.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，其中列出了有关如何设置计算环境以及运行此存储库中的笔记本所需的依赖项的说明。设置环境后，导航到
</font></font><a href="/microsoft/computervision-recipes/blob/staging/scenarios"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scenarios</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件夹并开始浏览笔记本。我们建议从</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像分类</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记本开始</font><font style="vertical-align: inherit;">，因为这引入了其他场景（例如 ImageNet 上的预训练）也使用的概念。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，我们支持 Binder
 </font></font><a href="https://mybinder.org/v2/gh/PatrickBue/computervision-recipes/master?filepath=scenarios%2Fclassification%2F01_training_introduction_BINDER.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/e91e1d353a8b6acf0b42547ac3901f2c30138a3abaaa3d3c242da30b5b4f8426/68747470733a2f2f6d7962696e6465722e6f72672f62616467655f6c6f676f2e737667" alt="活页夹" data-canonical-src="https://mybinder.org/badge_logo.svg" style="max-width: 100%;"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
，只需点击此链接即可轻松在网络浏览器中尝试我们的笔记本之一。然而，Binder 是免费的，因此仅具有有限的 CPU 计算能力并且没有 GPU 支持。预计笔记本电脑的运行速度会非常慢（通过将图像分辨率降低到例如 60 像素可以在一定程度上改善这一情况，但代价是精度较低）。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-scenarios" class="anchor" aria-hidden="true" tabindex="-1" href="#scenarios"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用场景</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是此存储库中涵盖的常用计算机视觉场景的摘要。对于每个主要场景（“基础”），我们提供了有效构建您自己的模型的工具。这包括简单的任务，例如根据自己的数据微调自己的模型，到更复杂的任务，例如硬负挖掘甚至模型部署。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设想</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="/microsoft/computervision-recipes/blob/staging/scenarios/classification"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分类</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像分类是一种监督机器学习技术，用于学习和预测给定图像的类别。</font></font></td>
</tr>
<tr>
<td><a href="/microsoft/computervision-recipes/blob/staging/scenarios/similarity"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相似</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像相似度是一种计算给定图像对的相似度分数的方法。给定图像，它允许您识别给定数据集中最相似的图像。</font></font></td>
</tr>
<tr>
<td><a href="/microsoft/computervision-recipes/blob/staging/scenarios/detection"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检测</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对象检测是一种允许您检测图像中对象的边界框的技术。</font></font></td>
</tr>
<tr>
<td><a href="/microsoft/computervision-recipes/blob/staging/scenarios/keypoints"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关键点</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关键点检测可用于检测对象上的特定点。提供预训练模型来检测人体关节以进行人体姿势估计。</font></font></td>
</tr>
<tr>
<td><a href="/microsoft/computervision-recipes/blob/staging/scenarios/segmentation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分割</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像分割为图像中的每个像素分配一个类别。</font></font></td>
</tr>
<tr>
<td><a href="/microsoft/computervision-recipes/blob/staging/scenarios/action_recognition"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动作识别</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动作识别，用于识别视频/网络摄像头镜头中执行的动作（例如“跑步”、“打开瓶子”）以及各自的开始/结束时间。我们还实现了动作识别的 i3d 实现，可以在 (contrib)[contrib] 下找到。</font></font></td>
</tr>
<tr>
<td><a href="/microsoft/computervision-recipes/blob/staging/scenarios/tracking"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">追踪</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跟踪允许随着时间的推移检测和跟踪视频序列中的多个对象。</font></font></td>
</tr>
<tr>
<td><a href="/microsoft/computervision-recipes/blob/staging/contrib/crowd_counting"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人群计数</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">统计低人群密度（如小于10人）和高人群密度（如数千人）场景下的人数。</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们将支持的 CV 场景分为两个位置：(i)</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基础</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：“utils_cv”和“scenarios”文件夹中的代码和笔记本，遵循严格的编码准则，经过良好的测试和维护； (ii) </font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">contrib</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：“contrib”文件夹中的代码和其他资产，主要涵盖使用最先进方法的不太常见的 CV 场景。 “contrib”中的代码没有定期测试或维护。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-computer-vision-on-azure" class="anchor" aria-hidden="true" tabindex="-1" href="#computer-vision-on-azure"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Azure 上的计算机视觉</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，对于某些计算机视觉问题，您可能不需要构建自己的模型。相反，Azure 上存在预构建或易于定制的解决方案，不需要任何自定义编码或机器学习专业知识。我们强烈建议评估这些是否足以解决您的问题。如果这些解决方案不适用，或者这些解决方案的准确性不够，则可能需要采用更复杂且耗时的定制方法。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下 Microsoft 服务提供简单的解决方案来解决常见的计算机视觉任务：</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><a href="https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视觉服务</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
是一组预先训练的 REST API，可调用它们来进行图像标记、人脸识别、OCR、视频分析等。这些 API 开箱即用，需要最少的机器学习专业知识，但定制功能有限。请参阅各种可用演示以感受其功能（例如</font></font><a href="https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/#analyze" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计算机视觉</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。该服务可以通过 API 调用或 SDK（支持 .NET、Python、Java、Node 和 Go 语言）使用</font></font></p>
</li>
<li>
<p dir="auto"><a href="https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/home" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Custom Vision</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
是一项 SaaS 服务，用于在给定用户提供的训练集的情况下将模型训练和部署为 REST API。包括图像上传、注释和模型部署在内的所有步骤都可以使用直观的 UI 或通过 SDK（提供 .NEt、Python、Java、Node 和 Go 语言）来执行。只需最少的机器学习专业知识即可训练图像分类或对象检测模型。与使用预先训练的认知服务 API 相比，自定义视觉提供了更大的灵活性，但要求用户携带并注释自己的数据。</font></font></p>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您需要训练自己的模型，以下服务和链接提供了可能有用的其他信息。</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><a href="https://docs.microsoft.com/azure/machine-learning/?WT.mc_id=computervision-github-azureai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Azure 机器学习服务（AzureML）</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
是一项帮助用户加速机器学习模型的训练和部署的服务。虽然 AzureML Python SDK 并非特定于计算机视觉工作负载，但可用于将机器学习解决方案进行可扩展且可靠的训练以及部署到云。我们在此存储库中的多个笔记本中利用 Azure 机器学习（例如</font></font><a href="https://github.com/microsoft/computervision-recipes/blob/master/scenarios/classification/22_deployment_on_azure_kubernetes_service.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署到 Azure Kubernetes 服务</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></p>
</li>
<li>
<p dir="auto"><a href="https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/training-python-models/?WT.mc_id=computervision-github-azureai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Azure AI 参考体系结构</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
提供了一组示例（由代码支持），说明如何构建利用多个云组件的常见的面向 AI 的工作负载。虽然不是特定于计算机视觉的，但这些参考架构涵盖了多种机器学习工作负载，例如模型部署或批量评分。</font></font></p>
</li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-build-status" class="anchor" aria-hidden="true" tabindex="-1" href="#build-status"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建状态</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-azureml-testing" class="anchor" aria-hidden="true" tabindex="-1" href="#azureml-testing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AzureML 测试</font></font></h3>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建类型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分支</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地位</font></font></th>
<th></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分支</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地位</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux GPU</font></font></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">掌握</font></font></td>
<td><a href="https://dev.azure.com/best-practices/computervision/_build/latest?definitionId=41&amp;branchName=master" rel="nofollow"><img src="https://camo.githubusercontent.com/d682deb2b20740a0b7ac7475ff8f512c318ab7da7ce42d69028e415e8c303159/68747470733a2f2f6465762e617a7572652e636f6d2f626573742d7072616374696365732f636f6d7075746572766973696f6e2f5f617069732f6275696c642f7374617475732f417a7572654d4c2f414d4c2d756e69742d746573742d6c696e75782d6770753f6272616e63684e616d653d6d6173746572" alt="构建状态" data-canonical-src="https://dev.azure.com/best-practices/computervision/_apis/build/status/AzureML/AML-unit-test-linux-gpu?branchName=master" style="max-width: 100%;"></a></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分期</font></font></td>
<td><a href="https://dev.azure.com/best-practices/computervision/_build/latest?definitionId=41&amp;branchName=staging" rel="nofollow"><img src="https://camo.githubusercontent.com/ca8fb6b041d657a69a8ecb80c178816759c464b43d62bb04465cb1e03e3d4a0b/68747470733a2f2f6465762e617a7572652e636f6d2f626573742d7072616374696365732f636f6d7075746572766973696f6e2f5f617069732f6275696c642f7374617475732f417a7572654d4c2f414d4c2d756e69742d746573742d6c696e75782d6770753f6272616e63684e616d653d73746167696e67" alt="构建状态" data-canonical-src="https://dev.azure.com/best-practices/computervision/_apis/build/status/AzureML/AML-unit-test-linux-gpu?branchName=staging" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux中央处理器</font></font></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">掌握</font></font></td>
<td><a href="https://dev.azure.com/best-practices/computervision/_build/latest?definitionId=37&amp;branchName=master" rel="nofollow"><img src="https://camo.githubusercontent.com/cb4e430872f80520e767a8279cc6fad01637fe3361a9760b46f8f78cf88d80cb/68747470733a2f2f6465762e617a7572652e636f6d2f626573742d7072616374696365732f636f6d7075746572766973696f6e2f5f617069732f6275696c642f7374617475732f417a7572654d4c2f414d4c2d756e69742d746573742d6c696e75782d6370753f6272616e63684e616d653d6d6173746572" alt="构建状态" data-canonical-src="https://dev.azure.com/best-practices/computervision/_apis/build/status/AzureML/AML-unit-test-linux-cpu?branchName=master" style="max-width: 100%;"></a></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分期</font></font></td>
<td><a href="https://dev.azure.com/best-practices/computervision/_build/latest?definitionId=37&amp;branchName=staging" rel="nofollow"><img src="https://camo.githubusercontent.com/ceb581be86066eb8bb7f961fb669c86b098fe8435cc76949872dcae6ed85ac07/68747470733a2f2f6465762e617a7572652e636f6d2f626573742d7072616374696365732f636f6d7075746572766973696f6e2f5f617069732f6275696c642f7374617475732f417a7572654d4c2f414d4c2d756e69742d746573742d6c696e75782d6370753f6272616e63684e616d653d73746167696e67" alt="构建状态" data-canonical-src="https://dev.azure.com/best-practices/computervision/_apis/build/status/AzureML/AML-unit-test-linux-cpu?branchName=staging" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记本单元GPU</font></font></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">掌握</font></font></td>
<td><a href="https://dev.azure.com/best-practices/computervision/_build/latest?definitionId=42&amp;branchName=master" rel="nofollow"><img src="https://camo.githubusercontent.com/17989c7e46a75d4b61c59a3c51d3f2b4167b441bc9038cb07e48589682115b5b/68747470733a2f2f6465762e617a7572652e636f6d2f626573742d7072616374696365732f636f6d7075746572766973696f6e2f5f617069732f6275696c642f7374617475732f417a7572654d4c2f414d4c2d756e69742d746573742d6c696e75782d6e622d6770753f6272616e63684e616d653d6d6173746572" alt="构建状态" data-canonical-src="https://dev.azure.com/best-practices/computervision/_apis/build/status/AzureML/AML-unit-test-linux-nb-gpu?branchName=master" style="max-width: 100%;"></a></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分期</font></font></td>
<td><a href="https://dev.azure.com/best-practices/computervision/_build/latest?definitionId=42&amp;branchName=staging" rel="nofollow"><img src="https://camo.githubusercontent.com/bdcb661cdba045f4f9ad0de2335040ce508faa30e84a1b1a66dca63eddaaae80/68747470733a2f2f6465762e617a7572652e636f6d2f626573742d7072616374696365732f636f6d7075746572766973696f6e2f5f617069732f6275696c642f7374617475732f417a7572654d4c2f414d4c2d756e69742d746573742d6c696e75782d6e622d6770753f6272616e63684e616d653d73746167696e67" alt="构建状态" data-canonical-src="https://dev.azure.com/best-practices/computervision/_apis/build/status/AzureML/AML-unit-test-linux-nb-gpu?branchName=staging" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<h2 tabindex="-1" dir="auto"><a id="user-content-contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目欢迎贡献和建议。请参阅我们的</font></font><a href="/microsoft/computervision-recipes/blob/staging/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</article></div>
