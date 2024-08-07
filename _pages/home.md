---
layout: project
urltitle:  "Natural Language Reasoning and Structured Explanations Workshop"
title: "Natural Language Reasoning and Structured Explanations Workshop"
categories: workshop, computer vision, natural language, grounding, interaction, machine learning, vigil, naacl, 2021
permalink: /
bibtex: true
paper: true
acknowledgements: ""
---

<!-- <br /> -->
<!-- <div class="row" id="title">
  <div class="col-xs-12">
    <center><h1>Natural Language Reasoning and Structured Explanations Workshop</h1></center>
    <center><h2>July 13-14, 2023 @ ACL 2023. Toronto, Canada.</h2></center>
 
    
    
  </div>
</div> -->

<br />

<div class="row">
    <div class="col-xs-12">
        <p>
          With recent scaling of large pre-trained Transformer language models (LLMs), the scope of feasible NLP tasks has broadened. Significant recent work has focused on tasks that require some kind of natural language reasoning. A trajectory in question answering has led us from extraction-oriented datasets like SQuAD to “multi-hop” reasoning datasets like HotpotQA and StrategyQA. Although LLMs have shown remarkable performance on most NLP tasks, it is often unclear why their answers follow from what they know. To address this gap, a new class of explanation techniques has emerged which play an integral part in structuring the reasoning necessary to solve these datasets. For example, the chain-of-thought paradigm leverages explanations as vehicles for LLMs to mimic human reasoning processes. Entailment trees offer a way to ground multi-step reasoning in a collection of verifiable steps. Frameworks like SayCan bridge high-level planning in language and with low-level action trajectories. As a result, we see a confluence of methods blending explainable machine learning/NLP, classical AI (especially theorem proving), and cognitive science (how do humans structure explanations?). This workshop aims to bring together a diverse set of perspectives from these different traditions and attempt to establish common ground for how these various kinds of explanation structures can tackle a broad class of reasoning problems in natural language and beyond.
        </p>
    </div>
</div>

<br />

<div class="row" id="schedule">
  <div class="col-md-4 col-xs-12">
    <h2>Schedule</h2>
  </div>
  <!-- <div class="col-md-8 col-xs-12">
      <select id="timezone-select" class="form-control"></select>
  </div> -->
