---
layout: project
urltitle:  "Visually Grounded Interaction and Language (ViGIL)"
title: "Visually Grounded Interaction and Language (ViGIL)"
categories: nips, neurips, vancouver, canada, workshop, computer vision, natural language, grounding, interaction, machine learning, vigil, 2019, neurips19
permalink: /
bibtex: true
paper: true
acknowledgements: ""
---

<br>
<div class="row">
  <div class="col-xs-12">
    <center><h1>Visually Grounded Interaction and Language (ViGIL)</h1></center>
    <center>The fourth ViGIL workshop will not be held at NeurIPS 2020. Stay posted for updates!</center>
  </div>
</div>

<br />

<div class="row" id="intro">
    <div class="col-xs-12">
        <h2>Introduction</h2>
        <p>Language understanding, perception, and motor control have historically been studied independently in the AI community. For example, although various algorithms have been developed to tackle the task of object recognition (ResNet [1], EfficientNet [2]) and language modeling (BERT [3], XLNet [4], GPT-3 [5]) individually, these methods are still restricted to the modalities they are trained on. While systems for object recognition can identify and sort objects in an image into one of many categories, they are not aware of language – more notably, they are not even trained to capture or identify the compositional relationships between objects that language would afford. Likewise, language modeling systems are ungrounded; while they can generate humanlike text, they cannot be used out-of-the-box to caption an image. We posit that, first, for systems to have a better understanding of language and be able to interact in the real world, they must be embodied in physical environments, and be able to reason about various types of context, including vision, physics, and sound. Second, it might not even be possible for artificial agents to grasp concepts of intuitive physics (e.g., how does a weighing scale work?) or common sense (e.g., how do mirrors work?) unimodally from static corpora. Learning these concepts requires agency and careful interplay of multiple modalities and interaction. Concretely, in this workshop, we hope to make progress towards building intelligent systems that can effectively leverage information from multiple modalities to perform tasks in interactive and immersive environments.</p>
        <p>To this end, there has been recent interest in jointly combining language, perception, and other modalities and to cement them through interaction. These include vision-and-language navigation [6–10], embodied question answering [11–13], audio-visual navigation [14, 15], visual dialog [16–18], vision and touch in robotics [19–21], or language-based collaboration [22, 23]. However, the language grounding problem is still vastly challenging, an issue highlighted by many benchmarks where human-level performance is yet to be achieved [24, 25]. We believe that progress can be made by focusing future research on embodied learning (EmbodiedQA [12], StreetLearn [26], VideoNavQA [27], ALFRED [28], REVERIE [29]), curiosity-driven interaction (AI2-Thor [30]), reasoning beyond objects and their spatial relationships in a scene (VCR [31], CLEVRER [32]) and collaborating via language-based interactions (CVDN [33], Talk the Walk [34], CerealBar [35]).</p>
        <p>The goal of this workshop is to bring together scientists from diverse backgrounds – machine learning, computer vision, natural language processing, robotics, neuroscience, cognitive science, psychology, and philosophy – to share their perspectives on grounding, embodiment, and interaction. While related workshops focus on machine learning methods and narrow grounding applications, ViGIL provides a unique opportunity for interdisciplinary discussion. We hope to use this diversity to foster new ideas about how to learn and leverage grounding. This one-day session would enable in-depth conversations on understanding the boundaries of current work and establishing promising avenues for future work. Our workshop ultimately aims to bridge the scientific fields of human cognition and machine learning.</p>
    </div>
</div>

<div class="hide">

<br />

<div class="row" id="dates">
  <div class="col-xs-12">
    <h2>Important Dates</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <table class="table table-striped">
      <tbody>
        <tr>
          <td>Paper Submission Deadline</td>
          <td>TBD</td>
        </tr>
        <tr>
          <td>Decision Notifications</td>
          <td>TBD</td>
        </tr>
        <tr>
          <td>Workshop</td>
          <td>TBD</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<br />

<div class="row" id="cfp">
  <div class="col-xs-12">
    <h2>Call for Papers</h2>
  </div>
</div>

<div class="row">
    <div class="col-xs-12">
        <p>
          We invite high-quality paper submissions on the following topics:
        </p>
        <p>
            <ul>
    <li>grounded and interactive language acquisition;</li>
    <li>reasoning and planning in language, vision, and interactive domains;</li>
    <li>machine translation with visual cues;</li>
    <li>transfer learning in language and vision tasks;</li>
    <li>visual captioning, dialog, storytelling, and question-answering;</li>
    <li>visual synthesis from language;</li>
    <li>embodied agents: language instructions, agent co-ordination through language, interaction;</li>
    <li>language-grounded robotic learning with multimodal inputs;</li>
    <li>human-machine interaction with language through robots or within virtual world;</li>
    <li>audio-visual dialog systems;</li>
    <li>audio-visual scene understanding;</li>
    <li>novel tasks that combine language, vision, interactions, and other modalities;</li>
    <li>understanding and modeling the relationship between language and vision in humans;</li>
    <li>semantic systems and modeling of natural language and visual stimuli representations in the human brain.</li>
            </ul>
        </p>
    </div>
