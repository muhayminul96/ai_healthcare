# Promise Without a Comparator: A Critical Synthesis of Five Perspectives on Artificial Intelligence in Mental Healthcare

*Synthesis paper draft*

---

## Abstract

Artificial intelligence has been positioned as a response to a mental health crisis defined by rising prevalence, workforce shortage, and unequal access. This paper synthesises five recent contributions to that literature — three narrative reviews of the AI-in-mental-health field (Shimada, 2023; El-Mashharawi et al., 2024; Alhuwaydi, 2024), one domain-specific review of conversational agents (Balcombe, 2023), and one philosophical analysis of whether AI should be adopted in psychiatry at all (Minerva & Giubilini, 2023). Read together, they converge on a familiar settlement: AI should complement rather than replace clinicians, and privacy, algorithmic bias, and dehumanisation are the principal risks. That consensus, we argue, is thinner than it looks. The reviews benchmark AI against an idealised clinician, while Minerva and Giubilini benchmark it against measured human performance — chance-level suicide prediction and antidepressants that barely outperform placebo — and reach materially different conclusions from the same evidence. Three further problems cut across the corpus: reported accuracy figures are anchored to diagnostic constructs whose validity only one paper interrogates; the evidence base is small-sample, short-follow-up, single-application, and almost entirely Anglophone; and digital technology appears as remedy while its documented role in worsening population mental health is largely absent. We propose four research directions addressing comparator design, adverse-event surveillance, human–AI collaboration trials, and participatory evidence generation outside high-income settings.

**Keywords:** artificial intelligence; mental healthcare; conversational agents; diagnostic validity; research ethics; evidence synthesis

---

## 1. Introduction

### 1.1 Background

The case for artificial intelligence in mental healthcare rests on an arithmetic that none of the five papers reviewed here dispute. Minerva and Giubilini (2023) cite Global Burden of Disease data showing a 48% rise in diagnosed mental disorders between 1990 and 2019, from roughly 654.8 million to 970.1 million cases across 204 countries, alongside a WHO-estimated global shortfall of 4.3 million mental health workers projected to reach 10 million by 2030 in low- and lower-middle-income countries. The economic figure they quote — $2.5 trillion annually, rising to $6 trillion by 2030 — is the kind of number that makes technological solutions look inevitable. Alhuwaydi (2024) frames the same picture from a service-delivery angle: fragmentation, stigma, funding gaps, and a digital divide that leaves marginalised populations furthest from care. Balcombe (2023), writing from Australia, notes that around 20% of adults there have a current mental disorder and 44% will over a lifetime.

Against that backdrop, AI arrives with a plausible offer. Machine learning can process data streams — speech, typing dynamics, social media text, wearable telemetry, neuroimaging — that clinicians cannot practically inspect. Conversational agents scale in a way that human therapists cannot. Predictive models operate continuously and cheaply. The distance from ELIZA in 1966, which Alhuwaydi (2024) marks as the field's origin point, to GPT-class systems is genuinely large.

### 1.2 Why These Five Papers

The five texts were not selected for topical similarity alone. They differ in a way that makes them productive to read against each other.

Shimada (2023), El-Mashharawi et al. (2024), and Alhuwaydi (2024) are broad narrative reviews surveying the full AI pipeline — screening, diagnosis, treatment, monitoring, prediction. They vary considerably in methodological rigour, which turns out to be analytically useful rather than merely regrettable. Balcombe (2023) narrows to conversational agents and, in doing so, engages seriously with regulation, harm, and the political economy of the technology. Minerva and Giubilini (2023) do something none of the others attempt: they set the empirical question aside, grant AI's technical claims for the sake of argument, and ask what follows normatively.

That last move is the reason the set works. Four papers ask *what can AI do?* One asks *what would it mean if it could?* The gap between those questions is where most of this synthesis lives.

### 1.3 Objectives

This synthesis addresses four questions:

1. Where do these authors agree about AI's capability in mental healthcare, and how well is that agreement evidenced?
2. Against what standard is AI performance being judged, and does the choice of standard change the conclusions?
3. What assumptions about psychiatric diagnosis, human empathy, and clinical responsibility are being carried unexamined across the corpus?
4. What would have to be true — methodologically and evidentially — before the field's optimism is warranted?

---

## 2. Literature Review and Comparative Analysis

### 2.1 Thematic Grouping

Rather than proceeding paper by paper, three lines of work are distinguishable.

**Line 1 — Capability inventories (Shimada, 2023; El-Mashharawi et al., 2024; Alhuwaydi, 2024).** These reviews catalogue what AI has been shown to do, organised by clinical function. All three cover early detection, personalised treatment planning, chatbots, predictive analytics, and NLP-based sentiment analysis. All three close with an ethics section listing privacy, bias, and the loss of the human element. The structural similarity is striking and, as argued below, partly explained by a shared and rather narrow citation base.

**Line 2 — Domain-specific critical appraisal (Balcombe, 2023).** Balcombe restricts scope to AI chatbots and gains depth for it. His organising construct — Human–Artificial Intelligence (HAI), in which multiple models operate with human input rather than a single algorithm acting alone — is the only positive design proposal in the corpus. He is also the only author to treat governance concretely, referencing Australia's voluntary AI Ethics Principles and Online Safety Act 2021, the EU's Digital Services and Digital Markets Acts, and OpenAI's proposals for pre-deployment risk assessment of frontier models.

**Line 3 — Normative and conceptual analysis (Minerva & Giubilini, 2023).** This paper accepts AI's promised capabilities as a stipulation and examines the consequences. Its most substantial contributions concern diagnostic categories and responsibility, discussed in §2.4.

### 2.2 Comparative Analysis Table

