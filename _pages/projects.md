---
layout: page
permalink: /projects/
title: projects
description: Here I showcase some of my projects.
nav: false
---

<div class="publications"><ol class="bibliography"><li>
	<h2 class="year">2022</h2>	
		<!-- DP‑X‑COVID -->
		<div>
			<b>DP‑X‑COVID</b><br/>
			Privacy-preserving detection of COVID-19 in X-ray images using differential privacy and deep<br/>learning (CNN).
			<!-- Links/Buttons -->
			<div class="links">
				<a class="abstract btn btn-sm z-depth-0 waves-effect waves-light" role="button">Info</a>
				<a href="https://github.com/luckyos-code/DP-X-COVID" class="btn btn-sm z-depth-0 waves-effect waves-light" role="button" target="_blank" rel="noopener noreferrer">Code</a>
				<a href="/assets/pdf/Masters_Thesis_Lucas_Lange.pdf" class="btn btn-sm z-depth-0 waves-effect waves-light" role="button" target="_blank" rel="noopener noreferrer">Report</a>
			</div>
			<!-- Hidden abstract block -->
			<div class="abstract hidden">
				<p>
					Chest X-rays enable a fast and safe diagnosis of COVID-19 in patients. Applying Machine Learning (ML) methods can support medical professionals by classifying large numbers of images. However, the amount of data needed for training such classifiers poses problems due to clinical data privacy regulations, which present strict limitations on data sharing between hospitals. Specifically, the models resulting from ML are vulnerable to attacks and can compromise data integrity by leaking details about their training data. Privacy-Preserving ML (PPML) offers methods to create private models that satisfy Differential Privacy (DP), enabling the development of medical applications while maintaining patient privacy.
					<br/>
					This work aims at investigating the privacy-preserving detection of COVID-19 in X-ray images. The PPML training methods DP-SGD and PATE are matched against non-private training. The private models should mitigate the data leakage threats posed by Membership Inference Attacks (MIAs). However, the inclusion of DP showed no improvements in MIA defense on the COVID-19 detection task. Instead, the non-private models presented the same repelling properties as the private models. Thus, if only the defense against MIAs is of concern, the non-private approach achieving 97.6% classification accuracy is the best choice. Private DP-SGD training for $\varepsilon = 1$ is a more sensible alternative when a theoretical privacy guarantee is needed. The best DP-SGD model reaches 74.1% accuracy. Even though the accuracy-privacy trade-off of 23.5% is significant, the private model performs 0.3% better than related work and keeps much tighter privacy guarantees. Ultimately, the conflicting findings from the additional experiments on the MNIST database, where DP significantly increased MIA defense, indicate that PPML (or DP-SGD) is heavily task-dependent. Thus, research on one dataset might not carry over to others.
				</p>
			</div>
		</div>
	<h2 class="year">2021</h2>
	    <!-- X-COVID -->
		<div>
			<b>X‑COVID</b><br/>
			Binary and multiclass classification of COVID-19 in X-ray images using deep learning (CNN).
			<!-- Links/Buttons -->
			<div class="links">
				<a class="abstract btn btn-sm z-depth-0 waves-effect waves-light" role="button">Info</a>
				<a href="https://github.com/luckyos-code/X-COVID" class="btn btn-sm z-depth-0 waves-effect waves-light" role="button" target="_blank" rel="noopener noreferrer">Code</a>
			</div>
			<!-- Hidden abstract block -->
			<div class="abstract hidden">
				<p>
					Binary accurarcy (COVID‑19 vs. Normal): 97.8%<br/>
					Multiclass accurarcy (COVID‑19 vs. Pneumonia vs. Normal): 94.1%
				</p>
			</div>
	    </div>
	<h2 class="year">2020</h2>
		<!-- SentArg -->
		<div>
			<b>SentArg</b><br/>
			Argument retrieval model for Touché @ CLEF 2020 - 1st Shared Task on Argument Retrieval.
			<!-- Links/Buttons -->
			<div class="links">
				<a class="abstract btn btn-sm z-depth-0 waves-effect waves-light" role="button">Info</a>
				<a href="https://github.com/luckyos-code/ArgU" class="btn btn-sm z-depth-0 waves-effect waves-light" role="button" target="_blank" rel="noopener noreferrer">Code</a>
				<a href="http://ceur-ws.org/Vol-2696/paper_191.pdf" class="btn btn-sm z-depth-0 waves-effect waves-light" role="button" target="_blank" rel="noopener noreferrer">Report</a>
				<a href="https://webis.de/events/touche-20/shared-task-1.html" class="btn btn-sm z-depth-0 waves-effect waves-light" role="button" target="_blank" rel="noopener noreferrer">Task</a>
			</div>
			<!-- Hidden abstract block -->
			<div class="abstract hidden">
				<p>
					In this work we explore the yet untested inclusion of sentiment analysis in the argument ranking process. By utilizing a word embedding model we create document embeddings for all queries and arguments. These are compared with each other to calculate top-N argument context scores for each query. We also calculate top-N DPH scores with the Terrier Framework. This way, each query receives two lists of top-N arguments. Afterwards we form an intersection of both argument lists and sort the result by the DPH scores. To further increase the ranking quality, we sort the final arguments of each query by sentiment values. Our findings ultimately imply that rewarding neutral sentiments can decrease the quality of the retrieval outcome.
				</p>
			</div>
		</div>
		<br/>
		<!-- ShapBiRd -->
		<div>
			<b>ShapBiRd</b><br/>
			Shapes and workflow for Bibtex to RDF.
			<!-- Links/Buttons -->
			<div class="links">
				<a class="abstract btn btn-sm z-depth-0 waves-effect waves-light" role="button">Info</a>
				<a href="https://github.com/AKSW/shapbird" class="btn btn-sm z-depth-0 waves-effect waves-light" role="button" target="_blank" rel="noopener noreferrer">Code</a>
			</div>
			<!-- Hidden abstract block -->
			<div class="abstract hidden">
				<p>
					The ShapBiRd project was an effort at the Institute for Applied Informatics (InfAI) to create a linked data infrastructure and workflow for the institute’s bibliography.
				</p>
			</div>
		</div>
	<h2 class="year">2017</h2>
		<!-- AutoSlides -->
		<div>
			<b>AutoSlides</b><br/>
			Agile software engineering project on automatic slideshow creation.
			<!-- Links/Buttons -->
			<div class="links">
				<a class="abstract btn btn-sm z-depth-0 waves-effect waves-light" role="button">Info</a>
				<a href="https://github.com/AKSW/Auto-Slides" class="btn btn-sm z-depth-0 waves-effect waves-light" role="button" target="_blank" rel="noopener noreferrer">Code</a>
				<a href="https://aksw.org/Projects/AutoSlides.html" class="btn btn-sm z-depth-0 waves-effect waves-light" role="button" target="_blank" rel="noopener noreferrer">Website</a>
				<a href="/assets/pdf/Munich.pdf" class="btn btn-sm z-depth-0 waves-effect waves-light" role="button" target="_blank" rel="noopener noreferrer">Demo</a>
			</div>
			<!-- Hidden abstract block -->
			<div class="abstract hidden">
				<p>AutoSlides is a tool that will automatically create Powerpoint based slideshows, based on chosen topics. It uses several online resources, like DbPedia, Wikipedia and Flickr in order to search for relevant content and to produce meaningful slideshows.</p>
			</div>
		</div>
</li></ol></div>