</div>

</div>

<hr />

<div class="row" id="organizers">
  <div class="col-xs-12">
    <h2>Organizers</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-6 col-lg-3">
    <a href="https://catalinacangea.netlify.app/">
      <img class="people-pic" src="{{ "/static/img/people/catalinacangea.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://catalinacangea.netlify.app/">Cătălina Cangea</a>
      <h6>University of Cambridge</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://abhishekdas.com">
      <img class="people-pic" src="{{ "/static/img/people/abhishek-das-dp.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://abhishekdas.com">Abhishek Das</a>
      <h6>Facebook AI Research</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://www.linkedin.com/in/drew-a-hudson">
      <img class="people-pic" src="{{ "/static/img/people/drew.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://www.linkedin.com/in/drew-a-hudson">Drew Hudson</a>
      <h6>Stanford</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://jacobkrantz.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/jacobkrantz.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://jacobkrantz.github.io/">Jacob Krantz</a>
      <h6>Oregon State University</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://www.cc.gatech.edu/~slee3191/">
      <img class="people-pic" src="{{ "/static/img/people/stefan.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://www.cc.gatech.edu/~slee3191/">Stefan Lee</a>
      <h6>Oregon State University</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://jiayuanm.com/">
      <img class="people-pic" src="{{ "/static/img/people/jiayuanmao.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://jiayuanm.com/">Jiayuan Mao</a>
      <h6>MIT</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://fstrub95.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/florianstrub.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://fstrub95.github.io/">Florian Strub</a>
      <h6>DeepMind</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="http://alanesuhr.com/">
      <img class="people-pic" src="{{ "/static/img/people/alane.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://alanesuhr.com/">Alane Suhr</a>
      <h6>Cornell</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="http://wijmans.xyz/">
      <img class="people-pic" src="{{ "/static/img/people/erikwijmans.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://wijmans.xyz/">Erik Wijmans</a>
      <h6>Georgia Tech</h6>
    </div>
  </div>
</div>

<hr>
<div class="row" id="scientific_committee">
  <div class="col-xs-12">
    <h2>Scientific Committee</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-6 col-lg-3">
    <a href="https://mila.quebec/en/person/aaron-courville/">
      <img class="people-pic" src="{{ "/static/img/people/aaron-courville-dp.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://mila.quebec/en/person/aaron-courville/">Aaron Courville</a>
      <h6>University of Montreal</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="http://www.mateuszmalinowski.com/">
      <img class="people-pic" src="{{ "/static/img/people/mateusz-malinowski-dp.jpeg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://www.mateuszmalinowski.com/">Mateusz Malinowski</a>
      <h6>DeepMind</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="http://www.lifl.fr/~pietquin/">
      <img class="people-pic" src="{{ "/static/img/people/olivier-pietquin-dp.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://www.lifl.fr/~pietquin/">Olivier Pietquin</a>
      <h6>Google Brain</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="http://www-etud.iro.umontreal.ca/~devries/">
      <img class="people-pic" src="/static/img/people/harmdevries.jpg" />
    </a>
    <div class="people-name">
      <a href="http://www-etud.iro.umontreal.ca/~devries/">Harm de Vries</a>
      <h6>University of Montreal | Element AI</h6>
    </div>
  </div>
</div>

<hr>
<div class="row">
  <div class="col-xs-12">
    <h2>Previous sessions</h2><a name="/prev_session"></a>
  </div>
</div>
<div class="row">
    <div class="col-xs-12">
        <p>
            <ul>
                <li><a href="https://nips2017vigil.github.io/">ViGIL Workshop at NeurIPS 2017</a></li>
                <li><a href="https://nips2018vigil.github.io/">ViGIL Workshop at NeurIPS 2018</a></li>
                <li><a href="https://vigilworkshop.github.io/2019">ViGIL Workshop at NeurIPS 2019</a></li>
            </ul>
        </p>
    </div>
</div>

<hr />

<div class="row">
  <div class="col-xs-12">
    <h2>References</h2>
  </div>
</div>
<div class="row">
  <div class="col-md-12">
    <ol>
