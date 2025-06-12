---
layout: single
permalink: /bachelorthesis/
---

# Mapping Bicycle Equity: A GIS-Tool for Analyzing Access to Cycling Infrastructure Across Social Groups

A short summary of my bachelor thesis

## ABSTRACT

Strategies on traffic transformation suggest improvements for bicycle-friendly cities. However, they often overlook whether all residents benefit from these changes. To address this, a GIS tool was developed to calculate a bicycle equity index for each place of residence in a city. The index shows the share of cycling infrastructure on everyday routes. With the aim to expand cycling infrastructure in a socio-political way, the work analyses correlations between the created bicycle equity index and social groups. In this case study the tool was applied to the city of Weimar, Germany. The findings show a correlation between a high bicycle equity index and milieus of the upper class as well as a correlation between a low bicycle equity index and milieus of the lower middle class. The tool does not only serve for research purposes but can be applied to any municipality by practitioners.

## INTRODUCTION

Flexible, cheap, climate-friendly and healthy – the list of positive attributes associated with cy-cling is ongoing (BMDV, 2022, p. 8). Expanding cycling infrastructure is a commonly chosen solution by many local councils to promote alternative modes of transport. While there are many studies proving the listed positive attributes of cycling, there is little research about who is benefiting from the advantages of cycling infrastructure (Johan de Hartog et al., 2010, p. 1109).

The aim of this work is to analyze the accessibility to cycling infrastructure across different social groups in the city of Weimar. So far, strategy papers on cycling infrastructure that were examined for this work propose technical improvements and evaluate their importance by a cost-benefit analysis (Lucas et al. 2015, p. 474). This work argues that investments in cycling infrastructure must also take a social-political perspective into account. For this, the concept of transport equity is applied to cycling and different understandings of justice will be discussed. The development of a GIS tool forms the main part and allows an empirical study of the accessibility to cycling infrastructure in the city of Weimar, Germany. This data-driven approach critically reflects on common decision processes for cycling infrastructure and draws attention to the potentials and limits of GIS analyses in socio-political contexts.

Existing social inequalities in the accessibility to transportation modes are discussed as “transport equity“ in various position papers by state agencies (Frey et al., 2020, p. 8), research associations (ARL 2023, p. 7) and scholars (Rammler and Schwedes 2018, p. 12), however this is mostly in relation to motorized private transport and public transport. Transport equity in the context of cycling has received little attention. Golub (2016, p. 2) outlines that for many people the bicycle is not an emancipatory tool but “the only reasonable travel option due to inadequate public transportation, complex travel needs, or low wages and high transportation costs”. Since several studies show that limited accessibility to transportation can restrict participation in social life (Rammler and Schwedes, 2018, p. 8; Fischer and Sommer, 2022, p. 28), the concept of transport equity needs to be further examined in the context of cycling.

Transferring transport equity to cycling planning is a very recent field of research, with the first publications appearing from 2015 onwards. Prelog (2015) examines the accessibility of cycling infrastructure in Chicago for discriminated groups. Her analysis is based on a GIS tool creating a buffer around bicycle facilities and then calculating the area of blocks within and outside the buffer (ibid.). Another GIS-based approach was developed by Braun, Rodriguez and Gordon-Larsen (2019, p. 1). Their index represents the distance to the nearest cycling facility in a direct line and is supplemented by a density index showing the coverage of the road network with cy-cling facilities (ibid., p. 5). So-called “bikeability” studies, which aggregate parameters such as bicycle route density, topography and destination density into an index, are criticized as being too imprecise (Haferburg and Kraudzun 2022, p. 141; Fischer and Sommer 2022, p. 30). On the one hand merging several parameters in one index makes the impact of each individual parameter less transparent (ebd.). On the other hand, the coverage of an area with cycling infrastructure does not display the connectivity of the infrastructure on routes between designated origins and destina-tions. A route-based approach was presented by Caggiani et al. (2019, p. 63). The mathematical model defines the shortest route along the road network and measures its proportional coverage with cycling facilities (ibid.). A GIS tool and thus the transfer of the mathematical model into practice is not included. Fischer and Sommer (2022, p. 30) carried out such a route-based analysis using GIS and applied it to Langenhagen, Germany. Their findings show that households with a lower economic status find less separated cycling lanes on their daily routes (ibid., p.32).

