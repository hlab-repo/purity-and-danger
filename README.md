# Purity and Danger
Explorations of frame overlap between viral discourse and xenophobic discourse during and after the COVID-19 pandemic.

Terms of purity and danger, sameness and otherness, that operate in the semantic frame of medicine and health (e.g., infection, contagion, foreign body, im/pure, un/clean, un/scathed, distance, quarantine, abject) are also common in contexts of social identity and difference, especially in xenophobic projections of racial and ethnic otherness as threats to the integrity and wellbeing of individual and social bodies and their cultures. This project uses machine learning to explore possible relationships (e.g., statistical overlaps) between the uses of such language in these two different frames. We are particularly interested in how the prevalence of this viral othering language in the medical frame during the COVID-19 pandemic might lead to increased use of viral metaphors in racist and other xenophobic discourses. Is an increase in the former leading to an increase in the latter? Will it do so in years to come?

## Notes on Approaches

* mataphor project might have some overlap
    * virus metaphors applied to society
* similar to K means clustering --> takes all points in the embedding into account
* Instead, use a Bayes/Gaussian mixture (like L1 regularization) --> filters out features of embedding that aren't relevant
    * distance from centroid
* combine supervised data with unsupervised data
* categories = medical contagion, pre-covid contagion, post-covid contagion
* we are interested in anomoly detection - new uses of language post-covid
* Need to find examples of uses of these metaphors
    * small set of example sentences that contain metaphors of contagion applied to social groups or otherness
    * small set of examples sentences that contains metaphors of contagion NOT applied to social othering

Could we simply use the Allen corpus to look at increased frequency of language like foreigner?