| Paper / Author | Core Methodology | Main Findings | Strengths | Limitations |
|---|---|---|---|---|
| **Shimada (2023)**, *Science Insights* — "The Role of Artificial Intelligence in Mental Health: A Review" | Narrative review. No stated search strategy, databases, inclusion criteria, or selection process. Single-author. | AI supports early detection via social media, browsing, and physiological data; chatbots extend access; predictive analytics can shift suicide prevention from reactive to proactive; personalised plans improve engagement and resource allocation. Ethics framed around privacy, bias, and dehumanisation. | Wide thematic coverage; accessible framing of the clinical use cases; consistently flags the need for AI to augment rather than supplant clinicians. | No reproducible method. Claims are asserted rather than quantified — almost no effect sizes, sample sizes, or accuracy figures appear. Critically, the section titled "Improved Access to Mental Health Services" argues that AI systems themselves experience "AI burnout," may develop "anxiety, depression, or other related conditions," and require coping strategies and mental health provision. The underlying source (Ashrafian, 2017) is a speculative philosophy-of-mind paper asking whether artificial intelligences could in principle suffer mental illness; Shimada converts that open metaphysical question into service-delivery recommendations without marking the shift. A review of clinical applications is the wrong venue for the claim, and its placement under an access heading — where readers expect patient access — compounds the error. |
| **Alhuwaydi (2024)**, *Risk Management and Healthcare Policy* — "Exploring the Role of AI in Mental Healthcare" | Narrative review with an explicit and reportable search strategy: PubMed, Saudi Digital Library, Google Scholar, Web of Science, IEEE Xplore; Boolean keyword combinations; English-language, five-year window; expert opinion, case studies, and grey literature excluded. | Synthesises specific quantitative anchors: 21–100% diagnostic effectiveness range across psychiatric conditions (Abd-Alrazaq et al. umbrella review); ~90% diagnostic accuracy from a 28-item decision support system (Tutun et al.); ~90% classification accuracy for schizophrenia from resting-state fMRI (Kalmady et al., EMPaSchiz). Reviews chatbot trials (MYLO, Wysa, Leora, Eleos Health). Ethical analysis extends to cybersecurity, "cyber-trauma," cultural sensitivity, and language barriers. | The most methodologically transparent of the three broad reviews. Ends with five explicitly enumerated knowledge gaps — a genuine contribution, since most reviews gesture at "further research" without specification. Raises equity beyond dataset composition, invoking multi-level anti-racism frameworks (R4P/3R). | Reported figures are reproduced from source reviews without interrogation; the 21–100% range in particular is accepted as evidence of promise when a range that wide is close to uninformative. Cites Shimada (2023) approvingly as evidence for AI's role in early screening. Restricted to English-language sources despite arguing for cultural and linguistic inclusivity. |
| **El-Mashharawi et al. (2024)**, *IJAER* — "AI in Mental Health: Innovations, Applications, and Ethical Considerations" | Described as a comprehensive literature review with thematic synthesis; sources from PubMed, IEEE Xplore, Google Scholar over the last decade. Six stated objectives. Self-reported limitations: publication bias, English-only, rapid technological change. | AI enhances diagnostic support via speech, text, and behavioural pattern analysis; chatbots deliver CBT with outcomes described as comparable to face-to-face therapy in some studies; predictive analytics anticipate readmission and self-harm risk; hybrid AI-plus-traditional models outperform either alone. | Clear objective-setting and explicit acknowledgement of publication bias and language restriction — an honesty many reviews omit. The consistent emphasis on integration with, rather than substitution for, existing care is well argued in the discussion. | Thematic synthesis is asserted rather than demonstrated; no coding framework, no article count, no selection flow. More seriously, the citation apparatus does not function. References 1–5 are placeholder entries with generic author names (Doe & Smith; Brown & Green; White & Black; Johnson & Davis; Lee & Kim), each carrying a DOI on the `10.1234/` test prefix. References 6–62 consist almost entirely of the authors' own prior work on unrelated subjects — expert systems for dermatological, agricultural, and paediatric complaints, neural networks for alphabet recognition and absenteeism. In-text attributions consequently resolve to unrelated sources: the 21–100% accuracy range is attributed to a placeholder entry, the ~90% decision-support figure to a 2016 expert system for video-game addiction, and the Wysa evaluation to a male infertility expert system. The substantive claims themselves are traceable and correct — they correspond to Abd-Alrazaq et al., Tutun et al., and Malik et al. as cited accurately by Alhuwaydi (2024) — but they are unsupported as presented, and the paper cannot be cited for any specific finding. |
| **Balcombe (2023)**, *Informatics* — "AI Chatbots in Digital Mental Health" | Narrative review structured on Demiris et al.'s four steps, guided by three pre-specified research questions from a journal editorial. Explicit databases (Scopus, ScienceDirect, Sage, ACM DL, PubMed, Google Scholar, IEEE Xplore), search string, and 2010–2023 inclusion window. Purposive selection, with heterogeneity given as the reason a systematic review was not attempted. | Woebot and Wysa show feasibility, engagement, and therapeutic-bond formation; chatbot attrition is lower than for other digital interventions, though dropout remains a concern. Counterweight evidence is given equal billing: an app-market overview found chatbots largely unable to recognise crisis situations, and "poor semantics" undermined contextual understanding; a chatbot was publicly implicated in a user's suicide. Development is driven by the technology side rather than by clinically trained researchers, and pattern-based versus hypothesis-driven epistemologies impede collaboration. | Uniquely balanced on benefit and harm. The only paper treating digital technology as part of the *causal* story in population mental health, citing evidence linking social media access to increased depression and anxiety and algorithmic filter bubbles to polarisation. Substantive engagement with regulation across jurisdictions. Recommendations are operational rather than aspirational. | Narrow scope by design — silent on neuroimaging, biomarkers, and non-conversational prediction. Inclusion of media articles alongside peer-reviewed work blurs evidentiary weight. The HAI construct, though promising, remains programmatic: no validation study, no specification of what optimal human–AI division of labour would look like in practice. Several economic and epidemiological figures are cited without scrutiny of the underlying methods, a weakness Balcombe elsewhere identifies in others. |
| **Minerva & Giubilini (2023)**, *Topoi* — "Is AI the Future of Mental Healthcare?" | Philosophical and ethical analysis. Explicitly brackets the empirical question, granting AI's claimed capabilities as a working assumption in order to isolate normative implications. | Human mental healthcare performs poorly on its own terms: psychiatrists predict suicide only marginally better than chance across 365 studies spanning 50 years, while an algorithm reportedly achieves ~85% accuracy at 24 months and ~92% at one week; antidepressants have been found only marginally superior to placebo. Identifies four mechanisms by which AI could help — circumventing poor self-awareness, bypassing stigma, serving patients for whom human contact impedes disclosure, and absorbing unmet demand. Raises two deeper issues: AI-derived data may render DSM-5 categories unfit for purpose, and practitioners may inherit a novel second-order responsibility for revising diagnostic criteria themselves. | The only paper to make the comparator explicit and defend it. The reframing — asking not "how many false positives does AI produce?" but "do they outweigh the false positives *and* false negatives humans produce?" — is the single most useful analytical move in the corpus. The DSM and responsibility arguments are original relative to the other four. | Deliberately non-empirical, so the strong performance figures it cites are accepted uncritically to serve the argument; the 92% one-week suicide prediction claim in particular receives no scrutiny of base rates or calibration. The stipulative assumption that AI delivers, while methodologically legitimate, means the paper cannot adjudicate whether any of this applies now. Equity is discussed thinly relative to the reviews. |