## METHODOLOGY

The GIS tool developed in this work uses a route-based approach and calculates a bicycle equity index for different places of residence as well as for different social groups. To elaborate the calculation, the underlying concept of what a fair distribution of cycling infrastructure implies, is discussed. Existing mobility-related literature lacks a critical engagement with justice principles that explain why the benefits and burdens of transportation are seen as unfairly distributed (Pereira, Schwanen and Banister, 2017, p. 13). So far, a utilitarian understanding of justice is one of the “most popular current methods for evaluating the impacts of transport policy” (Lucas et al. 2015, p. 474). A cost-benefit-analysis defines an action as morally right if the total amount of good is greater than the total amount of bad (Sinnott-Armstrong, 2003, n.p.). The most frequently cited criticism of utilitarianism is that of the political philosopher John Rawls (Pereira et al., 2017, p. 17; Lucas et al., 2015, p. 477). Rawls (1971/1975, p. 44) criticizes that the utilitarian distribution of costs and benefits is not considered among individuals. This is problematic if the aggregated welfare falls at the expense of the group with the least benefit (ibid., pp. 19-20). Rawls formulates principles based on the assumption that basic goods need to be allocated among society (ibid., p. 83). In contrast to utilitarianism, a fair considered distribution pattern does not focus on the wellbeing of all, but on the greatest possible advantage for the least advantaged group of people (ibid., p. 336).

This paper therefore presents an approach to how cycling infrastructure can be improved so that the most disadvantaged group benefits most. For this, a statistical analysis examines possible social inequalities by calculating correlations between the bicycle equity index and different social groups. Other than existing approaches, social groups are not reduced to a binary classification of economically deprived and not-deprived households but consider SINUS milieus. SINUS milieus are a social strata approach developed by SINUS Institute in the 1980s, which is still being further developed today and serves market research (Geißler, 2014, n.p.). People are grouped based on similar values and lifestyles as well as a comparable social situation which assigns them to “groups of like-minded people” (Sinus Markt- und Sozialforschung GmbH, 2024, n.p.). However, with the modernization of society, there is also growing criticism: Individualization and diversification make typical class mentalities dissolve, so that people identify less with a particular milieu (Geißler, 2014, n.p.). This critique is countered with the objection that social stratum of modern society is not disappearing but has become more dynamic and pluralistic (ibid.). For the application of the milieu approach in justice research, it is assumed that milieu-specific resources lead to unequal opportunities in life and participation (Höblich, 2012, p. 10).

The GIS tool automatically calculates a bicycle equity index for each place of residence using predefined input data (Fig. 1). The index shows the share of bicycle-friendly infrastructure on everyday routes from 0 % to 100 %. A high bicycle equity index corresponds to a high share of bicycle-friendly infrastructure along the routes. Everyday journeys are defined as cycling trips between home and daily necessities. All places of residence are represented in a grid of hexagons. The tool calculates the shortest route from all locations in the grid to the three nearest points of each destination category. Destination categories can be freely chosen, e.g. food supply, health care or education. For this case study the mobility survey “Mobilität in Deutschland” (Kuhnimhof and Nobis, 2018, p. 61) as well as transport accessibility studies (Burgdorf, Krischausky and Müller-Kleißler, 2015, p. 3) and time use surveys (Eurostat, 2022, n.p.) were analyzed to identify destination categories. The tool allows for customization by weighing destination categories individually. By assigning a weight between zero and one to each category, users can tailor the bicycle equity index to reflect the specific needs of different user groups. The named surveys give insight into the most frequented destinations. For a customized weighting, destinations that are higher frequented by the group of interest than other destinations receive a weight closer to one. In this case study a simplified approach is chosen that includes the four most frequented destinations without differentiating between gender, age or other characteristics. Supermarkets and services in the city center appear as some the most frequented destinations followed by schools and doctors. Exemplary supermarkets and the city center are weighed by 0.35 each and schools and doctors by 0.15 each.

