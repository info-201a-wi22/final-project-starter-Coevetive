<!--
CHECKLIST:
--- Project Set Up
[*] 1pt - Successfully creates repository and adds all group members to the repo
[*] 1pt - Uses well formatted markdown throughout this document (headers for each section, lists where appropriate, hyperlinked words, etc.)
--- Domain of Interest
[*] 1pt - Describes in at least 2 - 3 sentences why the group is interested in this area
[*] 2pts each - Relevant data driven projects
[*] 1pt each - Question is related to the field
[*] 1pt each - Describes how the question can be answered using data (e.g., a specific comparison within or analysis of the data that answers the question)
--- Finding Data
[] 1pt each - Link to URL where data is from, and download the data into the project repo in a data/ folder
[] 1pt each - Description of how was the data collected or generated
[] 1pt each - How many observations (rows) and features (columns) are in your data
[] 2pts each - What questions (from above) can be answered using the data in this dataset
-->

# COVID-19 and GHG Emissions, What Can We Learn? - Code Name: Greenfoot
* **Authors:** Justin Rhinehart @ jjrhine@uw.edu, Ryan Friesz @ ref7@uw.edu, Tom Jubin @ tomjubin@uw.edu, Liam Dale @ liamdale@uw.edu
* **Affiliation:** INFO-201: Technical Foundations of Informatics - The Information School - University of Washington
* **Date:** Winter 2022

### Abstract:

We are concerned with GHG emissions and the drastic effects it will have on our climate. This matters to us as within our lifetime we will be facing the damaging effects the climate crisis. To address our concern, we plan to use COVID-19 pandemic and the short drop in GHG emissions which followed as an example to how we can reduce our carbon footprint in the future.

**Keywords:** greenhouse gases, COVID-19, pandemic, climate change, lockdown

### Introduction:

The COVID-19 pandemic has brought massive change to the modern world. Lockdown restrictions intended to stem the spread of this disease saw fewer people driving, traveling and consuming, and more people isolating at home, rarely leaving. During the early waves of the pandemic we also saw temporary closures of large industrial centers, and a massive migration to remote, or online, work. Through our research, we plan to determine what effect, if any, these changes to modern life have had on both global and national greenhouse gas emissions. This collected data, once analyzed, has the capacity to show us what potential steps can be taken to curb future greenhouse gas emissions, and serve as a real-world display of what both minute and drastic changes in normal life can do to the environment.

### Design Situation:

Our primary topic of concern is greenhouse gas emissions. This matters to us as we will experience the drastic effects on our climate in our lifetime and will want the tools to combat it. In this report, we plan to look at how GHG emissions decreased temporarily because of restrictions relating to Covid-19 and gather what we can learn from the decrease in emissions. Our issue falls within the problem domain, as it is an issue that has multiple answers and can not be solved with a single ‘design’. Some key questions to consider are those pertaining to the lockdowns and how they lowered greenhouse gas emissions from “transport, industries, and fossil fuel burning”, along with agricultural industries which also saw a drop in ammonia emissions. (Mohsin et al., 2021)

As a single-planet species with significant control over our biosphere, it is our responsibility to maintain the only environment we have to support future generations and the propagation of our species. The simple wellbeing of the entire species is incredibly valuable, and the consequences of inaction on climate change and greenhouse gas emissions are drastic and terrible (Thompson and Bendik-Keymer, 2012). The interest of businesses in the realm of fossil fuels and manufacturing aligns directly against the further success of the human race, pushing for further pollution and emissions, with little regard for much beyond YOY profits.

The unfortunate reality of rising greenhouse gas emissions and global warming is that everyone has a stake in the hardship and disasters that they invite. Two main trains of thought tend to accompany this topic, those of apathy and denial, and those of hopeful progress and change. Those in the denial camp include oil, gas, and coal giants like BP, who have a long history of suppressing and outright lying about the negative effects of greenhouse gas emissions. Their bottom line is harmed by the steps that need to be taken to fix the planet, and tend to stand strongly against progress. Those who hold hope for the future, and work to undo, or at least halt, the damage being caused are motivated by the possibility that there is no future, unless changes are made. There are no indirect stakeholders here. Everyone is in the same boat, as we only have one planet that we have to share. (Major Groups & Stakeholders, 2022)

