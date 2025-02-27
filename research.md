---
layout: page
title: Research
---

<style>
/* Abstract Link Styling */
.abstract-link {
    color: #007BFF;
    cursor: pointer;
    text-decoration: none;
    font-size: 0.9em;
    display: flex;
    align-items: center;
}

.abstract-link:hover {
    color: #0056b3;
}

/* Triangle Icon Styling */
.triangle {
    margin-right: 5px;
    transition: transform 0.3s ease;
}

/* Abstract Content Styling */
.abstract-content {
    display: none;
    margin-top: 10px;
    padding: 10px;
    border-left: 3px solid #007BFF;
    background-color: #f9f9f9;
    font-size: 0.9em;
    border-radius: 5px;
}

</style>


**How  Platform Transparency Shapes Provider Choices: Evidence from A Natural Experiment**  
<u>Rubing Li</u>, Xiao Liu, Arun Sundararajan
<br><span style="font-size: 16px;">(Work in progress)</span>
<br><span style="font-size: 16px;">Conference Presentations: <em>WISE 2024</em></span>


**The Rise of Recommerce: Ownership and Sustainability with Overlapping Generations**  
<u>Rubing Li</u>, Arun Sundararajan  [arXiv](https://arxiv.org/abs/2405.09023){: .btn} [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4827707){: .btn}
<br><span style="font-size: 16px;"> Revise and Resubmit (2nd round), <em>Information Systems Research</em></span>
<br><span style="font-size: 16px;">Conference Presentations: <em>Marketing Science 2023, WISE 2023, IIOC 2024, INFORMS CIST 2024</em></span>
<br><span style="font-size: 16px;color:#0056b3">2023 <em>ICIS</em> Best Paper Finalist </span>
<span class="abstract-link" onclick="toggleAbstract('abstract1', this)">
    <span class="triangle">▼</span> Abstract
</span>
<div id="abstract1" class="abstract-content">
   The emergence of the branded recommerce channel — digitally enabled and branded marketplaces that facilitate purchasing pre-owned items directly from a manufacturer’s e-commerce site — leads to new variants of classic IS and economic questions relating to secondary markets. Such branded recommerce is increasingly platform-enabled, creating opportunities for greater sustainability and stronger brand experience control but posing a greater risk of cannibalization of the sales of new items. We model the effects that the sales of pre-owned items have on market segmentation and product durability choices for a monopolist facing heterogeneous customers, contrasting outcomes when the trade of pre-owned goods takes place through a third-party marketplace with outcomes under branded recommerce. We show that the direct revenue benefits of branded recommerce are not their primary source of value to the monopolist, and rather, there are three indirect effects that alter profits and sustainability. Product durability increases, a seller finds it optimal to forgo marketplace fees altogether, and there are greater seller incentives to lower the quality uncertainty associated with pre-owned items. We establish these results for a simple two-period model as well as developing a new infinite horizon model with overlapping generations. Our paper sheds new insight into this emerging digital channel phenomenon, underscoring the importance of recommerce platforms in aligning seller profits with sustainability goals.
</div>

**Predicting Consumer In-Store Purchase through Real-Time Video Analytics: An Advanced Computer Vision and Deep Learning Approach**  
<u>Rubing Li</u><sup>†</sup>, Wen Wang<sup>†</sup>, Anindya Ghose, Beibei Li, Kaiquan Xu [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4513385){: .btn}
<br><span style="font-size: 14px;"> Revise and Resubmit (2nd round), <em>Information Systems Research</em></span>
<br><span style="font-size: 14px;">Conference Presentations: <em>SCECR 2021, INFORMS CIST 2021, INFORMS Data Science Workshop 2022, ICIS 2022</em></span>
<br><span style="font-size: 14px;color:#0056b3">2022 ICIS Nunamaker-Chen Best Impact Paper Award</span>
<span class="abstract-link" onclick="toggleAbstract('abstract3', this)">
    <span class="triangle">▼</span> Abstract
</span>
<div id="abstract3" class="abstract-content">
This study introduces a novel, theory-driven video analytics framework to predict purchase decisions in offline retail settings using consumer shopping video data. Our framework addresses four key challenges in offline consumer purchase prediction: (1) capturing real-time behavior, (2) enabling scalability and automation, (3) integrating multi-dimensional data, and (4) preserving the organic nature of consumer behavior without disrupting the shopping experience. To accomplish this, we combine Person Re-identification (Re-ID) technology, which tracks individuals across multiple cameras, with GPS-like trajectory reconstruction, Vision-Language Models (VLMs), and pose estimation to extract theory-driven, real-time shopping behavior features from video data. Our feature set captures a comprehensive range of real-time spatial-temporal trajectory details, including movement speed and path complexity; product interaction features, such as physical touch, item pickup, and visual engagement; body pose and movement indicators, like hand positioning and head orientation; and facial dynamics and eye gaze—offering a holistic perspective on in-store behavior and decision-making. Using deep learning models, specifically transformers, our framework predicts consumer purchase decisions from real-time video features. Extensive experiments demonstrate that it significantly outperforms benchmark models, proving the predictive strength of real-time video data for offline purchase forecasting. We also conduct interpretability analyses to reveal key factors driving model performance, offering marketers actionable insights to refine strategies. To showcase practical applications, we demonstrate various decision-support use cases, including consumer segmentation and real-time intent analysis, which distinguish patterns between purchasers and non-purchasers throughout the shopping journey. Additionally, our framework enables personalized, real-time targeting, with simulations showing a 15.8% profit increase over non-targeted approaches and a 7.51% gain over static targeting strategies. Overall, our proposed framework equips retailers with a powerful tool for predicting real-time purchase decisions and enhancing offline marketing effectiveness.
</div>

**Reasoning and the Trusting Behavior of DeepSeek and GPT: An Experiment Revealing Hidden Fault Lines in Large Language Models**  
<u>Rubing Li</u>, João Sedoc, Arun Sundararajan   [arXiv](https://arxiv.org/pdf/2502.12825){: .btn}  
<span style="font-size: 14px;">Conference Presentations: <em>NYU AI Symposium 2024, Yale AI/ML 2024</em></span>
<span class="abstract-link" onclick="toggleAbstract('abstract4', this)">
    <span class="triangle">▼</span> Abstract
</span>
<div id="abstract4" class="abstract-content">

When encountering increasingly frequent performance improvements or cost reductions from a new large language model (LLM), developers of applications leveraging LLMs must decide whether to take advantage of these improvements or stay with older tried-and-tested models. Low perceived switching frictions can lead to choices that do not consider more subtle behavior changes that the transition may induce. Our experiments use a popular game-theoretic behavioral economics model of trust to show stark differences in the trusting behavior of OpenAI’s and DeepSeek’s models. We highlight a collapse in the economic trust behavior of the o1-mini and o3-mini models as they reconcile profit-maximizing and risk- seeking with future returns from trust, and contrast it with DeepSeek’s more sophisticated and profitable trusting behavior that stems from an ability to incorporate deeper concepts like forward planning and theory-of-mind. As LLMs form the basis for high-stakes commercial systems, our results highlight the perils of relying on LLM performance benchmarks that are too narrowly defined and suggest that careful analysis of their hidden fault lines should be part of any organization’s AI strategy.

</div>

**Visible Localized Climate Change Events Alter Sustainable Consumption Behaviors**  
<u>Rubing Li</u>, Andy Ruben, Arun Sundararajan   
<span style="font-size: 14px;">Conference Presentations: <em>SCECR 2024</em></span>
<span class="abstract-link" onclick="toggleAbstract('abstract2', this)">
    <span class="triangle">▼</span> Abstract
</span>
<div id="abstract2" class="abstract-content">

As concerns about environmental and climate change rise, consumers increasingly include sustainability considerations in their consumption choices. We examine whether consumers may be affected by the growing visible evidence of climate change that, rather than being distant, is geographically proximal to a consumer and has a direct effect on their lives. We focus on a single natural experiment — the “Mosquito Fire,” — the largest wildfire in California in 2022 that lasted from September 6, 2022 to October 22, 2022. We use NOAA and EPA data to determine the extent to which each zip code in California, Oregon and Washington was “treated,” that is, the extent to which a consumer might have been visibly affected by the Mosquito fire on any given day during the event window. We obtain demand data about the demand and revenue associated with purchases of pre-owned items sold by a selected set of global apparel and accessory brands from Trove, a platform that powers the “branded recommerce” sites of a range of leading brands. These data are obtained at the zipcode level for CA, OR and WA, as well as for a matched sample of control zipcodes chosen from a set of states not affected by the Mosquito Fire or any other major climate-related local event during the event window. Our results establish that consumers in zipcodes exposed to the Mosquito Fire increased their purchasing of pre-owned items by economically significant levels (ranging from 5% to 18%) following the event, and that these effects persisted in the months following the event. We rule out a number of alternative explanations, and also report on a “face validity” experiment establishing that consumers exposed to localized climate change disasters subsequently display a measurable preference for purchasing pre-owned items. 

</div>

**Common Law Annotations: Investigating the Stability of Dialog System Output Annotations**  
With Seunggun Lee, João Sedoc and nine other coauthors [ACL](https://aclanthology.org/2023.findings-acl.780.pdf){: .btn}
<br><span style="font-size: 14px;"><em>Findings of the Association for Computational Linguistics: ACL 2023</em></span>


**Rarity, Trader Heterogeneity and Pricing Power in an NFT Marketplace**  
<u>Rubing Li</u>, Arun Sundararajan   
<span style="font-size: 14px;">Conference Presentations: <em>SCECR 2022, WISE 2022</em></span>




<br><span style="font-size: 0.75em;">(<sup>†</sup> Indicates shared first authorship)</span>


<script>
function toggleAbstract(id) {
    var abstract = document.getElementById(id);
    if (abstract.style.display === "none" || abstract.style.display === "") {
        abstract.style.display = "block";
    } else {
        abstract.style.display = "none";
    }
}
</script>