### 2.3 Areas of Consensus — and Why They Are Weaker Than They Appear

Four propositions recur across all five papers.

**AI should augment, not replace.** Shimada (2023) insists AI must bolster rather than supplant practitioners. El-Mashharawi et al. (2024) devote a results subsection to integration with traditional methods. Alhuwaydi (2024) states that ML and NLP are complementary techniques because the patient–provider relationship is critical. Balcombe (2023) frames chatbots as complementary tools. Even Minerva and Giubilini (2023) rank human–AI collaboration among their four scenarios.

The unanimity is less meaningful than it looks, because the four groups reach it by different routes. For the three reviews it functions as an axiom — asserted at the point where evidence would otherwise be required. For Balcombe it is a design principle with a proposed mechanism (HAI). For Minerva and Giubilini it is a contingent empirical hypothesis, one of four possible futures, and explicitly falsifiable. A consensus that some hold as premise and others as conclusion is not really a consensus at all.

**Privacy, data security, and algorithmic bias are the principal ethical risks.** Every paper lists them. Only Alhuwaydi (2024) and Balcombe (2023) go further — Alhuwaydi toward cybersecurity and the concept of "cyber-trauma" following data breaches, Balcombe toward cross-jurisdictional regulatory design. The others treat ethics as a closing checklist.

**Diverse and representative training data is necessary.** Universal agreement, universally under-specified. Alhuwaydi (2024) is the exception, citing an Imperial College report on the potential for AI to worsen healthcare disparities for ethnic minority populations in the UK, and invoking Golden et al.'s argument that model improvement alone cannot address structural racism.

**Empathy is the human residual.** All five treat empathy as the thing machines cannot supply. Minerva and Giubilini (2023) go furthest in saying it may be "conceptually impossible to encode in an algorithm" — and then, remarkably, cite work in which expert raters scored ChatGPT's responses to patient questions higher than physicians' on both quality *and* empathy. They do not resolve the tension. Nobody in the corpus does.

### 2.4 Points of Genuine Divergence

**The comparator problem.** This is the fault line. Shimada (2023), El-Mashharawi et al. (2024), and Alhuwaydi (2024) evaluate AI against an implicit ideal: an unbiased, private, empathic clinician whose judgement AI risks degrading. Bias, opacity, and dehumanisation are framed as risks AI *introduces*. Minerva and Giubilini (2023) invert this. Human practitioners are documented to be biased — they cite the under-diagnosis of autism in women as an example — and their predictive performance in the highest-stakes task available is close to chance. Their conclusion follows directly: "the bar might be set low enough to make even a mediocre AI good enough to improve mental healthcare delivery and outcomes."

Both framings can be defended. What cannot be defended is leaving the choice implicit, because it silently determines the verdict. A tool that is worse than an idealised clinician and better than an average one will be recommended or rejected purely on the basis of an unstated benchmark.

**Digital technology as cause or cure.** Balcombe (2023) stands alone in treating the technology sector as implicated in the epidemiology it proposes to treat, citing causal evidence that access to social media raised severe depression and anxiety among American college students and noting a sharp rise in suicide deaths among Americans aged 10–24 in the decade following. The other four papers write as though AI arrives into a mental health crisis rather than partly out of one. That asymmetry deserves more attention than it receives.

**The validity of the diagnostic target.** Minerva and Giubilini (2023) are alone in asking whether DSM-5 categories will survive contact with finer-grained AI-derived signals — speech patterns, typing dynamics, passive sensing data that no manual was built to accommodate. The implication is uncomfortable for the other four papers. If a model classifies schizophrenia at 90% accuracy, it has achieved 90% agreement with a construct whose validity is itself contested. Accuracy against a shaky standard is a measure of concordance, not of truth.

**What regulation is for.** Balcombe (2023) is the only author to note that regulation cuts both ways — that overly stringent rules could stifle innovation, that without international coordination developers will migrate to permissive jurisdictions, and that public trust in AI varies systematically, with populations in Brazil, India, China, and South Africa more accepting than Western publics. The other papers call for "clear frameworks" without confronting the coordination problem.

### 2.5 An Uncomfortable Observation About the Evidence Base

Reading the three broad reviews alongside each other reveals a circularity worth naming. El-Mashharawi et al. (2024) and Alhuwaydi (2024) present the same primary studies in largely the same order, citing the same figures — the 21–100% diagnostic range, the ~90% decision-support accuracy, the same chatbot evaluations of MYLO, Eleos Health, and Wysa, the same argument about low- and middle-income countries. The reviewed set is not independent of itself: Alhuwaydi (2024) cites both Shimada (2023) and Minerva and Giubilini (2023) as sources, so two of these five papers appear inside a third's evidence base.