Interventions with data and technology have already happened with greenhouse gas emissions, the benefits have been immense in allowing us to prove and show the harm we are causing to our planet, the harms, however, have been immense as well, with many companies attempting to shift blame away from their actions either through funding studies which undermine the actual effects of GHGs or by pointing fingers at individual citizens or developing countries. It would be fair to argue that all of our direct stakeholders would benefit from a healthy climate in the long-run but short-term stakeholders such as businesses and governments will be greatly harmed by practices that attempt to reverse the effects of climate change.

### Research Questions:

United States lockdown policy varied greatly during the pandemic and we plan to explore if different policies across different states had a significant effect on GHG emissions. We will compare data before and after COVID was prevalent to see how the data reflected across different states over the years. We also plan to examine worldwide COVID restrictions, and the effect that those had on global emissions numbers. We plan to collect and analyze data from several different nations of varying geography and financial status - to ensure we take note of important factors like culture. Continuing on the global scale, we plan to look at specific sources of pollutants, chiefly manufacturing. From the data and analysis we have gathered here, we plan to examine if the COVID-19 pandemic made any significant change in the amount of pollution, and how these changes can be applied to both model and plan for a greener future.

### The Dataset:

EPA Air Emissions Dataset
* This dataset contains approx. 8 million entries of specific greenhouse gas types, emissions levels and locations across the united states from 2011 to 2020. The dataset was gathered from EPA monitoring systems and devices on the continental United states, for the purpose of tracking ghg emissions in the United States. This data is held directly by, and obtainable from, the EPA, and as such is secure and trustworthy.

European Environment Agency Industrial Reporting database
* Dataset contains data pertaining to greenhouse gas emissions in participating European countries from 2010-2021, on a national, sector, and facility level. The data was gathered from EEA monitoring systems and devices in participating European countries for the purpose of monitoring and reducing GHG emissions from the European Continent. This data was stored with the EEA, and obtained from the same group, and as such is both secure and trustworthy

Global Carbon Budget 2021
* The dataset contains fossil fuel emissions (CO2 mainly) dating from 1959 to 2021. Rows from the dataset are in MtC/yr (million tonne of carbon per year), with recorded features being types different ways of emission (Oil, Gas, etc.) and the country of origin. The data was collected from NOAA and a U.S. DOE organization, this data was funded by government programs and as such isn't profit focused. I believe this dataset was created primarily for climate researchers. The data is credible as it comes directly from a scientific journal (Earth System Science Data) and the Global Carbon Project which authored the report which collected and cleaned this data is a partner of United Nation's World Climate Research Programme.

IPCC AR5 WGIII Database
* This dataset contains models from Intergovernmental Panel on Climate Change (IPCC) dating from 2015. The models used mostly date from 2005-2100 and contain measurements in Mt CO2/yr, Mt CH4/yr, etc. as well as population and GDP estimates, in addition the data is sorted by region ASIA, NA, SA, etc. These models were created from the United Nation's IPCC and as such guarantees that the dataset with created with a non-profit focus, with the purpose of being used in IPCC's annual climate report. This data is credible as it originates from the United Nations.

EPA GHGP Data by Year
* This dataset contains *reported* total greenhouse gas emissions on a yearly basis for locations all across the United States from 2011-2020. The total emissions by year are broken down by different sectors across several sheets (i.e. direct emitters, onshore oil & gas, transmission pipelines, etc.) This dataset was created with the purpose of tracking all reported GHG emissions across the country for the public to view or for anyone who would like to pursue further research with. The data is credible as it was collected by the greenhouse gas reporting program of the environmental protection agency of the United States.      

Our World in Data CO2 and GHG Emissions Dataset
* This dataset contains data from the Global Carbon Project, Climate Watch Portal and the BP Statistical Review of World Energy to track GHG Emissions on an annual, per capita, cumulative and consumption basis. While most of this data comes from reputable sources, BP is not known to be trustworthy when the topic of climate comes up, and their portion of this data could be misleading or skewed. This particular collection of data is a github repository, and as such is securely held, to an extent, but not necessarily secure in its consistency or factuality.