</div>
<div class="row">
  <div class="col-xs-12">
    <table class="table table-striped" id="schedule-table">
    <tbody>
    <tr> <th scope="row" data-time="08:00">08:00 AM</th> <td>Virtual Poster Session</td></tr>
    <tr> <th scope="row" data-time="08:55">08:55 AM</th> <td>Opening Remarks</td></tr>
    <tr> <th scope="row" data-time="09:00">09:00 AM</th> <td>
      Invited Speaker - Sherry Tongshuang Wu<br />
      <!-- <span style="font-style:italic">Mechanistic Evidence of Structured Reasoning in LLMs</span>
      <a href="https://drive.google.com/file/d/1Fg_jiTd7ai20kd7WmEQL-lknSlqOq5bw/view?usp=drive_link" >[Slides]</a> -->
    </td></tr>
    <tr> <th scope="row" data-time="09:50">09:45 AM</th> <td>
      Invited Speaker - Karthik Narasimhan<br />
      <!-- <span style="font-style:italic">Reasoning in human and machine intelligence</span>
      <a href="https://docs.google.com/presentation/d/1x3WGLTiCb0BqjM1-FgsmmiyEDRKLCJVp/edit?usp=drive_link&ouid=103388184196365975806&rtpof=true&sd=true" >[Slides]</a> -->
    </td></tr>
    <tr> <th scope="row" data-time="10:30">10:30 AM</th> <td>Break 1</td></tr>
    <tr> <th scope="row" data-time="11:00">11:00 AM</th> <td>
      Invited Speaker - Thomas Icard<br />
      <!-- <span style="font-style:italic">Reasoning in human and machine intelligence</span>
      <a href="https://docs.google.com/presentation/d/1x3WGLTiCb0BqjM1-FgsmmiyEDRKLCJVp/edit?usp=drive_link&ouid=103388184196365975806&rtpof=true&sd=true" >[Slides]</a> -->
    </td></tr>
    <tr> <th scope="row" data-time="11:45">11:45 AM</th> <td>
      Oral Presentation: Kartik Chandra, Katherine M. Collins, Will Crichton, Tony Chen, Rachit Nigam, Adrian Weller, Tzu-Mao Li, Joshua B. Tenenbaum, Jonathan Ragan-Kelley<br/>
      <span style="font-style:italic">WatChat: Explaining perplexing programs by debugging mental models</span>
      <a data-toggle="collapse" href="#schedule-talk8" aria-cexpanded="false" aria-controls="schedule-talk8">[Abstract]</a>
      <div class="collapse" id="schedule-talk8">
        Abstract: Often, a good explanation for a program's unexpected behavior is a bug in the programmer's code. But sometimes, an even better explanation is a bug in the programmer's mental model of the language or API they are using. Instead of merely debugging our current code (giving the programmer a fish''), what if our tools could directly debug our mental models (teaching the programmer to fish'')? <br> In this paper, we apply recent ideas from computational cognitive science to offer a principled framework for doing exactly that. Given a ``why?'' question about a program, we automatically infer potential misconceptions about the language/API that might cause the user to be surprised by the program's behavior---and then analyze those misconceptions to provide explanations of the program's behavior. Our key idea is to formally represent misconceptions as counterfactual (erroneous) semantics for the language/API, which can be inferred and debugged using program synthesis techniques. <br> We demonstrate our framework, WatChat, by building systems for explanation in two domains: JavaScript type coercion, and the Git version control system. We evaluate WatChatJS and WatChatGit by comparing their outputs to experimentally-collected human-written explanations in these two domains: we show that WatChat explanations exhibit key features of human-written explanation, unlike those of a state-of-the-art language model.
      </div>
    </td> </tr>
    <tr> <th scope="row" data-time="12:00">12:00 PM</th> <td>
      Oral Presentation: Tianyi Zhang, Li Zhang, Zhaoyi Joey Hou, Ziyu Wang, Yuling Gu, Peter Clark, Chris Callison-Burch, Niket Tandon <br/>
      <span style="font-style:italic">PROC2PDDL: Open-Domain Planning Representations from Texts</span>
      <a data-toggle="collapse" href="#schedule-talk5" aria-cexpanded="false" aria-controls="schedule-talk5">[Abstract]</a>
      <div class="collapse" id="schedule-talk5">
        Abstract: Planning in a text-based environment continues to be a significant challenge for AI systems. Recent approaches have utilized language models to predict planning domain definitions (e.g., PDDL) but have only been evaluated in closed-domain simulated environments. To address this, we present Proc2PDDL, the first dataset containing open-domain procedural texts paired with expert-annotated PDDL representations. Using this dataset, we evaluate the task of predicting domain actions (parameters, preconditions, and effects). We experiment with various large language models (LLMs) and prompting mechanisms, including a novel instruction inspired by the zone of proximal development (ZPD), which reconstructs the task as incremental basic skills. Our results demonstrate that Proc2PDDL is highly challenging for end-to-end LLMs, with GPT-3.5's success rate close to 0% and GPT-4o's 38%. With ZPD instructions, GPT-4o's success rate increases to 45%, outperforming regular chain-of-thought prompting's 34%. Our analysis systematically examines both syntactic and semantic errors, providing insights into the strengths and weaknesses of language models in generating domain-specific programs.
      </div>
    </td></tr>
    <tr> <th scope="row" data-time="12:15">12:15 PM</th> <td>
      Oral Presentation: Debjit Paul, Robert West, Antoine Bosselut, Boi Faltings <br/>
      <span style="font-style:italic">Making Reasoning Matter: Measuring and Improving Faithfulness of Chain-of-Thought Reasoning</span>
      <a data-toggle="collapse" href="#schedule-talk6" aria-cexpanded="false" aria-controls="schedule-talk6">[Abstract]</a>
      <div class="collapse" id="schedule-talk6">
        Abstract: Large language models (LLMs) have been shown to perform better when asked to reason step-by-step before answering a question. However, it is unclear to what degree the model's final answer is faithful to the stated reasoning steps. In this paper, we perform a causal mediation analysis on twelve LLMs to examine how intermediate reasoning steps generated by the LLM influence the final outcome and find that LLMs do not reliably use their intermediate reasoning steps when generating an answer. To address this issue, we introduce FRODO, a framework to tailor small-sized LMs to generate correct reasoning steps and robustly reason over these steps. FRODO consists of an inference module that learns to generate correct reasoning steps using an implicit causal reward function and a reasoning module that learns to faithfully reason over these intermediate inferences using a counterfactual and causal preference objective. Our experiments show that FRODO significantly outperforms four competitive baselines. Furthermore, FRODO improves the robustness and generalization ability of the reasoning LM, yielding higher performance on out-of-distribution test sets. Finally, we find that FRODO's rationales are more faithful to its final answer predictions than standard supervised fine-tuning.
      </div>
    </td></tr>
    <tr> <th scope="row" data-time="12:30">12:30 PM</th> <td>Lunch Break</td> </tr>
    <tr> <th scope="row" data-time="14:00">14:00 PM</th> <td>
      Invited Speaker - Xiang Lorraine Li<br />
      <!-- <span style="font-style:italic">The role of NL reasoning in the age of GPT</span>
      <a href="https://docs.google.com/presentation/d/1Wcg7P4Yri-SWarNBRMkpUEIP2vQXIrpv/edit?usp=drive_link&ouid=103388184196365975806&rtpof=true&sd=true" >[Slides]</a>
      <a data-toggle="collapse" href="#schedule-talk7" aria-cexpanded="false" aria-controls="schedule-talk7">[Abstract]</a>
      <a data-toggle="collapse" href="#speaker-bio-talk7" aria-cexpanded="false" aria-controls="speaker-bio-talk7">[Speaker Bio]</a>
      <div class="collapse" id="schedule-talk7">
        Abstract: While the performance of new LLMs is stunning, it remains unclear how (or even if) an answer follows from their latent "beliefs" about the world, or whether an LLM even has a coherent internal belief system. In this talk I'll describe recent work we have done to probe a model's beliefs, construct interpretable representations of how the model's answers systematically follow from them, and how a broader system can identify and repair inconsistencies that may exist among those beliefs. More generally, I'll promote architectures in which interpretable, systematic NL reasoning and LLM-style reasoning co-exist in a broader system, allowing both styles of reasoning to inform each other, and paving the way for more interactive systems where users can probe, argue with, learn from, and teach our future companions.
      </div>
      <div class="collapse" id="speaker-bio-talk7">
        Peter Clark is a Senior Director and the interim CEO at the Allen Institute for AI (AI2), and leads the Aristo Project. His work focuses on natural language processing, machine reasoning, and world knowledge, and the interplay between these three areas.
      </div> -->
    </td> </tr>
    <tr> <th scope="row" data-time="14:45">14:45 PM</th> <td>
      Oral Presentation: Jiefu Ou, Arda Uzunoglu, Benjamin Van Durme, Daniel Khashabi<br />
      <span style="font-style:italic">The World Is Worth How Many APIs? A Thought Experiment</span>
      <a data-toggle="collapse" href="#schedule-talk4" aria-cexpanded="false" aria-controls="schedule-talk4">[Abstract]</a>
      <div class="collapse" id="schedule-talk4">
        Abstract: AI systems make decisions in physical environments through primitive actions or affordances that are accessed via API calls. While deploying AI agents in the real world involves numerous high-level actions, existing embodied simulators offer a limited set of domain-salient APIs. This naturally brings up the questions: how many primitive actions (APIs) are needed for a versatile embodied agent, and what should they look like? <br>
        We explore this via a thought experiment: assuming that wikiHow tutorials cover a wide variety of human-written tasks, what is the space of APIs needed to cover these instructions? We propose a framework to iteratively induce new APIs by grounding wikiHow instruction to situated agent policies. Inspired by recent successes in large language models (LLMs) for embodied planning, we propose a few-shot prompting to steer GPT-4 to generate Pythonic programs as agent policies and bootstrap a universe of APIs by 1) reusing a seed set of APIs; and then 2) fabricate new API calls when necessary. The focus of this thought experiment is on defining these APIs rather than their executability. <br> We apply the proposed pipeline on instructions from wikiHow tutorials. On a small fraction (0.5%) of tutorials, we induce an action space of 300+ APIs necessary for capturing the rich variety of tasks in the physical world. A detailed automatic and human analysis of the induction output reveals that the proposed pipeline enables effective reuse and creation of APIs. Moreover, a manual review revealed that existing simulators support only a small subset of the induced APIs (9 of the top 50 frequent APIs), motivating the development of action-rich embodied environments.
      </div>
    </td> </tr>
    <tr> <th scope="row" data-time="15:00">15:00 PM</th> <td>
      Oral Presentation: Hyeonbin Hwang, Doyoung Kim, Seungone Kim, Seonghyeon Ye, Minjoon Seo<br />
      <span style="font-style:italic">Self-Explore to Avoid the Pit: Improving the Reasoning Capabilities of Language Models with Fine-grained Rewards</span>
      <a data-toggle="collapse" href="#schedule-9" aria-cexpanded="false" aria-controls="schedule-9">[Abstract]</a>
      <div class="collapse" id="schedule-9">
        Abstract: Training on large amounts of rationales (i.e., CoT Fine-tuning) is effective at improving the reasoning capabilities of large language models (LLMs). However, acquiring human-authored rationales or augmenting rationales from proprietary models is costly and not scalable. In this paper, we study the problem of whether LLMs could self-improve their reasoning capabilities. To this end, we propose Self-Explore, where the LLM is tasked to explore the first wrong step (i.e., the first pit) within the rationale and use such signals as fine-grained rewards for further improvement. On the GSM8K and MATH test set, Self-Explore achieves 11.57% and 2.89% improvement on average across three LLMs compared to supervised fine-tuning (SFT).
      </div>
    </td> </tr>
        <tr> <th scope="row" data-time="15:15">15:15 PM</th> <td>
      Oral Presentation: Yichen Pan, Dehan Kong, Sida Zhou, Cheng Cui, Yifei Leng, Bing Jiang, Hangyu Liu, Yanyi Shang, Shuyan Zhou, Tongshuang Wu, Zhengyang Wu<br />
      <span style="font-style:italic">WebCanvas: Benchmarking Web Agents in Online Environments</span>
      <a data-toggle="collapse" href="#schedule-10" aria-cexpanded="false" aria-controls="schedule-10">[Abstract]</a>
      <div class="collapse" id="schedule-10">
        Abstract: For web agents to be practically useful, they must adapt to the continuously evolving web environment characterized by frequent updates to user interfaces and content. However, most existing benchmarks only capture the static aspects of the web. To bridge this gap, we introduce Webcanvas, an innovative online evaluation framework for web agents that effectively addresses the dynamic nature of web interactions. Webcanvas contains three main components to facilitate realistic assessments: (1) A novel evaluation metric which reliably capture critical intermediate actions or states necessary for task completions while disregarding noise caused by insignificant events or changed web-elements. (2) A benchmark dataset called Mind2Web-Live, a refined version of original Mind2Web static dataset containing 542 tasks with 2439 intermediate evaluation states; (3) Lightweight and generalizable annotation tools and testing pipelines that enables the community to collect and maintain the high-quality, up-to-date dataset. Building on Webcanvas, we open-source an agent framework with extensible modules for reasoning, providing a foundation for the community to conduct online inference and evaluations. Our best-performing agent achieves a task success rate of 23.1% and a task completion rate of 48.8% on the Mind2Web-Live test set. Additionally, we analyze the performance discrepancies across various websites, domains, and experimental environments. We encourage the community to contribute further insights on online agent evaluation, thereby advancing this field of research. Our platform, tool and dataset are publically available at https://www.imean.ai/web-canvas and https://huggingface.co/datasets/iMeanAI/Mind2Web-Live.
      </div>
    </td> </tr>
    <tr> <th scope="row" data-time="15:30">15:30 PM</th> <td>Break 2</td></tr>
    <tr> <th scope="row" data-time="16:00">16:00 PM</th> <td>In-Person Poster Session</td> </tr>
    </tbody>
    </table>
  </div>