![Necessary input layer](/assets/images/BA_layer.png)

*Figure 1: Necessary input data (Own figure)*

Qualitive characteristics of cycling infrastructure might vary and characteristics such as width, surface, traffic volume and proximity to other vehicles influence people´s perception on safety differently. Nevertheless, the tool treats all forms of cycling infrastructure equally. This is because the main goal of the tool is to analyze whether all social groups can equally access their daily needs with the existing cycling network. The tool serves as an aid to identify locations where no cycling infrastructure is present but needed to improve the accessibility of the least advantaged group. A statement about what type of cycling infrastructure is needed at these locations requires more detailed information about the street spatial conditions and goes beyond the tool's objective. This focus also leads to the decision underlying the shortest route calculation: Since the index represents the share of bicycle-friendly infrastructure, the shortest route is measured by distance and not by travel time and therefore disregards the topography.

## RESULTS OF EXAMPLE IMPLEMENTATION AND DISCUSSION

The city of Weimar is represented in the model by 3189 hexagons (Fig. 2). On average, the index is 40 %. This means that on average, people can cycle 40 % of their everyday journeys on bicycle-friendly infrastructure. Figure 2 reveals that this index is unequally distributed and that there are fluctuations of between 6 % and 81 % around the mean value. The highest index is found in the southern part of the city.

![Map showing Biycycle Equity Index](/assets/images/BA_index.png)

*Figure 2: Bicycle-Equity Index of Weimar (Own figure)*

Data on the SINUS milieus is stored in many data points that represent a different number of households each. Each data point contains the probability with which a certain milieu lives in that place. For the correlation analysis, data points are weighed by the number of households they represent. Similar to the bicycle equity index, the highest share of upper-class milieus is found in the southern part of the city.

To analyze possible correlations between the bicycle equity index and the social milieus a Pearson correlation has been performed. While there is a positive correlation between milieus of the upper class and the bicycle-equity index, there is a negative correlation between milieus of the lower class and the index. In other words, a high likelihood of upper-class milieus living in a place correlates with a high coverage of cycling infrastructure on everyday routes. On the contrary, a high likelihood of lower-class milieus correlates with a low coverage of cycling infrastructure on everyday routes. Figure 3 shows the scatter plots of the milieus with the highest and lowest correlations. Given the high percentage of households without a car among lower-class milieus, it means that those more reliant on cycling have less access to bike-friendly infrastructure (Sinus Markt- und Sozialforschung GmbH, 2022, pp. 11–15). However, the correlation coefficient varies between 0.21 to 0.29 and -0.3 to -0.2, respectively. So, one can only speak of a weak correlation (Wewel, 2011, p. 88). For further research purposes, the tool can be implemented in additional municipalities to examine whether similar correlations appear elsewhere.

![Scatterplot of different milieus](/assets/images/BA_scatterplot.png)

*Figure 3: Correlation analysis of the milieus with the highest and lowest correlation (Own figure)*

In practice, decisions must be taken from these findings as to where infrastructure should be expanded. Based on the available data, places of residence as well as corresponding social milieus that benefit little from the existing cycling infrastructure can be identified. A closer look at which routes connect these locations and milieus to the chosen destinations exposes road sections where bicycle-friendly infrastructure is missing. To determine the potential influence of an improvement on this section, the road can be added to the bicycle network and the index can be recalculated. With this socio-political perspective the analysis makes an important contribution to traffic planning that has previously been neglected but does not claim exclusivity alongside criteria such as safety, environmental impact, and cost-effectiveness.

## CONCLUSION

Flexible, cheap, climate-friendly and healthy – this initial list of positive attributes of cycling highlights important prerequisites for a successful transition in transport. This work shows that the list is not complete. Cycling must be socially equitable and accessible to all. While the term 'transport equity' is becoming a buzzword in policy concepts, there is no common understanding of this concept.