<li>Kaiming He, Xiangyu Zhang, Shaoqing Ren, and Jian Sun. Deep Residual Learning for Image Recognition. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2016. </li>
<li>Mingxing Tan and Quoc V Le. Efficientnet: Rethinking Model Scaling for Convolutional Neural Networks. In International Conference on Machine Learning, 2019. </li>
<li>Jacob Devlin, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova. BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding. In Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers), 2019. </li>
<li>Zhilin Yang, Zihang Dai, Yiming Yang, Jaime Carbonell, Russ R Salakhutdinov, and Quoc V Le. XLNet: Generalized Autoregressive Pretraining for Language Understanding. In Advances in Neural information Processing Systems, 2019. </li>
<li>Tom B. Brown, Benjamin Mann, Nick Ryder, Melanie Subbiah, Jared Kaplan, Prafulla Dhariwal, Arvind Neelakantan, Pranav Shyam, Girish Sastry, Amanda Askell, Sandhini Agarwal, Ariel Herbert-Voss, Gretchen Krueger, Tom Henighan, Rewon Child, Aditya Ramesh, Daniel M. Ziegler, Jeffrey Wu, Clemens Winter, Christopher Hesse, Mark Chen, Eric Sigler, Mateusz Litwin, Scott Gray, Benjamin Chess, Jack Clark, Christopher Berner, Sam McCandlish, Alec Radford, Ilya Sutskever, and Dario Amodei. Language Models are Few-Shot Learners. arXiv:2005.14165, 2020. </li>
<li>Peter Anderson, Qi Wu, Damien Teney, Jake Bruce, Mark Johnson, Niko Sünderhauf, Ian Reid, Stephen Gould, andAnton van den Hengel. Vision-and-Language Navigation: Interpreting visually-grounded navigation instructions in real environments. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2018. </li>
<li>Weituo Hao, Chunyuan Li, Xiujun Li, Lawrence Carin, and Jianfeng Gao. Towards Learning a Generic Agent for Vision-and-Language Navigation via Pre-training. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2020.</li>
<li>Jacob Krantz, Erik Wijmans, Arjun Majumdar, Dhruv Batra, and Stefan Lee. Beyond the Nav-Graph: Vision-andLanguage Navigation in Continuous Environments. arXiv:2004.02857, 2020.</li>
<li>Qiaolin Xia, Xiujun Li, Chunyuan Li, Yonatan Bisk, Zhifang Sui, Jianfeng Gao, Yejin Choi, and Noah A Smith. MultiView Learning for Vision-and-Language Navigation. arXiv:2003.00857, 2020.</li>
<li>Yi Zhu, Fengda Zhu, Zhaohuan Zhan, Bingqian Lin, Jianbin Jiao, Xiaojun Chang, and Xiaodan Liang. Vision-Dialog Navigation by Exploring Cross-modal Memory. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2020. </li>
<li>Daniel Gordon, Aniruddha Kembhavi, Mohammad Rastegari, Joseph Redmon, Dieter Fox, and Ali Farhadi. IQA: Visual Question Answering in Interactive Environments. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2018. </li>
<li>Abhishek Das, Samyak Datta, Georgia Gkioxari, Stefan Lee, Devi Parikh, and Dhruv Batra. Embodied Question Answering. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops, 2018. </li>
<li>Abhishek Das, Federico Carnevale, Hamza Merzic, Laura Rimell, Rosalia Schneider, Josh Abramson, Alden Hung, Arun Ahuja, Stephen Clark, Gregory Wayne, et al. Probing Emergent Semantics in Predictive Agents via Question Answering. In Proceedings of the International Conference on Machine Learning, 2020. </li>
<li>Chuang Gan, Yiwei Zhang, Jiajun Wu, Boqing Gong, and Joshua B Tenenbaum. Look, Listen, and Act: Towards Audio-Visual Embodied Navigation. In Proceedings of the IEEE International Conference on Robotics and Automation, 2020. </li>
<li>Changan Chen, Unnat Jain, Carl Schissler, Sebastia Vicenc Amengual Gari, Ziad Al-Halah, Vamsi Krishna Ithapu, Philip Robinson, and Kristen Grauman. Audio-Visual Embodied Navigation. arXiv:1912.11474, 2019. </li>
<li>Harm De Vries, Florian Strub, Sarath Chandar, Olivier Pietquin, Hugo Larochelle, and Aaron Courville. GuessWhat?! Visual Object Discovery through Multi-modal Dialogue. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2017. </li>
<li>Abhishek Das, Satwik Kottur, Khushi Gupta, Avi Singh, Deshraj Yadav, José MF Moura, Devi Parikh, and Dhruv Batra. Visual Dialog. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2017.</li>
<li>Abhishek Das, Satwik Kottur, José MF Moura, Stefan Lee, and Dhruv Batra. Learning Cooperative Visual Dialog Agents with Deep Reinforcement Learning. In Proceedings of the IEEE/CVF International Conference on Computer Vision, 2017. </li>
<li>Oliver Kroemer, Christoph H Lampert, and Jan Peters. Learning Dynamic Tactile Sensing with Robust Vision-based Training. IEEE transactions on robotics, 27(3):545–557, 2011. </li>
<li>Martina Zambelli and Yiannis Demiris. Multimodal Imitation using Self-learned Sensorimotor Representations. In 2016 IEEE/RSJ International Conference on Intelligent Robots and Systems, 2016.</li>
<li>Roberto Calandra, Andrew Owens, Dinesh Jayaraman, Justin Lin, Wenzhen Yuan, Jitendra Malik, Edward H Adelson, and Sergey Levine. More Than a Feeling: Learning to Grasp and Regrasp Using Vision and Touch. IEEE Robotics and Automation Letters, 3(4):3300–3307, 2018. </li>
<li>Angeliki Lazaridou, Karl Moritz Hermann, Karl Tuyls, and Stephen Clark. Emergence of Linguistic Communication from Referential Games with Symbolic and Pixel Input. In International Conference on Learning Representations, 2018. </li>
<li>Angeliki Lazaridou, Anna Potapenko, and Olivier Tieleman. Multi-agent Communication meets Natural Language: Synergies between Functional and Structural Language Learning. In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, 2020. </li>
<li>Emily M. Bender and Alexander Koller. Climbing towards NLU: On Meaning, Form, and Understanding in the Age of Data. In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, 2020. </li>
<li>Yonatan Bisk, Ari Holtzman, Jesse Thomason, Jacob Andreas, Yoshua Bengio, Joyce Chai, Mirella Lapata, Angeliki Lazaridou, Jonathan May, Aleksandr Nisnevich, Nicolas Pinto, and Joseph Turian. Experience Grounds Language. arXiv:2004.10151, 2020. </li>
<li>Piotr Mirowski, Matt Grimes, Mateusz Malinowski, Karl Moritz Hermann, Keith Anderson, Denis Teplyashin, Karen Simonyan, Andrew Zisserman, Raia Hadsell, et al. Learning to Navigate in Cities Without Map. In Advances in Neural information Processing Systems, 2018. </li>
<li>Cătălina Cangea, Eugene Belilovsky, Pietro Liò, and Aaron Courville. VideoNavQA: Bridging the Gap between Visual and Embodied Question Answering. In Proceedings of the British Machine Vision Conference, 2019. </li>
<li>Mohit Shridhar, Jesse Thomason, Daniel Gordon, Yonatan Bisk, Winson Han, Roozbeh Mottaghi, Luke Zettlemoyer, and Dieter Fox. ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2020. </li>
<li>Yuankai Qi, Qi Wu, Peter Anderson, Xin Wang, William Yang Wang, Chunhua Shen, and Anton van den Hengel. REVERIE: Remote Embodied Visual Referring Expression in Real Indoor Environments. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2020. </li>
<li>Eric Kolve, Roozbeh Mottaghi, Daniel Gordon, Yuke Zhu, Abhinav Gupta, and Ali Farhadi. AI2-Thor: An Interactive 3D Environment for Visual AI. arXiv:1712.05474, 2017. </li>
<li>Rowan Zellers, Yonatan Bisk, Ali Farhadi, and Yejin Choi. From Recognition to Cognition: Visual Commonsense Reasoning. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2019. </li>
<li>Kexin Yi, Chuang Gan, Yunzhu Li, Pushmeet Kohli, Jiajun Wu, Antonio Torralba, and Joshua B. Tenenbaum. CLEVRER: Collision Events for Video Representation and Reasoning. In International Conference on Learning Representations, 2020. </li>
<li>Jesse Thomason, Michael Murray, Maya Cakmak, and Luke Zettlemoyer. Vision-and-Dialog Navigation. In Proceedings of the Conference on Robot Learning, 2020. </li>
<li>Harm de Vries, Kurt Shuster, Dhruv Batra, Devi Parikh, Jason Weston, and Douwe Kiela. Talk the Walk: Navigating New York City through grounded dialogue. arXiv:1807.03367, 2018. </li>
<li>Alane Suhr, Claudia Yan, Jack Schluger, Stanley Yu, Hadi Khader, Marwa Mouallem, Iris Zhang, and Yoav Artzi. Executing instructions in situated collaborative interactions. In Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP), pages 2119–2130, 2019. </li>
<li>Christopher D. Manning Drew A. Hudson. GQA: A New Dataset for Real-World Visual Reasoning and Compositional Question Answering. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2019. </li>
    </ol>
  </div>
</div>