</div>

<hr />

<!-- Speakers -->
<div class="row" id="speakers">
  <div class="col-xs-12">
    <h2>Speakers</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-6 col-lg-3">
    <a href="https://www.cs.cmu.edu/~sherryw/">
      <img class="people-pic" src="{{ "/static/img/people/sherrywu.jpeg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://www.cs.cmu.edu/~sherryw/">Sherry Tongshuang Wu</a>
      <h6>Carnegie Mellon University</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://www.cs.princeton.edu/~karthikn/">
      <img class="people-pic" src="{{ "/static/img/people/karthikn.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://www.cs.princeton.edu/~karthikn/">Karthik Narasimhan</a>
      <h6>Princeton University</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://web.stanford.edu/~icard/">
      <img class="people-pic" src="https://philosophy.stanford.edu/sites/philosophy/files/styles/hs_medium_square_360x360/public/media/image/TIcard-photo.jpg?h=e98ce842&itok=kSJ6I6Bl">
    </a>
    <div class="people-name">
      <a href="https://web.stanford.edu/~icard/">Thomas Icard</a>
      <h6>Stanford University</h6>
    </div>
  </div>
    <div class="col-xs-6 col-lg-3">
    <a href="https://lorraine333.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/lorrianeli.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://lorraine333.github.io/">Xiang Lorraine Li</a>
      <h6>University of Pittsburgh</h6>
    </div>
  </div>