Verification of the underlying bibliographies makes the problem sharper than mere overlap. El-Mashharawi et al.'s (2024) reference list does not support its own text. Its first five entries are placeholder records — authors named Doe and Smith, Brown and Green, White and Black, each with a DOI on the reserved `10.1234/` test prefix — and the remaining fifty-odd are the authors' prior work on unrelated topics. The in-text citation numbers therefore point to sources that have nothing to do with the claims they are attached to. Notably, the claims themselves are correct and traceable elsewhere in the corpus. Content and citation have come apart.

Errors of attribution are not confined to the weakest paper. Minerva and Giubilini (2023) report a survey in which psychiatrists across 22 countries viewed AI as a possible response to workforce shortage, and cite a Doraiswamy et al. scoping review of telehealth use during COVID-19 — a different study that does not contain that finding. The lapse is minor beside the preceding one, and the underlying claim is defensible from the correct source, but it appears in the most carefully argued paper of the five.

Narrative reviews citing narrative reviews citing a small pool of primary studies produce an appearance of accumulating evidence without the substance of it. Each citation adds apparent weight; none adds data. When the same handful of trials — several with small samples, short follow-up, and single-platform designs — underwrites three independent-looking reviews, and when the links between claim and source cannot be relied upon, the field's confidence outruns its evidence in two directions at once.

---

## 3. Research Gaps and Critical Synthesis

### 3.1 Theoretical Gaps

**The ground-truth problem goes almost entirely unaddressed.** Only Minerva and Giubilini (2023) confront it. Every accuracy figure in the corpus is anchored to clinician-assigned labels derived from a classification system with well-documented reliability and validity problems. This is not a peripheral concern — it determines what any performance metric means. A model that reproduces clinical judgement perfectly reproduces its errors perfectly.

**No theory of therapeutic mechanism.** The reviews report that chatbots reduce symptoms without asking why. Is it behavioural activation? Structured self-monitoring? Non-judgemental disclosure? Simple availability? Balcombe (2023) touches the question through "digital therapeutic alliance" but concedes the mechanism is unestablished. Without it, negative results cannot be interpreted and positive ones cannot be generalised.

**"Personalisation" is used without definition.** All five papers endorse moving beyond one-size-fits-all care. None specifies what personalisation means operationally, what data justify it, or how much heterogeneity in treatment effect actually exists to be exploited.

### 3.2 Methodological Gaps

**Base rates and calibration are absent.** No paper distinguishes accuracy from calibration, or discusses positive predictive value under low base rates. This matters most where the stakes are highest. A suicide prediction model reported at 92% accuracy over a one-week horizon, cited approvingly by Minerva and Giubilini (2023), operates against an event rate low enough that the positive predictive value could be very poor indeed. Minerva and Giubilini alone raise false positives, and even they frame the issue as cost comparison rather than as a statistical property of rare-event prediction.

**Short follow-up and single-platform designs.** Alhuwaydi (2024) states this plainly: most evidence rests on short-duration follow-up while conditions like schizophrenia require lifelong management, and most findings derive from a single app or web portal. His observation applies to his own review, and to El-Mashharawi et al.'s (2024), and to Balcombe's (2023).

**Almost no head-to-head comparison.** Given that the comparator question is the central analytical issue, the near-total absence of studies pitting AI against clinicians on the same cases, prospectively, is striking.

**No cost analysis.** Cost-effectiveness is invoked as motivation throughout and measured nowhere. Balcombe (2023) is sharpest here, questioning how forecasts of a 66.67% to 266.67% GDP uplift from AI in Australia were calculated. Nobody costs model development, validation, integration, monitoring, or the clinical labour absorbed by false positives.

**Language and geography.** All five papers restrict to English-language sources. Alhuwaydi (2024) writes from Saudi Arabia and El-Mashharawi et al. (2024) from Palestine; both argue for culturally sensitive AI while drawing on an evidence base generated almost entirely in Anglophone, high-income settings. The irony is not a criticism of the authors so much as a diagnosis of what is available to cite.

### 3.3 Practical Gaps

**No adverse event framework.** Balcombe (2023) reports that mental health chatbots were found largely incapable of identifying crisis situations, and recounts a case in which a chatbot was blamed for a user's death. These are treated as cautionary anecdotes. There is no reporting registry, no standardised crisis-response test, no post-market surveillance of the kind any medical device would require.

**Implementation science is missing.** Alhuwaydi (2024) notes that few studies evaluate collaboration between healthcare professionals and AI. Balcombe (2023) identifies the deeper obstacle: development is driven by technologists interested in mental health rather than by clinicians who are technologically fluent, and the two communities work in incompatible epistemic modes — pattern-based versus hypothesis-derived.

**Patient and stakeholder voice is largely absent.** Alhuwaydi (2024) lists this as his fifth knowledge gap; Balcombe (2023) calls for qualitative work on user needs and barriers. Neither can point to much existing evidence. The literature about patients contains very little from them.

**Responsibility remains unresolved.** Minerva and Giubilini (2023) push past the familiar responsibility gap to a subtler point: if AI-derived signals destabilise diagnostic categories, practitioners may become responsible not only for correct diagnoses but for correctly revising the criteria of correctness — a task that plausibly falls outside professional obligation and for which no one is trained. The other papers call for clear legal frameworks without engaging this.

---

## 4. Future Directions and Conclusion

### 4.1 Four Actionable Research Directions

**1. Prospective, comparator-explicit validation with pre-registered performance reporting.**
The field needs multi-site prospective studies in which AI models are evaluated against practising clinicians on identical cases, with outcomes and analysis plans registered in advance. Reporting should mandate base rates, calibration curves, positive and negative predictive values, and decision-curve or net-benefit analysis rather than accuracy alone. Where the target is a contested construct, studies should additionally report against functional outcomes — hospitalisation, treatment response, return to work — that do not depend on the label being correct. This addresses the comparator problem raised by Minerva and Giubilini (2023) and the sample-size and follow-up limitations enumerated by Alhuwaydi (2024) directly.