In this paper, bicycle equity refers to the distribution of cycling infrastructure and its accessibility to different social groups: The application of the tool for practitioners described here identifies disadvantaged environments for cycling and then finds route sections where a bicycle-friendly adaptation would lead to an improvement. The tool can be seen as a contribution to a broader understanding of transport equity, which includes the ability of individuals to afford transport, to participate in decision-making and to feel safe when using different modes (Karner et al. 2020, p. 440). The approach presented shows how existing geodata can be used to provide substantial support for planning and policy discussions on 'transport equity'.

Many assumptions have been made that can be adapted or further differentiated when applied to other areas. The more complex the algorithms of a tool are, the more difficult it becomes for third party users to understand the processing of input data and to interpret the output data correctly. Therefore, finding a balance between a tool that is as realistic and complex as possible and one that is user-friendly is crucial for its further development and implementation. For example, not all routes start from home; they may connect work, sports, and shopping without returning home. These complex travel chains are not accounted for in the current model. Further research is needed to examine the potential impact of travel chains on the model.

In general, cities are becoming increasingly digital. As a result, the use of GIS for urban planning issues will become important. Particularly in Germany, there is still a need for the digital provision of open data in municipalities according to common standards (Deutscher Städtetag, 2020, p. 3). This would also ensure transparency with regard to the timeliness and quality of the data, such as accuracy or completeness (ibid, p. 5).

---

## REFERENCES

Akademie für Raumentwicklung in der Leibniz-Gemeinschaft (Ed.). 2023. Mobilität, Erreich-barkeit und soziale Teilhabe – Für eine gerechtere Raum- und Verkehrsentwicklung (144). Han-over. https://www.arl-net.de/system/files/pdf/2023-12/pospapier_144.pdf.

Braun L. M., Rodriguez D. A. & Gordon-Larsen P. 2019. Social (in) equity in access to cycling infrastructure_ Cross-sectional associations between bike lanes and area-level sociodemo-graphic characteristics in 22 large U.S. cities. Journal of Transport Geography, Vol. 80, pp. 1–10. https://doi.org/10.1016/j.jtrangeo.2019.102544.

Burgdorf M., Krischausky G. & Müller-Kleißler R. 2015. Indikatoren zur Nahversorgung. BBSR-Analysen KOMPAKT 10/2015. Bundesinstitut für Bau-, Stadt- und Raumforschung. https://www.bbsr.bund.de/BBSR/DE/veroeffentlichungen/analysen-kom-pakt/2015/AK102015.html.

Caggiani L., Camporeale R., Binetti M. & Ottomanelli M. 2019. An urban bikeway network de-sign model for inclusive and equitable transport policies. Transportation Research Procedia, Vol. 37, pp. 59–66. https://doi. org/10.1016/j.trpro.2018.12.166.

Eurostat. 2022. Time spent, participation time and participation rate in the main activity by sex and age group. https://doi.org/10.2908/TUS_00AGE.

Fischer A., Sommer C. 2022. Entwicklung einer GIS-basierten Methode zur Analyse der Mobi-litätsgerechtigkeit – am Beispiel des Radverkehrs für die Kommune Langenhagen in der Region Hannover. Journal für Mobilität und Verkehr, Vol. 14, pp. 28–42. doi:10.34647/jmv.nr14.id90.

Frey K., Burger A., Dziekan K., Bunge C. & Lünenbürger B. 2020. Verkehrswende für ALLE. So erreichen wir eine sozial gerechtere und umweltverträglichere Mobilität. 

Umweltbundesamt. Dessau-Rosslau. https://www.umweltbundesamt.de/sites/default/files/medien/376/publikatio-nen/2020_pp_verkehrswende_fuer_alle_bf_02.pdf

Geißler R. 2014. Facetten der modernen Sozialstruktur. Bundeszentrale für politische Bildung. https://www.bpb.de/shop/ zeitschriften/izpb/sozialer-wandel-in-deutschland-324/198045/facet-ten-der-modernen-sozialstruktur/.