### Expected Implications:

* With the Covid-19 pandemic, there was a decrease/downtrend in total greenhouse gas emissions outputted. The expected implications of this are that policymakers will be able to see that with dramatic global shutdown, minimizing the direct emissions into our atmosphere is very possible on a large scale. The obvious problem however is that life will not be in lockdown forever, but this temporary period may give some insight for a further permanent solution in decreasing emissions. By taking a deeper look into which and where certain emissions experienced drastic change, it may be possible to pinpoint or target a specific area/region to prioritize first for maximum efficiency when trying to tackle the issues.

### Limitations:

* The limitations to this study would be that we can only work with the provided data on record. Also, this data for reported GHG emissions is exactly that: reported. Therefore, although the data is as accurate as we have possible, it is most likely not exactly reflective of the true GHG emissions experienced.

### **References:**

Environmental Protection Agency. (2020). Air Emissions Dataset (Version number) [CSV]. Retrieved from https://echo.epa.gov/tools/data-downloads

European Environment Agency. (2021). Industrial Reporting database (v5) [CSV]. Retrieved from https://www.eea.europa.eu/data-and-maps/data/industrial-reporting-under-the-industrial-4

Friedlingstein, P., Jones, M. W., O'Sullivan, M., Andrew, R. M., Bakker, D. C. E., Hauck, J., Le Quéré, C., Peters, G. P., Peters, W., Pongratz, J., Sitch, S., Canadell, J. G., Ciais, P., Jackson, R. B., Alin, S. R., Anthoni, P., Bates, N. R., Becker, M., Bellouin, N., Bopp, L., Chau, T. T. T., Chevallier, F., Chini, L. P., Cronin, M., Currie, K. I., Decharme, B., Djeutchouang, L., Dou, X., Evans, W., Feely, R. A., Feng, L., Gasser, T., Gilfillan, D., Gkritzalis, T., Grassi, G., Gregor, L., Gruber, N., Gürses, Ö., Harris, I., Houghton, R. A., Hurtt, G. C., Iida, Y., Ilyina, T., Luijkx, I. T., Jain, A. K., Jones, S. D., Kato, E., Kennedy, D., Klein Goldewijk, K., Knauer, J., Korsbakken, J. I., Körtzinger, A., Landschützer, P., Lauvset, S. K., Lefèvre, N., Lienert, S., Liu, J., Marland, G., McGuire, P. C., Melton, J. R., Munro, D. R., Nabel, J. E. M. S., Nakaoka, S.-I., Niwa, Y., Ono, T., Pierrot, D., Poulter, B., Rehder, G., Resplandy, L., Robertson, E., Rödenbeck, C., Rosan, T. M., Schwinger, J., Schwingshackl, C., Séférian, R., Sutton, A. J., Sweeney, C., Tanhua, T., Tans, P. P., Tian, H., Tilbrook, B., Tubiello, F., van der Werf, G., Vuichard, N., Wada, C., Wanninkhof, R., Watson, A., Willis, D., Wiltshire, A. J., Yuan, W., Yue, C., Yue, X., Zaehle, S., and Zeng, J.: Global Carbon Budget 2021, Earth Syst. Sci. Data Discuss. [preprint], https://doi.org/10.5194/essd-2021-386, in review, (2021). [XLSX] Retrieved from https://www.icos-cp.eu/science-and-impact/global-carbon-budget/2021. [CSV] Retrieved from https://zenodo.org/record/5569235#.YYxC8tZBxjw.

IPCC. (2015). AR5 Scenario Database (v1.0.2) [CSV]. Retrieved from https://tntcat.iiasa.ac.at/AR5DB/dsd?Action=htmlpage&page=about

Ritchie, H., Roser, M., Mathieu, E. and Macdonald, B., 2022. GitHub - owid/co2-data: Data on CO2 and greenhouse gas emissions by Our World in Data. [online] GitHub. [CSV] Retrieved from https://github.com/owid/co2-data

Mohsin M, Naseem S, Sarfraz M, Ivascu L and Albasher G (2021) COVID-19 and Greenhouse Gas Emission Mitigation: Modeling the Impact on Environmental Sustainability and Policies. Front. Environ. Sci. 9:764294. doi: 10.3389/fenvs.2021.764294

