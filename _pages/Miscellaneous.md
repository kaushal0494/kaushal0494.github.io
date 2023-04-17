---
layout: page
permalink: /Miscellaneous/
title: Miscellaneous
description: 
nav: true
nav_order: 3
---

<html>
<head>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<style>
		.project {
			width: 100%;
			padding: 10px;
			border: 1px solid #ccc;
			margin-bottom: 15px;
			box-sizing: border-box;
            height: 30%;  
		}
		.project1 {
			width: 100%;
			padding: 10px;
			border: 1px solid #ccc;
			margin-bottom: 20px;
			box-sizing: border-box;
            height: 28%;  
		}
		.boxp1 {
			border: 1px solid #ccc;
			padding: 10px;
			margin: 10px;
			display: none;
		}
		.boxp2 {
			border: 1px solid #ccc;
			padding: 10px;
			margin: 10px;
			display: none;
		}
		.boxp3 {
			border: 1px solid #ccc;
			padding: 10px;
			margin: 10px;
			display: none;
		}
		.boxp4 {
			border: 1px solid #ccc;
			padding: 10px;
			margin: 10px;
			display: none;
		}
		.boxp5 {
			border: 1px solid #ccc;
			padding: 10px;
			margin: 10px;
			display: none;
		}
		.boxp6 {
			border: 1px solid #ccc;
			padding: 10px;
			margin: 10px;
			display: none;
		}
		.boxp7 {
			border: 1px solid #ccc;
			padding: 10px;
			margin: 10px;
			display: none;
		}
		.boxp8 {
			border: 1px solid #ccc;
			padding: 10px;
			margin: 10px;
			display: none;
		}
		.headline {
			cursor: pointer;
			color: #0076df;
		}
		.show {
			display: block;
		}
	</style>
	<script>
		function toggleBox1() {
			var box = document.querySelector('.boxp1');
			box.classList.toggle('show');
		}
		function toggleBox2() {
			var box = document.querySelector('.boxp2');
			box.classList.toggle('show');
		}
		function toggleBox3() {
			var box = document.querySelector('.boxp3');
			box.classList.toggle('show');
		}
		function toggleBox4() {
			var box = document.querySelector('.boxp4');
			box.classList.toggle('show');
		}
		function toggleBox5() {
			var box = document.querySelector('.boxp5');
			box.classList.toggle('show');
		}
		function toggleBox6() {
			var box = document.querySelector('.boxp6');
			box.classList.toggle('show');
		}
		function toggleBox7() {
			var box = document.querySelector('.boxp7');
			box.classList.toggle('show');
		}
		function toggleBox8() {
			var box = document.querySelector('.boxp8');
			box.classList.toggle('show');
		}
	</script>