Golub A., Hoffmann M. F., Lugo A. E. & Sandoval G. F. (Eds.). 2016. Bicycle Justice and Ur-ban Transformation. Biking for All? (Routledge equity, justice and the sustainable city). London & New York: Routledge, Taylor & Francis Group. https://doi.org/10.4324/9781315668840.

Haferburg C. & Kraudzun T. 2022. Bikeability-Studien und Radwegplanung von unten. Akade-mische und aktivistische Interventionen zur Verkehrswende. In F. Dammann & B. Michel (Eds.), Handbuch kritisches Kartieren, pp. 139–156. transcript Verlag.

Höblich, D. 2012. Soziale Gerechtigkeit: Eine multidisziplinäre Einführung. https://osa.basa-online.de/wp-content/uploads/2018/09/Basistext-o6_neu.pdf.

Johan de Hartog J, Boogaard H, Nijland H, Hoek G. 2010. Do the health benefits of cycling out-weigh the risks? Environ Health Perspect. Vol. 118, No. 8, pp. 1109-16. doi: 10.1289/ehp.0901747.

Karner A., London J., Rowangould D. & Manaugh K. 2020. From Transportation Equity to Transportation Justice: Within, Through, and Beyond the State. Journal of Planning Literature, Vol. 35, No. 4, pp. 440-459. https://doi.org/10.1177/0885412220927691

Kuhnimhof T. & Nobis C. 2018. Mobilität in Deutschland – MiD. Ergebnisbericht. Bonn, Ber-lin: BMVI, infas, DLR, IVT, infas 360. https://www.mobilitaet-in-deutschland.de/ar-chive/pdf/MiD2017_Ergebnisbericht.pdf.

Lucas K., Van Wee B. & Maat K. 2015. A method to evaluate equitable accessibility: combin-ing ethical theories and accessibility-based approaches. Transportation, Vol. 43, No. 3, pp. 473–490. https://doi.org/10.1007/s11116- 015-9585-2.

Pereira R. H. M., Schwanen T. & Banister D. 2017. Distributive justice and equity in transporta-tion. Transport Reviews, Vol. 37, No. 2, pp. 1–31. https://doi. org/10.1080/01441647.2016.1257660.

Prelog R. 2015. Equity of Access to Bicycle Infrastructure. GIS methods for investigating the equity of access to bike infrastructure. League of American Bicyclists. https://is-suu.com/bikeleague/docs/bicycle_equity_index_final_web.

Rammler S. & Schwedes O. 2018. Mobilität für alle! Gedanken zur Gerechtigkeitslücke in der Mobilitätspolitik (1. ed.). Berlin: Friedrich-Ebert Stiftung. Forum Berlin. https://www.fes.de/po-litischer-dialog/politische-bildung-und-dialog/artikelseite/mobilitaet-fuer-alle-gedanken-zur-ge-rechtigkeitsluecke-in-der-mobilitaetspolitik-1.

Rawls J. 1975. Eine Theorie der Gerechtigkeit (H. Vetter, Trans.) (1. ed.). Suhrkamp (Original work published 1971).

Schwarze, B. (2015). Eine Methode zum Messen von Naherreichbarkeit in Kommunen: Erreich-barkeit als strategisches Ziel von Raum- und Verkehrsplanung: ein Ansatz zur Evaluation von Naherreichbarkeit in Kommunen. [Doctoral dissertation, TU Dortmund]. https://eldorado.tu-dortmund.de/handle/2003/34458.

Sinnott-Armstrong W. 2003. Consequentialism, Stanford Encyclopedia of Philosophy. https://plato.stanford.edu/entries/consequentialism/.

Sinus Markt- und Sozialforschung GmbH. (Ed.). 2022. Infopaket „Nachhaltigkeit“

Sinus Markt- und Sozialforschung GmbH. (Ed.). 2024. Was sind Sinus-Milieus? https://www.sinus-institut.de/sinus-milieus.

Wewel, M. C. 2011. Statistik im Bachelor-Studium der BWL und VWL: Methoden, Anwendung, Interpretation; mit herausnehmbarer Formelsammlung. Pearson Education.

---