**2. Safety certification and adverse-event surveillance for conversational agents.**
Given documented failures of crisis recognition (Balcombe, 2023), conversational agents deployed for mental health support should face a standardised battery of red-team crisis scenarios — suicidal ideation expressed obliquely, through idiom, in non-English phrasing, by minors — with published pass thresholds. Deployment should carry mandatory adverse-event reporting to a public registry on the model of pharmacovigilance. The Eliza case should be the first entry in a surveillance system, not an anecdote in a discussion section.

**3. Trials of human–AI collaboration with the dyad as the unit of analysis.**
Balcombe's HAI proposal and Minerva and Giubilini's third scenario make the same wager from different directions: that the clinician-plus-AI configuration outperforms either alone. Nobody has tested it properly. Such trials should randomise the *configuration* rather than the tool, measure therapeutic alliance, disclosure, attrition, and clinician workload alongside symptom outcomes, and specify in the protocol who is accountable for which decisions. The responsibility question becomes tractable once it is operationalised as a design variable rather than debated in the abstract.

**4. Participatory, multilingual evidence generation anchored outside high-income settings.**
Every paper claims AI could serve low-resource contexts; none presents evidence generated in one. Priority should go to co-designed studies in low- and middle-income settings, conducted in local languages, with patients and families involved in defining outcomes before development rather than consulted after deployment. Equity outcomes — differential accuracy and differential access across demographic strata — should be pre-specified endpoints, not post-hoc subgroup checks. This responds to Alhuwaydi's (2024) fifth gap and to Golden et al.'s argument, which he cites, that model refinement alone cannot address structural inequity.

A fifth, more infrastructural suggestion follows from §2.5: the field would benefit from a living systematic review with enforced primary-source citation, breaking the pattern in which narrative reviews cite narrative reviews and confidence compounds without evidence accumulating.

### 4.2 Conclusion

The state of knowledge in this field is best described as a large volume of literature resting on a small volume of data. Read individually, each of the five papers reviewed here is reasonable. Read together, they reveal a discipline that has settled on its conclusions — AI is promising, it should complement clinicians, privacy and bias are the risks — with a confidence that the underlying evidence does not yet support.

Three things follow.

The first is that the comparator question is not a technicality. Minerva and Giubilini (2023) show that the same evidence supports very different verdicts depending on whether AI is measured against an ideal clinician or a real one, and their demonstration that human performance in suicide prediction is close to chance while antidepressants barely outperform placebo should unsettle anyone who invokes the human touch as a settled argument. That phrase is doing rhetorical work in the reviews where analytical work is needed.

The second is that accuracy figures against contested diagnostic categories mean less than they appear to. This is the deepest problem in the corpus and the one that receives least attention. Until it is confronted, a reported 90% is a statement about agreement with clinicians, not about clinical truth.

The third concerns intellectual hygiene, and it is the finding that should trouble readers most. Shimada's (2023) claim that AI systems experience burnout, anxiety, and depression and require coping strategies — a speculative philosophical question rendered as clinical recommendation — appeared in a peer-reviewed venue and was subsequently cited approvingly by Alhuwaydi (2024). El-Mashharawi et al. (2024) present a literature review whose citations do not connect to the sources they name, resting on a bibliography that opens with placeholder entries. Even Minerva and Giubilini (2023) misattribute a survey finding. Three separate failures of a single mechanism — the link between a claim and its warrant — surfaced in a corpus of five papers, and none was caught before publication. A field growing this fast, reviewed this loosely, will accumulate errors faster than it corrects them, and reviews are precisely the genre through which such errors propagate fastest. Anyone building on this literature should verify attributions against primary sources rather than trusting the reviews to have done it.

None of this argues against AI in mental healthcare. The need is real, the workforce shortfall is not closing, and some of the technical results — particularly in multimodal detection and in reaching people who will not or cannot speak to a human — are encouraging. The argument is narrower. What is missing is not enthusiasm but evidence of the specific kind that would let a clinician, a regulator, or a patient decide whether a given tool is worth using. Producing that evidence is slower and less exciting than surveying the promise. It is also the only thing that will resolve the question these five papers, in their different ways, all leave open.

---

## References

### Primary Sources (Papers Synthesised)

Alhuwaydi, A. M. (2024). Exploring the role of artificial intelligence in mental healthcare: Current trends and future directions — A narrative review for a comprehensive insight. *Risk Management and Healthcare Policy*, 17, 1339–1348.

Balcombe, L. (2023). AI chatbots in digital mental health. *Informatics*, 10(4), 82.

El-Mashharawi, H. Q., Alshawwa, I. A., Salman, F. M., Abu Al-qumboz, M. N., Abu-Nasser, B. S., & Abu-Naser, S. S. (2024). AI in mental health: Innovations, applications, and ethical considerations. *International Journal of Academic Engineering Research*, 8(10), 53–58.

Minerva, F., & Giubilini, A. (2023). Is AI the future of mental healthcare? *Topoi*, 42, 809–817.

Shimada, K. (2023). The role of artificial intelligence in mental health: A review. *Science Insights*, 43(5), 1119–1127.

### Note on Secondary Citation

The works below are cited within the five synthesised papers and are referenced in this synthesis at second hand. They have not been consulted in the original. Each entry records the reviewed paper through which it was encountered, and in-text use should be marked accordingly (e.g. "Walsh et al., 2017, as cited in Minerva & Giubilini, 2023"). Given the attribution failures documented in §2.5, any of these sources that carries argumentative weight should be retrieved and verified before the manuscript is submitted.

Bibliographic details are reproduced as they appear in the source papers; where a review's own citation was found not to support the claim attached to it, this is flagged in the entry.

No entries are drawn from El-Mashharawi et al. (2024), whose reference list contains placeholder records and unrelated self-citations rather than the sources its text invokes.

### Secondary References (Works Cited Within the Synthesised Papers)

Abd-Alrazaq, A., Alhuwail, D., Schneider, J., et al. (2022). The performance of artificial intelligence-driven technologies in diagnosing mental disorders: An umbrella review. *npj Digital Medicine*, 5(1), 87. *(via Alhuwaydi, 2024)*