</head>
<body>
  <!-- Box for Research Internships-->
    <h1 class="headline" onclick="toggleBox6()">Research Internships</h1>
	<div class="boxp6">
    <div class="project">
			<h3>Microsoft India, Machine Translation Team</h3>
			<p>Research Intern, Auguest 2022 - December 2022 [ 5 Months ]</p>
      <p> <b>Topic:</b> Machine Translation for Extremely Low Resource Languages/Dialects</p>
		</div>
		<div class="project">
			<h3>Microsoft India, Auto-suggest Team</h3>
			<p>Research Intern, June 2021 - July 2021 [ 2 Months ]</p>
      <p> <b>Topic:</b> Trie Context Augmentation to improve Auto-suggestions for Bing Search Engine</p>
		</div>
		<div class="project">
			<h3>Nvidia AI Research Center India</h3>
			<p>Research Intern, May 2020 - Jan 2021 [ 9 Months ]</p>
      <p> <b>Topic:</b> Towards Unsupervised Cross-lingual Transfer and Generation for Indian Languages</p>
		</div>
	</div>
  <!-- Box for Experience -->
  <h1 class="headline" onclick="toggleBox1()">Experience</h1>
	<div class="boxp1">
		<h3> Data Scientist at <a href="https://ntwist.com/">NTwist</a>, India</h3>
		<p>AI Startup, July 2017 - March 2018 [9 Months]</p>
    <ol type="1">
      <li>Optimization and automation of Gas-plant production by modelling with Deep Reinforcement
 Learning and Deep Neural Networks. </li>
      <li>Attributes Correlation study in higher dimension.</li>
    </ol>
	</div>
  <!-- Box for Research Collaborations  -->
  <h1 class="headline" onclick="toggleBox7()">Research Collaborations</h1>
	<div class="boxp7">
    <div class="project">
			<h3>Microsoft India, Auto-suggest Team</h3>
			<p>Collaborator Under Microsoft Academic Grant (MAPG), July 2022 - June 2023 [ 1 Year ]</p>
      <p> <b>Topic:</b> Multilingual and Non-toxic Auto-suggestion Genenrations for Bing Search Engine</p>
		</div>
		<div class="project">
			<h3>Microsoft India, Auto-suggest Team</h3>
			<p>Collaborator Under Microsoft Academic Grant (MAPG), July 2021 - June 2021 [ 1 Year ]</p>
      <p> <b>Topic:</b> Trie Context Augmentation to improve Auto-suggestions for Bing Search Engine</p>
		</div>
	</div>
  <!-- Box Technical Advisor< -->
  <h1 class="headline" onclick="toggleBox2()">Technical Advisor</h1>
	<div class="boxp2">
		<h3> Technical Advisor at <a href="https://lendingkatalyst.com/">Lending Katalyst</a>, India</h3>
		<p>AI-NLP Startup in Legal Domain, February 2022- Present</p>
    <ol type="1">
      <li>Provide AI/NLP-oriented solutions for real-world use cases in the legal domain </li>
      <li>The problems are interdisciplinary in nature involving NLP, multilingual, legal domain and linguistic</li>
    </ol>
	</div>
  <!-- Box for Guest talk -->
  <h1 class="headline" onclick="toggleBox8()">Guest Talks</h1>
	<div class="boxp8">
    <div class="project1">
      <h5><b>[April 2022]</b> Guest Task at SCIS, University of Hyderabad, India</h5> <b>Topic:</b> Introduction to Deep-Learning through lenses of Natural Language Processing 
		</div>
    <div class="project1">
      <h5><b>[December 2021]</b> Guest Talk at SVECW college, Bhimavaram, AP, India</h5> <b>Topic:</b> Introduction to Deep Learning for Natural Language Processing [<b>100+</b> participants]
		</div>
    <div class="project1">
      <h5><b>[May 2021]</b> Guest Talk at ASIC, NLP Reading and Discussion Groups</h5> <b>Topic:</b> ZmBART: An Unsupervised Cross-lingual Transfer Framework for Language Generation
		</div>
    <div class="project1">
      <h5><b>[December 2020]</b> Guest Talk at Faculty Development Program on Data Science</h5> <b>Topic:</b> Introduction to RNN - Data Processing and Text Classification
		</div>
    <div class="project1">
      <h5><b>[November 2020]</b> Guest Talk at ACM IIT Hyderabad Student Chapter</h5> <b>Topic:</b>  Learning to Distract: Generation of incorrect options from Reading Comprehension MCQ
		</div>
  	</div>
  <!-- RESEARCH SERVICES < -->
  <h1 class="headline" onclick="toggleBox3()">Research Services</h1>
	<div class="boxp3">
    <ol type="1">
      <li><b>Reviewer:</b> ACL [2021-23], EMNLP [2021-22], ICLR [2021-22], AAAI [2021-22], ARR [2022-23], SIGTYPE [2021] and MLR [2021]</li>
      <li><b>Student Volunteer:</b> ACL [2020, 21, 22(in-person)], EMNLP [2020, 21, 22(head)], ICML [2020-21], ICLR [2020-21], NeuralPS [2020-21], NAACL [2021-22], CIKM [2020] and ACML [2022(lead)] </li>
      <li>Attended ACL [2020, 21, 22(in-person)], EMNLP [2020-22], NAACL [2021-22], ICLR [2020-21], ICML [2020-21], CIKM [2020-2021], NeuralPS [2020-21], ACML [2022 (In-person)] and CoDS-COMAD [2020(in-person), 21, 22, 23] </li>
      <li>Hybrid infrastructure (Airmeet) <b>head</b> for the ACML conference 2022</li>
      <li>Participated in <b>Google India Hackathon</b> at the Hyderabad office in Oct-2018</li>
      <li>Organizer of a one-day workshop on <b>Sara Translator and Recent Trends in NLP</b> in october 2016</li>
    </ol>
	</div>
  <!-- ACADEMIC HONORS & AWARDS < -->
  <h1 class="headline" onclick="toggleBox4()">Selected Academic Honors And Awards</h1>
	<div class="boxp4">
    <ol type="1">
      <li>Received a grant of 100K INR for attending the conference by IIT Hyderabad in <b>Exceptional Research Scholar</b> category</li>
      <li><a href="http://lcs2.iiitd.edu.in/CONSTRAINT-2021/"> Shared task best paper honorable mention</a> for our CONSTRAINT workshop of AAAI 2021 paper </li>
      <li><b>Microsoft and ACL Travel Grant:</b> Received travel grants to present our Meta-XNLG work in ACL 2022 in Dublin, Ireland</li>
      <li>Our <b>ZmBART</b> and <b>Meta-XNLG</b> papers are recognized as the premier papers from India by IKDD-ACM India. <a href="https://ikdd.acm.org/premier-papers.php/">[Link]</a></li>
      <li>Received <b>Student Travel Grant</b> to attend CODS-COMAD 2022 and 2023</li>
      <li>Received <b>fully-funded</b> summer school offers from <b>Oxford University ML Summer School</b> 2021, 2022 and 2023</li>
      <li><b>ACM SIGIR and ACM India-IARCS Grant 2020:</b> Received to present our CIKM 2020 work</li>
      <li><b>Suzuki Foundation Fellowship 2020 & 2021:</b> Fully funded visit to Shizuoka University, Japan, for a short research stay</li>
      <li><b>BBC & IITG Hackathon:</b> Received a fully paid trip for a Hackathon in Google office Gurugram, India by BBC India and IITG</li>
      <li>The <b>University of Tokyo and IITH workshop 2018:</b> Secured <b>2nd place</b> in the workshop (shared task) at IIT Hyderabad</li>
      <li>2014, 2015, and 2016 GATE qualified with <b>95+</b> percentile</li>
      <li>In high school, secured <b>2nd</b> place in Ballia district, Utter Pradesh, India</li>
      <li><b>Winning</b> caption of National Cadet Corps (NCC) in 8th grade.</li>
    </ol>
	</div>
  <!-- TEACHING ASSISTANTSHIP & MENTORSHIP < -->
  <h1 class="headline" onclick="toggleBox5()">Teaching Assistantship and Mentorship</h1>
	<div class="boxp5">
    <ol type="1">
      <li>Took <b>lectures/hands-on sessions</b> in the NLP/IR Course at IITH during 2020-2023</li>
      <li><b>TA at IITH:</b> NLP&IR (Spring’23, 45+ students), Information Retrieval (Fall’21, 25+ students), NLP (Spring’21, 110+ students), IR(Fall’20, 60+ students), NLP (Spring’’20, 45+ students), IR (Fall’19, 30+ students) and Algorithm (Spring’19, 120+ students)</li>
      <li><b>TA at UoH:</b> NLP (Fall’16, 20+ students) and Optimization Technique (Spring’17, 55+ students)</li>
      <li><b>Project Mentor at IITH:</b> NLP&IR (Spring’23, mentored 4 groups), IR (Fall’21, mentored 7 groups), IR (Fall’20, mentored 8 groups), NLP (Summar’20, mentored 4 groups), and NLP (Winter’19, mentored 2 Groups)</li>
    </ol>
	</div>
</body>