</div>

<hr />

<div class="row" id="accepted">
  <div class="col-xs-12">
    <h2>Accepted Papers</h2>
  </div>
</div>

<ul class="paper-list">
  <li>
    <span class="paper-title">Applying RLAIF for Code Generation with API-usage in Lightweight LLMs</span><br>
    <span class="paper-authors">Sujan Dutta, Sayantan Mahinder, Raviteja Anantha, Bortik Bandyopadhyay</span><br>
    <span class="paper-type"><span>[Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Are Machines Better at Complex Reasoning? Unveiling Human-Machine Inference Gaps in Entailment Verification</span><br>
    <span class="paper-authors">Soumya Sanyal, Tianyi Xiao, Jiacheng Liu, Wenya Wang, Xiang Ren</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Are self-explanations from Large Language Models faithful?</span><br>
    <span class="paper-authors">Andreas Madsen, Sarath Chandar, Siva Reddy</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">COPA-SSE: Semi-structured Explanations for Commonsense Reasoning</span><br>
    <span class="paper-authors">Ana Brassard, Benjamin Heinzerling, Pride Kavumba, Kentaro Inui</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Concept-aware Data Construction Improves In-context Learning of Language Models</span><br>
    <span class="paper-authors">Michal Štefánik, Marek Kadlcík, Petr Sojka</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Cooperative Explanation as Rational Communication</span><br>
    <span class="paper-authors">Kartik Chandra, Tony Chen, Tzu-Mao Li, Jonathan Ragan-Kelley, Joshua B. Tenenbaum</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Deception in Reinforced Autonomous Agents: The Unconventional Rabbit Hat Trick in Legislation</span><br>
    <span class="paper-authors">Atharvan Dogra, Ameet Deshpande, John J Nay, Tanmay Rajpurohit, Ashwin Kalyan, Balaraman Ravindran</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">DiffuCOMET: Contextual Commonsense Knowledge Diffusion</span><br>
    <span class="paper-authors">Silin Gao, Mete Ismayilzada, Mengjie Zhao, Hiromi Wakaki, Yuki Mitsufuji, Antoine Bosselut</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Distilling Algorithmic Reasoning from LLMs via Explaining Solution Programs</span><br>
    <span class="paper-authors">Jierui Li, Ray Mooney</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">SAGA: A Participant-specific Examination of Story Alternatives and Goal Applicability for a Deeper Understanding of Complex Events</span><br>
    <span class="paper-authors">Sai Vallurupalli, Katrin Erk, Francis Ferraro</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Fill in the Blank: Exploring and Enhancing LLM Capabilities for Backward Reasoning in Math Word Problems</span><br>
    <span class="paper-authors">Aniruddha Deb, Neeva Hareshbhai Oza, Sarthak Singla, Dinesh Khandelwal, Dinesh Garg, Parag Singla</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">From Good to Great: Improving Math Reasoning with Tool-Augmented Interleaf Prompting</span><br>
    <span class="paper-authors">Nuo Chen, Hongguang Li, Baoyuan Wang, Jia Li</span><br>
    <span class="paper-type"><span>[Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">GraphReason: Enhancing Reasoning Capabilities of Large Language Models through A Graph-Based Verification Approach</span><br>
    <span class="paper-authors">Lang Cao</span><br>
    <span class="paper-type"><span>[Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Inductive or Deductive? Rethinking the Fundamental Reasoning Abilities of LLMs</span><br>
    <span class="paper-authors">Kewei Cheng, Jingfeng Yang, Haoming Jiang, Zhengyang Wang, Binxuan Huang, Ruirui Li, Shiyang Li, Zheng Li, Yifan Gao, Xian Li, Bing Yin, Yizhou Sun</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">It’s Not Easy Being Wrong: Large Language Models Struggle with Process of Elimination Reasoning</span><br>
    <span class="paper-authors">Nishant Balepur, Shramay Palta, Rachel Rudinger</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">LINC: A Neurosymbolic Approach for Logical Reasoning by Combining Language Models with First-Order Logic Provers</span><br>
    <span class="paper-authors">Theo X. Olausson, Alex Gu, Benjamin Lipkin, Cedegao E. Zhang, Armando Solar-Lezama, Joshua B. Tenenbaum, Roger Levy</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">LLMs cannot find reasoning errors, but can correct them given the error location</span><br>
    <span class="paper-authors">Gladys Tyen, Hassan Mansoor, Victor Carbune, Peter Chen, Tony Mak</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">LOGIC-LM++: Multi-Step Refinement for Symbolic Formulations</span><br>
    <span class="paper-authors">Shashank Kirtania, Priyanshu Gupta, Arjun Radhakrishna</span><br>
    <span class="paper-type"><span>[Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Language Models as Compilers: Simulating Pseudocode Execution Improves Algorithmic Reasoning in Language Models</span><br>
    <span class="paper-authors">Hyungjoo Chae, Yeonghyeon Kim, Seungone Kim, Kai Tzu-iunn Ong, Beong-woo Kwak, Moohyeon Kim, Sunghwan Kim, Taeyoon Kwon, Jiwan Chung, Youngjae Yu, Jinyoung Yeo</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Large Language Models for Automated Open-domain Scientific Hypotheses Discovery</span><br>
    <span class="paper-authors">Zonglin Yang, Xinya Du, JUNXIAN LI, Jie Zheng, Soujanya Poria, Erik Cambria</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Large Language Models for Automated Open-domain Scientific Hypotheses Discovery</span><br>
    <span class="paper-authors">Zonglin Yang, Xinya Du, Junxian Li, Jie Zheng, Soujanya Poria, Erik Cambria</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Making Reasoning Matter: Measuring and Improving Faithfulness of Chain-of-Thought Reasoning</span><br>
    <span class="paper-authors">Debjit Paul, Robert West, Antoine Bosselut, Boi Faltings</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Multi-hop Question Answering under Temporal Knowledge Editing</span><br>
    <span class="paper-authors">Keyuan Cheng, Gang Lin, Haoyang Fei, Yuxuan Zhai, Lu Yu, Muhammad Asif Ali, Lijie Hu, Di Wang</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">PARADISE: Evaluating Implicit Planning Skills of Language Models with Procedural Warnings and Tips Dataset</span><br>
    <span class="paper-authors">Arda Uzunoğlu, Abdalfatah Rashid Safa, Gözde Gül Şahin</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">PROC2PDDL: Open-Domain Planning Representations from Texts</span><br>
    <span class="paper-authors">Tianyi Zhang, Li Zhang, Zhaoyi Joey Hou, Ziyu Wang, Yuling Gu, Peter Clark, Chris Callison-Burch, Niket Tandon</span><br>
    <span class="paper-type"><span>[Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Prompt Engineering a Prompt Engineer</span><br>
    <span class="paper-authors">Qinyuan Ye, Maxamed Axmed, Reid Pryzant, Fereshte Khani</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">QA-NatVer: Question Answering for Natural Logic-based Fact Verification</span><br>
    <span class="paper-authors">Rami Aly, Marek Strong, Andreas Vlachos</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Self-Explore to Avoid the Pit: Improving the Reasoning Capabilities of Language Models with Fine-grained Rewards</span><br>
    <span class="paper-authors">Hyeonbin Hwang, Doyoung Kim, Seungone Kim, Seonghyeon Ye, Minjoon Seo</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Self-Training with Direct Preference Optimization Improves Chain-of-Thought Reasoning</span><br>
    <span class="paper-authors">Tianduo Wang, Shichen Li, Wei Lu</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Small Language Models Need Strong Verifiers to Self-Correct Reasoning</span><br>
    <span class="paper-authors">Yunxiang Zhang, Muhammad Khalifa, Lajanugen Logeswaran, Jaekyeom Kim, Moontae Lee, Honglak Lee, Lu Wang</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">SummEQuAL: Summarization Evaluation via Question Answering using Large Language Models</span><br>
    <span class="paper-authors">Junyuan Liu, Zhengyan Shi, Aldo Lipani</span><br>
    <span class="paper-type"><span>[Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Tailoring with Targeted Precision: Edit-Based Agents for Open-Domain Procedure Customization</span><br>
    <span class="paper-authors">Yash Kumar Lal, Li Zhang, Faeze Brahman, Bodhisattwa Prasad Majumder, Peter Clark, Niket Tandon</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">TextGenSHAP: Scalable Post-hoc Explanations in Text Generation with Long Documents</span><br>
    <span class="paper-authors">James Enouen, Hootan Nakhost, Sayna Ebrahimi, Sercan O Arik, Yan Liu, Tomas Pfister</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">The Counterfeit Conundrum: Can Code Language Models Grasp the Nuances of Their Incorrect Generations?</span><br>
    <span class="paper-authors">Alex Gu, Wen-Ding Li, Naman Jain, Theo X. Olausson, Celine Lee, Koushik Sen, Armando Solar-Lezama</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">The World Is Worth How Many APIs? A Thought Experiment</span><br>
    <span class="paper-authors">Jiefu Ou, Arda Uzunoglu, Benjamin Van Durme, Daniel Khashabi</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">TimeChara: Evaluating Point-in-Time Character Hallucination of Role-Playing Large Language Models</span><br>
    <span class="paper-authors">Jaewoo Ahn, Taehyun Lee, Junyoung Lim, Jin-Hwa Kim, Sangdoo Yun, Hwaran Lee, Gunhee Kim</span><br>
    <span class="paper-type"><span>[Cross-Submission]</span></span><br>
  </li>

  <li>
    <span class="paper-title">Towards A Unified View of Answer Calibration for Multi-Step Reasoning</span><br>
    <span class="paper-authors">Shumin Deng, Ningyu Zhang, Nay Oo, Bryan Hooi</span><br>
    <span class="paper-type"><span>[Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">WatChat: Explaining perplexing programs by debugging mental models</span><br>
    <span class="paper-authors">Kartik Chandra, Katherine M. Collins, Will Crichton, Tony Chen, Rachit Nigam, Adrian Weller, Tzu-Mao Li, Joshua B. Tenenbaum, Jonathan Ragan-Kelley</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>

  <li>
    <span class="paper-title">WebCanvas: Benchmarking Web Agents in Online Environments</span><br>
    <span class="paper-authors">Yichen Pan, Dehan Kong, Sida Zhou, Cheng Cui, Yifei Leng, Bing Jiang, Hangyu Liu, Yanyi Shang, Shuyan Zhou, Tongshuang Wu, Zhengyang Wu</span><br>
    <span class="paper-type"><span>[Non-Archival]</span></span><br>
  </li>
</ul>


<div class="row" id="cfp">
  <div class="col-xs-12">
    <h2>Call for Papers</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
    <p>
      We welcome submissions on all topics related to natural language reasoning or structured explanations, which might include:
    </p>
    <p>
  <ul>
  <li>Multi-step natural language reasoning;</li>
  <li>Structured explanations;</li>
  <li>Foundations of natural language reasoning;</li>
  <li>Knowledge retrieval for multi-step reasoning;</li>
  <li>Reasoning in interactive environments;</li>
  <li>Applications of natural language reasoning;</li>
  <li>Reasoning as programs;</li>
  <li>Neuro-symbolic reasoning;</li>
          </ul>
      </p>
      <p>With recent scaling of large pre-trained Transformer language models (LLMs), the scope of feasible NLP tasks has broadened, including tasks requiring increasingly complex reasoning. Although LLMs have shown remarkable performance, it is still unclear how to best elicit this reasoning and to what extent the answers that models give follow from what they “know.” This workshop aims to bring together a diverse set of perspectives and attempts to establish common ground for how various kinds of explanation structures can tackle a broad class of reasoning problems in natural language and beyond. As such, the workshop welcomes and covers a wide range of topics, including (non-exclusively):</p>
  
  <ul>
    <li><b>Multi-step natural language reasoning: </b>Solving reasoning problems, such as those involving abstract manipulations, has been a long-standing challenge in the field of artificial intelligence. Large language models have recently achieved a new state-of-the-art performance on many reasoning benchmarks, often with approaches only requiring prompting. Current research frontiers are exploring what kinds of explanation formats are most effective, how reasoning is most effectively broken down, how to get language models to plan their reasoning, and what resources can be used to improve reasoning capabilities of language models. Tasks include mathematical reasoning, logical reasoning, commonsense reasoning, and more.</li>
  <li><b>Structured explanations: </b>Explanations for these complex tasks are typically composed of two or more facts that are used to help guide the reasoning process while also providing a record of the path taken to arrive at an inference. What representations can be best used by inference algorithms to construct large explanations? Frontiers of research include exploring search algorithms over such representations, how to represent annotations at scale and continual learning models.</li>
  <li><b>Foundations of natural language reasoning: </b>Does the structured reasoning constitute a plausible (interpretable to humans) and faithful (true to the model's processes) explanation? Does perturbing the reasoning lead to correctly modified behavior?</li>
  <li><b>Knowledge retrieval for multi-step reasoning: </b>It has been shown that LLMs can store factual knowledge implicitly in their parameters, however, their ability to access and manipulate knowledge is still limited. Future avenues of research include effective methods to combine parametric and non-parametric knowledge for complex reasoning, conditioning retrieval given intermediate reasoning context, retrieving better provenance for structured explanations.</li>
  <li><b>Reasoning in interactive environments: </b>Interactive environments are becoming an increasingly popular method for evaluating reasoning where an agent observes the environment, then takes steps in that environment to accomplish some goal. Here, manner (i.e. how-to) explanations take the form of the list of actions the agent required to accomplish some goal, e.g., "how to boil water in a kitchen", "how to grow an apple tree", "how to book a flight and a hotel in LA".</li>
  <li><b>Applications of natural language reasoning: </b>New QA settings, language grounding, explainable diagnosis systems, theorem provers using natural language, reasoning for scientific discovery, and more.</li>
  <li><b>Reasoning as programs: </b>Another body of work within computational cognitive science and AI has formalized reasoning as inference over programs, building on classical views of human reasoning in a symbol-like language of thought and linguistic semantics with logical languages. Language models of code to produce structured reasoning for commonsense problems or other similar approaches are all in scope here.</li>
  <li><b>Neuro-symbolic reasoning: </b>Pockets of contemporary work have proposed reformulating natural language reasoning as proceeding via modular neurosymbolic systems. Here LLMs operate as declarative programmers, “translating” natural language into a formal specification, such as one accepted by a satisfiability solver, and explicit inference is offloaded to classical symbolic algorithms for planning, constraint satisfaction, or probabilistic simulation.</li>
 </ul>
  </div>
</div>
<hr />
<!-- Submission -->
<div class="row" id="guidelines">
  <div class="col-xs-12">
    <h2>Submission Guidelines</h2>
  </div>
</div>
<div class="row">
    <div class="col-xs-12">
      <p>
      We welcome three types of papers: archival workshop papers, non-archival papers, and non-archival cross-submissions. Only regular workshop papers will be included in the workshop proceedings. <i>Regular workshop submissions (both archival and non-archival)</i> should be in PDF format and made through the <b>OpenReview website</b> set up for this workshop 
      <a style="color:#2980b9;font-weight:400;" href="https://openreview.net/group?id=aclweb.org/ACL/2024/Workshop/NLRSE#tab-your-consoles">(link)</a>. In line with the ACL main conference policy, camera-ready versions of regular workshop papers will be given one additional page of content. <i>Non-archival cross-submissions</i> should be made through the <b>form</b> <a style="color:#2980b9;font-weight:400;" href="https://forms.gle/BKn4bczXfaXN7GSg7">(link)</a>.
        </p>
    <ul>
      <li><b>Archival regular workshop papers: </b>
      <!-- Authors should submit a paper up to <b>8 pages (both short and long papers are welcome)</b>, with unlimited pages for references, following the <a style="color:#2980b9;font-weight:400;" href="https://2023.aclweb.org/calls/main_conference/#paper-types-and-formats">ACL 2023 formatting requirements</a>. The reported research should be substantially original. All submissions will be reviewed in a single track, regardless of length. Accepted papers will be presented as posters by default, and best papers may be given the opportunity for a brief talk to introduce their work. Reviewing will be double-blind, and thus no author information should be included in the papers; self-reference that identifies the authors should be avoided or anonymised. Accepted papers will appear in the workshop proceedings. -->
      Authors should submit a paper <b>up to 8 pages (both short and long papers are welcome)</b>, with unlimited pages for references, following the <a href="https://www.aclweb.org/adminwiki/index.php/ACL_Author_Guidelines" style="color:#2980b9;font-weight:400;">ACL author guidelines</a>. The reported research should be substantially original. All submissions will be reviewed in a single track, regardless of length. Accepted papers will be presented as posters by default, and best papers may be given the opportunity for a brief talk to introduce their work. Reviewing will be double-blind, and thus no author information should be included in the papers; self-reference that identifies the authors should be avoided or anonymised. Accepted papers will appear in the workshop proceedings. <b>Preference for oral presentation slots in the workshop will be given to archival papers</b>.</li>
      <li> <b> Non-archival regular workshop papers: </b> This is the same as the option above, but these papers will not appear in the proceedings and will typically only receive poster presentation slots. Non-archival submissions in this category will still undergo the review process. This is appropriate for nearly finished work that is intended for submission to another venue at a later date. </li>
      <li><b>Non-archival cross-submissions: </b> We also solicit cross-submissions, i.e., papers on relevant topics that <i>have already</i> appeared in other venues (e.g., workshop or conference papers at NLP, ML, or cognitive science venues, among others). Accepted papers will be presented at the workshop, with an indication of original venue, but will not be included in the workshop proceedings. Cross-submissions are ideal for related work which would benefit from exposure to the <b>NLReasoning</b> audience. Papers in this category do not need to follow the ACL format, and the submission length is determined by the original venue. The paper selection will be solely determined by the organizing committee in a non-blind fashion. These papers will typically receive poster presentation slots.</li>
    </ul>
    <p>
        In addition, we welcome papers on relevant topics that are <i>under review or to be submitted to </i> other venues (including the ACL 2024 main conference). These papers must follow the regular workshop paper format and will not be included in the workshop proceedings. Papers in this category will be reviewed by workshop reviewers.</p>
   
   <p>
     <b>Note to authors: For archival and non-archival regular workshop submissions, while you submit your paper through OpenReview (<a style="color:#2980b9;font-weight:400;" href="https://openreview.net/group?id=aclweb.org/ACL/2024/Workshop/NLRSE#tab-your-consoles">link</a>), please select the "Submission Type" properly based on the guidelines. For cross-submissions, please fill out this form (<a style="color:#2980b9;font-weight:400;" href="https://forms.gle/BKn4bczXfaXN7GSg7">link</a>) and do NOT submit through OpenReview.
</b></p>
   <p>
   For questions about the submission guidelines, please contact workshop organizers via <a href="nl-reasoning@googlegroups.com">nl-reasoning@googlegroups.com</a>.

     </p>
      
</div>
</div>
<hr />
  
<div class="col-xs-12"  id="dates">
    <h2>Important Dates</h2>  
</div>

<br>
<div class="row">
  <div class="col-xs-12">
    <table class="table table-striped">
      <tbody>
        <tr>
          <td>Paper Submission Deadline</td>
          <td>May 21, 2024 (All deadlines are 11:59 PM AoE time.)</td>
        </tr>
        <tr>
          <td>Decision Notifications</td>
          <td>June 17, 2024</td>
        </tr>
        <tr>
          <td>Camera Ready Paper Deadline</td>
          <td>July 1, 2024</td>
        </tr>
        <tr>
          <td>Workshop Date</td>
          <td>Aug 15, 2024</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>


<hr />


<!-- Organizers -->
<div class="row" id="organizers">
  <div class="col-xs-12">
    <h2>Organizers</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-6 col-lg-3">
    <a href="https://www.cs.utexas.edu/~gdurrett//">
      <img class="people-pic" src="https://www.cs.utexas.edu/~gdurrett/photo.png">
    </a>
    <div class="people-name">
      <a href="https://www.cs.utexas.edu/~gdurrett/">Greg Durrett</a>
      <h6>University of Texas, Austin</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://allenai.org/team/bhavanad/">
      <img class="people-pic" src="https://images.ctfassets.net/wf5t1ptx352c/6W6eEkb6MMkoU8gYM8CWgW/d2f1d7519f70705caef84f2a5b1af39b/Bhavana-Dalvi.jpg">
    </a>
    <div class="people-name">
      <a href="https://allenai.org/team/bhavanad/">Bhavana Dalvi</a>
      <h6>Allen Institute for AI</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://cognitiveai.org/">
      <img class="people-pic" src="http://cognitiveai.org/wp-content/uploads/2016/10/peter_tedx-300x300.jpg">
    </a>
    <div class="people-name">
      <a href="https://cognitiveai.org/">Peter Jansen</a>
      <h6>University of Arizona</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://dnr2.github.io/academic_website/">
      <img class="people-pic" src="https://dnr2.github.io/academic_website/images/profile.jpg">
    </a>
    <div class="people-name">
      <a href="https://dnr2.github.io/academic_website/">Danilo Ribeiro</a>
      <h6>Amazon AWS</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://web.mit.edu/zyzzyva/www/academic.html">
      <img class="people-pic" src="https://web.mit.edu/zyzzyva/www/images/CathyWong_profile.png">
    </a>
    <div class="people-name">
      <a href="https://web.mit.edu/zyzzyva/www/academic.html">Lionel Wong</a>
      <h6>MIT</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://xiye17.github.io/">
      <img class="people-pic" src="https://xiye17.github.io/avatar.jpg">
    </a>
    <div class="people-name">
      <a href="https://xiye17.github.io/">Xi Ye</a>
      <h6>University of Texas, Austin</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://wenting-zhao.github.io/">
      <img class="people-pic" src="https://avatars.githubusercontent.com/u/8762524?v=4">
    </a>
    <div class="people-name">
      <a href="https://wenting-zhao.github.io/">Wenting Zhao</a>
      <h6>Cornell University</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://benlipkin.github.io/index.html">
      <img class="people-pic" src="https://benlipkin.github.io/assets/images/compressed-816x816.jpg">
    </a>
    <div class="people-name">
      <a href="https://benlipkin.github.io/index.html">Ben Lipkin</a>
      <h6>MIT</h6>
    </div>
  </div>
</div>