Ahmed, Z., Mohamed, K., Zeeshan, S., & Dong, X. (2020). Artificial intelligence with multi-functional machine learning platform development for better healthcare and precision medicine. *Database*, 2020. *(via Alhuwaydi, 2024)*

Almohammed, O. A., Alsalem, A. A., Almangour, A. A., Alotaibi, L. H., Al Yami, M. S., & Lai, L. (2022). Antidepressants and health-related quality of life (HRQoL) for patients with depression. *PLoS ONE*, 17(4), e0265928. *(via Minerva & Giubilini, 2023)*

Ashrafian, H. (2017). Can artificial intelligences suffer from mental illness? A philosophical matter to consider. *Science and Engineering Ethics*, 23(2), 403–412. *(via Shimada, 2023 — a speculative philosophical paper, presented by Shimada as grounds for clinical service provision; see §2.2)*

Australian Bureau of Statistics. (2021). *National Study of Mental Health and Wellbeing.* *(via Balcombe, 2023)*

Australian Commission on Safety and Quality in Health Care. (2020). *National Safety and Quality Digital Mental Health Standards.* *(via Balcombe, 2023)*

Australian Government. (2023). *Australia's AI Ethics Principles.* Department of Industry, Science and Resources. *(via Balcombe, 2023)*

Australian Productivity Commission. (2020). *Mental Health.* *(via Balcombe, 2023)*

Ayers, J. W., Poliak, A., Dredze, M., et al. (2023). Comparing physician and artificial intelligence chatbot responses to patient questions posted to a public social media forum. *JAMA Internal Medicine*. *(via Minerva & Giubilini, 2023)*

Balcombe, L., & De Leo, D. (2021). Digital mental health challenges and the horizon ahead for solutions. *JMIR Mental Health*, 8, e26811. *(via Balcombe, 2023)*

Balcombe, L., & De Leo, D. (2023). The impact of YouTube on loneliness and mental health. *Informatics*, 10, 39. *(via Balcombe, 2023)*

Beatty, C., Malik, T., Meheli, S., & Sinha, C. (2022). Evaluating the therapeutic alliance with a free-text CBT conversational agent (Wysa): A mixed-methods study. *Frontiers in Digital Health*, 4, 847991. *(via Balcombe, 2023)*

Braghieri, L., Levy, R., & Makarin, A. (2022). Social media and mental health. *American Economic Review*, 112, 3660–3693. *(via Balcombe, 2023)*

Bryant, A. (2023). AI chatbots: Threat or opportunity? *Informatics*, 10, 49. *(via Balcombe, 2023 — source of the three guiding research questions)*

Buck, B., Scherer, E., Brian, R., et al. (2019). Relationships between smartphone social behavior and relapse in schizophrenia: A preliminary report. *Schizophrenia Research*, 208, 167–172. *(via Minerva & Giubilini, 2023)*

Corrigan, P. W., & Watson, A. C. (2002). Understanding the impact of stigma on people with mental illness. *World Psychiatry*, 1(1), 16. *(via Minerva & Giubilini, 2023)*

Curtin, S., & Garnett, M. (2023). *Suicide and homicide death rates among youth and young adults aged 10–24: United States, 2001–2021.* Centers for Disease Control and Prevention. *(via Balcombe, 2023)*

D'Alfonso, S. (2020). AI in mental health. *Current Opinion in Psychology*, 36, 112–117. *(via Minerva & Giubilini, 2023; Balcombe, 2023 — source of the personal sensing / NLP / chatbot tripartite framing)*

D'Alfonso, S., Santesteban-Echarri, O., Rice, S., et al. (2017). Artificial intelligence-assisted online social therapy for youth mental health. *Frontiers in Psychology*, 8, 796. *(via Alhuwaydi, 2024)*

Darcy, A., Daniels, J., Salinger, D., Wicks, P., & Robinson, A. (2021). Evidence of human-level bonds established with a digital conversational agent. *JMIR Formative Research*, 5, e27868. *(via Balcombe, 2023)*

Demiris, G., Oliver, D. P., & Washington, K. T. (2019). The foundations of behavioral intervention research in hospice and palliative care. In *Behavioral Intervention Research in Hospice and Palliative Care* (pp. 17–25). Academic Press. *(via Balcombe, 2023 — source of the four-step review method)*