Thompson, A. and Bendik-Keymer, J., 2012. Human Values and Institutional Responses to Climate Change. Ethical Adaptation to Climate Change, pp.281-297.

UNEP - UN Environment Programme. 2022. Major Groups & Stakeholders. [online] Available at: <https://www.unep.org/civil-society-engagement/why-civil-society-matters/major-groups-stakeholders> [Accessed 5 February 2022].

<!--
## Developer Notes

* **Where is the project brief?**  [`../instructions/project-design-brief.pdf`](../instructions/project-design-brief.pdf).
* **Making Progress**: We understand this work might be difficult. Also, we understand that your project ideas might not be completely worked out. So, we ask that you do the best you can. You will receive specific guidance from your TA and constructive feedback. We are confident that you will succeed!
* **What should be included in the proposal?** Every proposal will be different. It depends on your particular project.  That said, in the table below you will find the expected report elements.  It is important that you engage with and respond to the the Design Brief.
* **How should the proposal be formatted?** You should format your proposal using Markdown in this file. You should aim for a professional presentation - clear, concise, interesting, and free of spelling and grammatical errors.
* **What headings should we use?** As needed, the suggested headings below can be revised and new headings and sub-headings can be added. Please use headings, bullet lists, tables, figures, and other markdown code effectively - seek a professional presentation.
* **Finishing up.** When you are finished writing and formatting your proposal, save these developer notes(they might useful in the future). Then, delete them.
* **Questions?** If you have questions, please ask your TA or post on Teams.

|Element | Brief Description|
|---------------| --------------
|Code name | Give your project a _code name_, a short, evocative name for efficiently referring to your project. Your code name does not change! Examples: _Jazz-4_, _Rocking Fish_, etc. |
|Project title| Give your project a concise, interesting title that summarizes the entirety of your project. (Your title can change on subsequent deliverables.) |
|Authors | Names of your team members and contact information (email addresses). |
|Affiliation |  INFO-201: Technical Foundations of Informatics - The Information School - University of Washington |
|Date | Winter 2022|
|Abstract | No more than three sentences that summarize your project. Focus on the very most important aspects. For example: **(1)** "Our main question is .... This question is important because .... To address the question, we will ...." **(2)** "We are concerned with ..., becuase .... To address this concern, we plan to ...." **(3)** "Consider that ....  This is important because .... Accordingly, we plan to ...."   |
|Keywords | 3-5 keywords that summarize your project.  (e.g., "Keywords: human physiology; bicycle exercise; elderly; power and heart rate times-series data") |
|1.0 Introduction | Briefly introduce your project. (about 150 words) |
|2.0 Design Situation | Use short sub-sections to describe your topic and the setting (that is, the sociotechnical situation), including project framing, human values, direct and indirect stakeholders, possible harms and benefits. See the Design Brief, section B.3. **Note**: You *must* include three citations to related work (URLs to similar work, high quality articles from the popular press, reseach papers, etc. ). You may find it helpful to include a figure.  (about 400 words) |
|3.0 Research questions | 3-5 research questions. What motivates the questions? Why are they important? See the Deign Brief, section B.4. (about 150 words) |
|4.0 The Dataset | See Design Brief, setions B.5 (_Size and complexity_) and B.6 (_Data provenance_). Use short sub-sections for describing the size and complexity of the dataset and for describing the origins fo the data. (about 400 words) |
|5.0 Expected Implications | Assuming you answer your research questions, briefly describe the expected or possible implications for technologists, designers, and policymakers. (about 150 words) |
|6.0 Limitations | What limitations might you need to address? Briefly discuss. (about 150 words) |
|Acknowledgements | Is there anyone you would like to thank? A librarian who helped you with your research? A Teaching Assistant? A friend who helped you find your data? Say thank you in this section.|
|References | Include citations to your three references. See 2.0 Introduction. If you like, you can cite more than three references.  Please use a standard citation style of your choice.  See [Citing Sources](https://guides.lib.uw.edu/research/citations) at the UW Library. |
|Appendix A: Questions| Do you have questions for your TA or instructor?  Include them here.|

-->
