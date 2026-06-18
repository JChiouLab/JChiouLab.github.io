---
layout: page
title: Research
description: read our stories
image: assets/images/Research.png
nav-menu: true
show_tile: true
---

<header>
	<div class=inner>
		<h1>Research</h1>
	</div>
</header>


<section id="research" class="spotlights">
	<section id="PatternFormation">
		<div class="content">
			<div class="inner">
				<h3>Patterning in an Interdisciplinary Field</h3>
				<p>Pattern formation is a critical and fascinating process in the development of multicellular organisms. Typically, a homogeneous egg or a piece of tissue requires certain proteins/mRNA to be spatially localized heterogeneously (patterned) to develop complex structures. The molecular pathways underlying different patterning systems are usually distinct depending on the system. However, they often follow similar pattern formation principles.</p>
				<p><span class="image left"><img src="assets/images/TuringTuring_thinshort.gif" style="width:200px;height:200px;"></span>The Turing pattern is a good example of pattern formation principles. In 1952, Alan Turing (yes, Benedict Cumberbatch in the <i>Imitation Game</i>) demonstrated that a system consisting of a slow-diffusing "activator" activating a fast-diffusing "substrate" can spontaneously generate patterns such as spots and strips. This pattern has been shown to underlie the patterning of pigments on animal coats, the development of animal digits, the distribution of trichomes on plant leaves, and even the vegetation in savanna landscapes.</p>
				<p>Since mathematical principles of pattern formation often transcend taxonomic boundaries and even spatial scales, why can't patterning also occur in 'unicellular' microbes? In our lab, we use interdisciplinary approaches including <b>live cell microscopy</b> and <b>mathematical modeling</b> to study the <b>principles of pattern formation</b> that play key roles in <b>microbial developmental processes</b>. Specifically, we focus on three aspects:</p>
			</div>
		</div>
	</section>

	<section id="CellPolarity">
		<div class="content">
			<div class="inner">
				<h3>Fungal Cell Polarity</h3>
				<p>Different cells develop in different cell polarity modes: Pollens only grow toward one direction to develop a single pollen tube, while neurons grow toward multiple directions when forming dendrites. Contrasting polarity modes as such originate from the different spatial patterns of polarity proteins within a single cell. Previous studies have shown that the mathematical principles that govern the patterning of polarity proteins in the budding yeast (a member of the Ascomycota phylum) follow that of a mass-conserved version of the Turing system, the system that generates the spots and stripes on your cat! However, a cat can have many spots and stripes, but the budding yeast always pattern their polarity proteins to produce only one bud per cell cycle. What is the underlying mechanism?</p>
				<p><span class="image right"><img src="assets/images/PLoSCompBio2018.png" style="width:200px;height:200px;"></span>The question of how cells control the number of polarity sites is as much a biological question as a mathematical one. If having multiple polarity sites is mathematically unstable, the polarity sites will compete with each other and eventually the largest one will be the only one remaining. In 2018, we published the conditions in a minimalistic Mass-conserved Turing model that determine the degree of instability of the polarity sites (<a href="d_Publications.html#2018PloSCompBio">Chiou et al., 2018, <i>PLoS Comp. Bio.</i></a>). Elucidating the underlying mathematical principles of yeast cell polarity has allowed us to genetically remodel the growth of budding yeast. We changed budding yeast cells from unipolar budding to multipolar growth, resembling lateral branching of fungal hyphae (<a href="d_Publications.html#2021ELife">Chiou et al., 2021, <i>eLife</i></a>).</p>
				<div class="row">
					<div class="6u 12u$(small)">
						<span><img src="assets/images/ResearchFigure2_wb.pdf" style="width:100%;height:auto;border-radius:4px;"></span>
					</div>
					<div class="6u 12u$(small)">
						<p>A second discovery from our 2021 paper is that if we consider a slightly more realistic version of the same mathematical model, more complicated polarity modes emerge from one single model. In addition to competition (where only one polarity site can last), there are scenarios of equalization (where multiple polarity sites can stably exist and equalize) and splitting (where even one polarity site is unstable). Coincidentally, genetic and genomic data confirmed that the entire Ascomycota phylum shares the same conserved polarity machinery. Despite that, Ascomycete fungi feature diverse polarity modes including unipolar budding in the budding yeast, New End Take Off (NETO) in the fission yeast, and apical hyphal branching in multiple filamentous fungi species, corresponding to theoretical predictions. Combining the two pieces of information from theory and experiments, we ask the bigger question: <b>What if the theoretical predictions on the stability of polarity sites correspond to diverse polarity modes of other Ascomycete fungi?</b></p> <p>Starting from the perspective of dynamic systems theory using partial differential systems, we test whether genetic evidence in each individual Ascomycete species would support the same theoretical framework. If that is the case, Ascomycota would become a model phylum in understanding diverse cell polarity modes in general. Experimentally, we focus first on the fission yeast <i>Schizosaccharomyces pombe</i>, which exhibits monopolar, bipolar, and oscillatory polarity dynamics during its cell cycle. We use an autamated image analysis to extract the population variation of cell polarity dynamics, and combine neural network approaches with dynamic modeling to dissect how the same polarity machinery can result in contrasting outcomes.</p>
					</div>
				</div>
			</div>
		</div>
	</section>

	<section id="PlantSyntheticBiology">
		<div class="content">
			<div class="inner">
				<div class="row">
					<div class="6u 12u$(small)">
						<h3>Synthetic Cell Polarity in Plants</h3>
						<p>If we truly understand the mathematical and physical principles of a Turing-based patterning system, we should be able to build it from scratch in an entirely foreign host. In this research direction, we aim to <b>synthetically build yeast cell polarity into plants</b>. Plants represent an ideal orthogonal system: they are evolutionarily distal to fungi, yet they share similar cell-wall-remodeling-based growth mechanics. This allows us to study cell polarity without the fitness constraints of native yeast cells, creating a clean platform for quantitative cell biology and bio-engineering.</p>
						<p>Our goals are to functionally validate the complete synthetic polarity module in plant root epidermal cells, titrate the relative expression levels of the modules to explore different numbers of polarity sites, and ultimately hijack plant exocytosis pathways to control root hair growth. This attempt would eventually allow us to optimize root hair growth mode for different argricultural contexts, and let us learn more about how the theoretical principles of polarity establishment is realized in a real polarity circuit.</p>
					</div>
					<div class="6u 12u$(small)">
						<span><img src="assets/images/ResearchFigure4_wb.pdf" style="width:100%;height:auto;border-radius:4px;"></span>
					</div>
				</div>
			</div>
		</div>
	</section>

	<section id="BiofilmDevelopment">
		<div class="content">
			<div class="inner">
				<div class="row">
					<div class="6u 12u$(small)">
						<span><img src="assets/images/ResearchFigure3_wb.pdf" style="width:600px;height:auto;"></span>
					</div>
					<div class="6u 12u$(small)">
						<h3>Biofilm Development</h3>
						<p>The general textbook impression of bacteria is that they are unicellular organisms. However, most bacterial species can in fact develop into multicellular communities called biofilms. Although each bacterium in a biofilm is an individual organism, biofilm as an entity shares many surprising features with true multi-cellular organisms. Studies have shown that Bacillus subtilis cells within a biofilm can communicate with each other through electrochemical signals similar to action potential within neurons. The latest research has shown that <i>B. subtilis</i> biofilms can develop concentric segments driven by molecular clocks in individual bacterial cells, similar to vertebrate somitogenesis, and use this pattern to control cell differentiation(<a href="d_Publications.html#2022Cell">Chou, Lee, Chiou et al., 2022, <i>Cell</i></a>). </p>
						<p>Cell-autonomous oscillations within individual cells are the driving forces of segmentation. However, when each cell has an independent clock, the expectation of the macroscopic pattern is a field of blurred noise. To generate concentric rings with sharp boundaries, a mechanism that synchronizes and couples the clocks has to exist, just like how fireflies on the same tree turn bright simultaneously. <b>How do molecular clocks talk to each other?</b> Would it be electrochemical signals? We are planning to solve the key problem of synchronization under microscopic live imaging.
						</p>
					</div>
				</div>
			</div>
		</div>
	</section>
</section>