Doraiswamy, S., Abraham, A., Mamtani, R., & Cheema, S. (2020). Use of telehealth during the COVID-19 pandemic: Scoping review. *Journal of Medical Internet Research*, 22(12), e24087. *(via Minerva & Giubilini, 2023 — cited there for a 22-country survey of psychiatrists' views on AI, which this scoping review does not report; see §2.5)*

Drysdale, A. T., Grosenick, L., Downar, J., et al. (2017). Resting-state connectivity biomarkers define neurophysiological subtypes of depression. *Nature Medicine*, 23(1), 28–38. *(via Minerva & Giubilini, 2023)*

Esteva, A., & Topol, E. (2019). Can skin cancer diagnosis be transformed by AI? *The Lancet*, 394(10211), 1795. *(via Minerva & Giubilini, 2023)*

European Commission. (2023). *The Digital Services Act package.* *(via Balcombe, 2023)*

Fiske, A., & Henningsen, P. (2019). Your robot therapist will see you now: Ethical implications of embodied artificial intelligence in psychiatry, psychology, and psychotherapy. *Journal of Medical Internet Research*, 21(5), e13216. *(via Minerva & Giubilini, 2023)*

FitzGerald, C., & Hurst, S. (2017). Implicit bias in healthcare professionals: A systematic review. *BMC Medical Ethics*, 18(1), 1–18. *(via Minerva & Giubilini, 2023)*

Fitzpatrick, K. K., Darcy, A., & Vierhile, M. (2017). Delivering cognitive behavior therapy to young adults with symptoms of depression and anxiety using a fully automated conversational agent (Woebot): A randomized controlled trial. *JMIR Mental Health*, 4, e19. *(via Balcombe, 2023)*

Franklin, J. C., Ribeiro, J. D., Fox, K. R., et al. (2017). Risk factors for suicidal thoughts and behaviors: A meta-analysis of 50 years of research. *Psychological Bulletin*, 143, 187–232. *(via Minerva & Giubilini, 2023 — source of the chance-level suicide prediction finding)*

GBD 2019 Mental Disorders Collaborators. (2022). Global, regional, and national burden of 12 mental disorders in 204 countries and territories, 1990–2019. *Lancet Psychiatry*, 9(2), 137–150. *(via Minerva & Giubilini, 2023)*

Gilleen, J., Greenwood, K., & David, A. S. (2010). Anosognosia in schizophrenia and other neuropsychiatric disorders: Similarities and differences. *Study of Anosognosia*, 1, 255–290. *(via Minerva & Giubilini, 2023)*

Gillespie, N., Lockey, S., Curtis, C., Pool, J., & Akbari, A. (2023). *Trust in artificial intelligence: A global study.* University of Queensland & KPMG Australia. *(via Balcombe, 2023)*

Golden, B., Asiodu, I. V., Franck, L. S., et al. (2022). Emerging approaches to redressing multi-level racism and reproductive health disparities. *npj Digital Medicine*, 5(1), 169. *(via Alhuwaydi, 2024 — source of the R4P/3R frameworks)*

Graham, S., Depp, C., Lee, E. E., Nebeker, C., Tu, X., Kim, H.-C., & Jeste, D. V. (2019). Artificial intelligence for mental health and mental illnesses: An overview. *Current Psychiatry Reports*, 21(11), 116. *(via Alhuwaydi, 2024; Balcombe, 2023; Shimada, 2023)*

Grote, T., & Berens, P. (2020). On the ethics of algorithmic decision-making in healthcare. *Journal of Medical Ethics*, 46(3), 205–211. *(via Minerva & Giubilini, 2023)*

Haque, M. D. R., & Rubya, S. (2023). An overview of chatbot-based mobile mental health apps: Insights from app description and user reviews. *JMIR mHealth and uHealth*, 11, e44838. *(via Balcombe, 2023; Shimada, 2023 — source of the crisis-recognition failure finding)*

He, Y., Yang, L., Qian, C., et al. (2023). Conversational agent interventions for mental health problems: Systematic review and meta-analysis of randomized controlled trials. *Journal of Medical Internet Research*, 25, e43862. *(via Balcombe, 2023)*

Hohenstein, J., Kizilcec, R. F., DiFranzo, D., et al. (2023). Artificial intelligence in communication impacts language and social relationships. *Scientific Reports*, 13, 5487. *(via Balcombe, 2023)*

Hyman, S. E. (2010). The diagnosis of mental disorders: The problem of reification. *Annual Review of Clinical Psychology*, 6, 155–179. *(via Minerva & Giubilini, 2023 — underpins the DSM validity argument)*

Inkster, B., Knibbs, C., & Bada, M. (2023). Cybersecurity: A critical priority for digital mental health. *Frontiers in Digital Health*, 5, 1242264. *(via Alhuwaydi, 2024 — source of the "cyber-trauma" concept)*

Joyce, D. W., Kormilitzin, A., Smith, K. A., & Cipriani, A. (2023). Explainable artificial intelligence for mental health through transparency and interpretability for understandability. *npj Digital Medicine*, 6, 6. *(via Balcombe, 2023)*

Kalmady, S. V., Greiner, R., Agrawal, R., et al. (2019). Towards artificial intelligence in mental health by improving schizophrenia prediction with multiple brain parcellation ensemble-learning. *npj Schizophrenia*, 5(1), 2. *(via Alhuwaydi, 2024 — the EMPaSchiz model)*

Kiener, M. (2022). Can we bridge AI's responsibility gap at will? *Ethical Theory and Moral Practice*, 25, 575–593. *(via Minerva & Giubilini, 2023)*

Le Glaz, A., Haralambous, Y., Kim-Dufor, D. H., et al. (2021). Machine learning and natural language processing in mental health: Systematic review. *Journal of Medical Internet Research*, 23(5), e15708. *(via Alhuwaydi, 2024; Shimada, 2023)*

Lee, E. E., Torous, J., De Choudhury, M., et al. (2021). Artificial intelligence for mental health care: Clinical applications, barriers, facilitators, and artificial wisdom. *Biological Psychiatry: Cognitive Neuroscience and Neuroimaging*, 6(9), 856–864. *(via Alhuwaydi, 2024; Shimada, 2023)*

Lim, S. M., Shiau, C. W. C., Cheng, L. J., & Lau, Y. (2022). Chatbot-delivered psychotherapy for adults with depressive and anxiety symptoms: A systematic review and meta-regression. *Behavior Therapy*, 53, 334–347. *(via Balcombe, 2023)*

Liu, G.-D., Li, Y.-C., Zhang, W., & Zhang, L. (2020). A brief review of artificial intelligence applications and algorithms for psychiatric disorders. *Engineering*, 6(4), 462–467. *(via Alhuwaydi, 2024)*

Loh, E. (2018). Medicine and the rise of the robots: A qualitative review of recent advances of artificial intelligence in health. *BMJ Leader*, 2, 59–63. *(via Minerva & Giubilini, 2023)*

Lucas, G. M., Rizzo, A., Gratch, J., et al. (2017). Reporting mental health symptoms: Breaking down barriers to care with virtual human interviewers. *Frontiers in Robotics and AI*, 4, 51. *(via Minerva & Giubilini, 2023)*

Malik, T., Ambrose, A. J., & Sinha, C. (2022). Evaluating user feedback for an artificial intelligence-enabled, cognitive behavioral therapy-based mental health app (Wysa): Qualitative thematic analysis. *JMIR Human Factors*, 9(2), e35668. *(via Alhuwaydi, 2024)*

Mastoras, R. E., Iakovakis, D., Hadjidimitriou, S., et al. (2019). Touchscreen typing pattern analysis for remote detection of the depressive tendency. *Scientific Reports*, 9, 13414. *(via Minerva & Giubilini, 2023)*

Mateu, A., Pascual-Sánchez, A., Martinez-Herves, M., Hickey, N., Nicholls, D., & Kramer, T. (2020). Cyberbullying and post-traumatic stress symptoms in UK adolescents. *Archives of Disease in Childhood*, 105(10), 951–956. *(via Alhuwaydi, 2024)*

Mental Health Commission of Canada. (2023). *Artificial intelligence in mental health services: Results from a literature review and an environmental scan.* *(via Alhuwaydi, 2024)*

Morrison, R. (2023). *WHO urges caution over use of generative AI in healthcare.* Tech Monitor. *(via Balcombe, 2023)*

Ognibene, D., Wilkens, R., Taibi, D., et al. (2023). Challenging social media threats using collective well-being-aware recommendation algorithms and an educational virtual companion. *Frontiers in Artificial Intelligence*, 5, 654930. *(via Balcombe, 2023 — the SMVC framework)*

OpenAI. (2023). *Frontier AI regulation: Managing emerging risks to public safety.* *(via Balcombe, 2023)*

Petersson, L., Larsson, I., Nygren, J. M., et al. (2022). Challenges to implementing artificial intelligence in healthcare: A qualitative interview study with healthcare leaders in Sweden. *BMC Health Services Research*, 22(1), 850. *(via Alhuwaydi, 2024)*

Purgato, M., Singh, R., Acarturk, C., & Cuijpers, P. (2021). Moving beyond a 'one-size-fits-all' rationale in global mental health: Prospects of a precision psychology paradigm. *Epidemiology and Psychiatric Sciences*, 30, e63. *(via Alhuwaydi, 2024)*

Rosenfeld, A., Benrimoh, D., & Armstrong, C. (2019). Big data analytics and AI in mental healthcare. *arXiv preprint.* *(via Alhuwaydi, 2024 — source of the gold-standard diagnosis argument)*

Sadeh-Sharvit, S., Camp, T. D., Horton, S. E., et al. (2023). Effects of an artificial intelligence platform for behavioral interventions on depression and anxiety symptoms: Randomized clinical trial. *Journal of Medical Internet Research*, 25, e46781. *(via Alhuwaydi, 2024 — the Eleos Health trial)*

Schwalbe, N., & Wahl, B. (2020). Artificial intelligence and the future of global health. *The Lancet*, 395(10236), 1579–1586. *(via Alhuwaydi, 2024)*

Sharma, A., & Verbeke, W. (2021). Understanding importance of clinical biomarkers for diagnosis of anxiety disorders using machine learning models. *PLoS ONE*, 16(5), e0251365. *(via Alhuwaydi, 2024)*

Straw, I., & Callison-Burch, C. (2020). Artificial intelligence in mental health and the biases of language based models. *PLoS ONE*, 15(12), e0240376. *(via Shimada, 2023)*

Tamim, B. (2023). *Belgian woman blames ChatGPT-like chatbot ELIZA for her husband's suicide.* Interesting Engineering. *(via Balcombe, 2023)*

The Lancet Global Health. (2020). Mental health matters. *Lancet Global Health*, 8(11), e1352. *(via Minerva & Giubilini, 2023 — source of the $2.5 trillion cost estimate)*

Timmons, A. C., Duong, J. B., Fiallo, N. S., et al. (2022). A call to action on assessing and mitigating bias in artificial intelligence applications for mental health. *Perspectives on Psychological Science*, 18, 1062–1096. *(via Balcombe, 2023)*

Tutun, S., Johnson, M. E., Ahmed, A., et al. (2023). An AI-based decision support system for predicting mental health disorders. *Information Systems Frontiers*, 25(3), 1261–1276. *(via Alhuwaydi, 2024)*

Vaidyam, A. N., Wisniewski, H., Halamka, J. D., Kashavan, M. S., & Torous, J. B. (2019). Chatbots and conversational agents in mental health: A review of the psychiatric landscape. *Canadian Journal of Psychiatry*, 64(7), 456–464. *(via Minerva & Giubilini, 2023; Balcombe, 2023; Shimada, 2023)*

van der Schyff, E. L., Ridout, B., Amon, K. L., Forsyth, R., & Campbell, A. J. (2023). Providing self-led mental health support through an artificial intelligence-powered chat bot (Leora) to meet the demand of mental health care. *Journal of Medical Internet Research*, 25, e46448. *(via Alhuwaydi, 2024; Balcombe, 2023)*

Walsh, C. G., Ribeiro, J. D., & Franklin, J. C. (2017). Predicting risk of suicide attempts over time through machine learning. *Clinical Psychological Science*, 5, 457–469. *(via Minerva & Giubilini, 2023 — source of the 85%/92% accuracy figures)*

Weizenbaum, J. (1966). ELIZA — a computer program for the study of natural language communication between man and machine. *Communications of the ACM*, 9(1), 36–45. *(via Alhuwaydi, 2024)*

World Health Organization. (n.d.). *Health workforce.* *(via Minerva & Giubilini, 2023 — source of the 4.3 million / 10 million shortage figures)*

Wrightson-Hester, A. R., Anderson, G., Dunstan, J., et al. (2023). An artificial therapist (Manage Your Life Online) to support the mental health of youth: Co-design and case series. *JMIR Human Factors*, 10, e46849. *(via Alhuwaydi, 2024 — the MYLO chatbot)*

Xu, H., Wu, X., & Liu, X. (2022). A measurement method for mental health based on dynamic multimodal feature recognition. *Frontiers in Public Health*, 10, 990235. *(via Alhuwaydi, 2024)*

Zener, D. (2019). Journey to diagnosis for women with autism. *Advances in Autism*, 5(1), 2–13. *(via Minerva & Giubilini, 2023)*

Zhang, W., Yang, C., Cao, Z., et al. (2023). Detecting individuals with severe mental illness using artificial intelligence applied to magnetic resonance imaging. *eBioMedicine*, 90, 104541. *(via Alhuwaydi, 2024)*
