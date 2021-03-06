## 2.1 Defining a Common Language for Sampling

1.  A **census** is an attempt to collect data from every member of the population, while a **sample survey** is a collection of data from a subset of the population chosen by the researcher. A **sample survey** is a type of **observational study**.

2.  **Sampling Unit**

    The individual person, animal, or object that has the measurement (observation) taken on them / it.

3.  **Population**

    The entire group of individuals or objects that we wish to know something about. A numerical characteristic of the population is called a **parameter**.

4.  **Sampling Frame**

    The list of the sampling units from which those to be contacted for inclusion in the sample is obtained. The sampling frame lies between the population and intended sample. Ideally, the sampling frame should match the population, but rarely does because the population is not usually small enough to list all members of the population.

5.  **Intended Sample**

    Those individuals or objects who are contacted or selected from the sampling frame to have the measurement taken.

5.  **Sample**

    Those individuals or objects who provide the data to be collected. Numerical characteristics of the sample are called **statistics** and are typically used as estimates of population parameters.

6.  The process

    You want to know about a **POPULATION** but you only really have access to a **SAMPLING FRAME** that you can draw an **INTENDED SAMPLE** from, but in the end, you only get observations from the actual **SAMPLE**.

7.  **Selection Bias**

    The sampling frame should be as close to the entire population as possible. If this is not possible, the sampling frame should appropriately represent the desired population. **Undercoverage** is a type of selection bias in which sampling frame leaves out major portions of the population.

8.  **Nonresponse Bias**

    Nonresponse bias arises from low response rate, in which case the sample is much smaller than the intended sample. This problem can create bias if the people who respond have different views than those who do not.

## 2.2 The Beauty of Sampling

1.  If you follow the news, you might remember hearing that many of these polls are based on samples of size 1000 to 1500 people. So, why is a sample size of around 1000 people commonly used in surveying? The answer is based on understanding what is called the **margin of error**.

    For a sample size of ![equation](https://latex.codecogs.com/gif.latex?%5Cinline%20n%3D1000), the **margin of error** for a sample proportion is around ![equation](https://latex.codecogs.com/gif.latex?%5Cinline%20%5Cfrac%20%7B%201%20%7D%7B%20%5Csqrt%20%7B%20n%20%7D%20%7D%20%3D%5Cfrac%20%7B%201%20%7D%7B%20%5Csqrt%20%7B%201000%20%7D%20%7D%20%5Capprox%200.03) or about 3%. Since other problems inherent in surveys may often cause biases of a percent or two, pollsters often believe that it is not worth the expense to achieve the small improvement in the margin of error that might be gained by increasing the sample size further.

2.  **Margin of Error**

    - Measures the reliability of the percent or other estimate based on the survey data
    - Is smaller when the sample size (*n*) is larger
    - Does not provide information about bias or other errors in a survey

3.  Interpretation

    If one obtains many unbiased samples of the same size form a defined population, the difference between the sample percent and the true population percent will be within the margin of error, at least 95% of the time.

## 2.3 Relationship between Sample Size and Margin of Error

1.  The margin of error does not substantially decrease at sample sizes above 1500 (since it is already below 3%). After that point, it is probably better to spend additional resources on reducing sources of bias that might be on the same order as the margin of error. An obvious exception would be in a government survey, like the one used to estimate the unemployment rate, where even tenths of a percent matter.

## 2.4 Simple Random Sampling and Other Sampling Methods

1.  Sampling Methods

    - **Probability Sampling**

      Sample has a known probability of being selected

    - **Non-probability Sampling**

      Sample does not have known probability of being selected as an convenience or voluntary response surveys

### 2.4.1 Probability Sampling

1.  **Probability Sampling**

    - **Simple Random Sampling (SRS)**
    - **Stratified Sampling**
    - **Cluster Sampling**
    - **Systematic Sampling**
    - **Multistage Sampling (in which some of the methods above are combined in stages)**

2.  **Simple Random Sampling (SRS)**

    **Simple random sampling** is a type of probability sampling in which each member of the population has an equal probability of being chosen.

    A sampling bias can occur with a **simple random sampling** if the sample does not end up accurately reflecting the population it is supposed to represent. For example, it would be possible to draw 25 men even if the population consisted of 125 women and 125 men.

3.  **Stratified Sampling**

    **Stratified sampling** is possible when it makes sense to partition the population into groups based on a factor that may influence the variable that is being measured. These groups are then called strata. An individual group is called stratum. With **stratified sampling** one should:
    
    - partition the population into groups (strata)
    - obtain a simple random sample from each group (stratum)
    - collect data on each sampling unit that was randomly sampled from each group (stratum)

    **Stratified sampling** works best when a heterogeneous population is split into fairly homogeneous groups. Under these conditions, stratification generally produces more precise estimates of the population percents than estimates that would be found from a simple random sample.

4.  **Cluster Sampling**

    With **cluster sampling** one should
    
    - divide the population into groups (clusters).
    - obtain a simple random sample of so many clusters from all possible clusters.
    - obtain data on every sampling unit in each of the randomly selected clusters.

    It is important to note that, unlike with the strata in **stratified sampling**, the clusters should be microcosms, rather than subsections, of the population. Each cluster should be heterogeneous.

    Given equal sizes, **cluster sampling** usually provides less precision than either **simple random sampling** or **stratified sampling**. On the other hand, if travel costs between clusters are high, **cluster sampling** may be more cost-effective than other methods.

5.  **Systematic Sampling**

    **Systematic sampling** is a type of probability sampling method in which sampling units from an ordered sampling frame are selected according to a random starting point and a fixed, periodic interval. This interval, called the sampling interval *k*, is calculated by dividing the sampling frame size *N* by the intended sample size *n*.

    <p align="center"><img alt="equation" src="https://latex.codecogs.com/gif.latex?k%3D%5Cfrac%20%7B%20N%20%7D%7B%20n%20%7D"></p>

    **Simple random sampling** can be inefficient and time-consuming, statisticians turn to other methods, such as **systematic sampling**. Choosing a sample size through a **systematic sampling** approach can be done quickly. Once a fixed starting point has been identified, a constant interval is selected to facilitate sampling unit selection.

    **Systematic sampling** is to be applied only if the given population is logically homogeneous, because systematic sample units are uniformly distributed over the population. The researcher must ensure that the chosen sampling interval does not hide a pattern. Any pattern would threaten randomness.

### 2.4.2 Non-probability Sampling

1.  **Non-probability sampling** that should be avoided:

    - **Volunteer Samples**
    
      A voluntary sample is made up of people who self-select into the survey. Often, these folks have a strong interest in the main topic of the survey.
    
    - **Haphazard (Convenience) Samples**

      Members of the population are chosen based on their relative ease of access. To sample friends, co-workers, or shoppers at a single mall, are all examples of convenience sampling. Reseachers may unconciously approach some kinds of respondents and avoid others.

2.  Since such **non-probability sampling** methods are based on human choice rather than random selection, a statistical theory cannot explain how they might behave and potential sources of bias are rampant. The two types of non-probability samples listed above are called "sampling disasters".

## 2.5 Defining a Common Language for Comparative Studies

1.  **Experimental Unit**

    The **experimental unit** is the smallest basic object to which one can assign different conditions (treatments). In research studies, the **experimental unit** does not always have to be a person. In fact, the statistical terminology that is associated with research studies actually came from studies done in agriculture. Examples of an **experimental unit** include person, animal, plant, set of twins, married couple, plot of land, and building.

2.  **Explanatory Variable / Treatment** (in randomized experiment)

    The **explanatory variable** is the variable used to form or define the different samples. In randomized experiments, **explanatory variable** is the variable that is used to explain differences in the groups. In this instance, the **explanatory variable** can also be called a treatment when each experimental unit is randomly assigned a certain condition. Examples of **explanatory variables** include gender, type of plant, type of drug, type of medical procedure, and teaching method.
    
    You should note that gender and type of plant cannot be called treatments because one cannot randomly assign gender or type of plant.

3.  **Response (Outcome) Variable**

    The **response variable** is the outcome of the study that is either measured or counted. Examples of **response variables** include height, weight, temperature, classification of whether a person is a vegetarian, and classification of symptom severity for an illness.

4.  **Confounding Variable**

    A **confounding variable** is a variable that affects the response variable and is also related to the explanatory variable. The effect of a **confounding variable** on the response variable cannot be separated from the effect of the explanatory variable. Therefore, we cannot clearly determine that the explanatory variable is solely responsible for any effect on the response or outcome variable when a **confounding variable** is present. **Confounding variables** are problematic in observational studies.

## 2.6 Types of Research Studies

1.  With a **randomized experiment**, the researcher

    * Creates differences in the explanatory variable when randomly assigning treatments.
    * Allows for possible "**cause and effect**" conclusions if other precautions are taken.
    * Can minimize the effect of "**confounding**" variables.

2.  With an **observational study**, the researcher

    * Observes differences in the explanatory variable in natural settings / groupings (no variable is randomly assigned).
    * Strives for association conclusions since "cause and effect" conclusions are not possible.
    * Must accept that confounding variables are potential problems.

3.  **Independent Samples**

    The label of **independent samples** is used when the results for the one sample have no impact on the results found in the second sample. Each experimental unit provides a measurement for only one treatment. The results from experimental units in one group will not impact the results of experimental units in the other group, so the results form the two samples are **independent**.

4.  **Block Design** / **Randomized Block Design**

    With a **block design**, the researcher divides the experimental units into subgroups called **blocks**, such that the variability within blocks is less than the variability between blocks. In experiment study, experimental units within each block are randomly assigned to a treatment condition. Compared to independent samples, this design reduces variability within treatment conditions and potential confounding, producing a better estimate of treatment effects.

5.  **Matched Pairs Design** and **Dependent Samples**

    A **matched pairs design** is a special case of a block design. It can be used when the research study has only two explanatory values; and subjects can be grouped into pairs, based on some blocking variables. Specifically, each pair forms the experimental unit and provides two data observations that can be paired together. Consequently, we can say that we have two dependent samples as the values are more similar for each pair of measurements for each experimental unit than the values are between experimental units. But rather than comparing the two dependent samples, we are comparing the two data observations each experimental unit provides to each other which distinguishes matched pairs from independent samples.

6.  **Carryover Effect**

    Problems can exist with block designs, including matched pair designs, in experiment study, when what happens with the first measurement "carries over" to the second measurement. This **carryover effect** is a type of confounding that is found with block designs.

    For example, **carryover effect** could possibly occur if complicated equipment was used to measure force exerted by a hand. If everyone used their right hand first, they might not do so well with the right hand because of not understanding the equipment, but do much better with their left hand because they learned how the equipment worked. In statistics, this is called a **training effect**. The opposite, however, could also take place, when one became bored or fatigued resulting in **fatigue effect**.

7.  **Randomized Matched Pairs Design**

    The overall conclusion is that if you randomly assign the order of treatment, it should cancel out the possibility of a carryover effect. In statistics, we call this a **randomized matched pairs design**.

8.  The table below summarizes some combination of research studies:

    |Type of Samples              |Type of Study|Randomization Used          |Is Confounding Possible?                 |
    |-----------------------------|-------------|----------------------------|-----------------------------------------|
    |Two Independent              |Experiment   |Randomize type of treatment |No, randomization cancels out confounding|
    |Two Independent              |Observational|None                        |Yes                                      |
    |Matched Pairs (Two Dependent)|Experiment   |Randomize order of treatment|No, randomization cancels out confounding|
    |Matched Pairs (Two Dependent)|Observational|None                        |Yes                                      |

## 2.7 Designing a Better Observational Study

1.  The problem of confouding makes the interpretation of observational studies difficult. Thus, it is important to design observational studies in a way that minimizes confounding.

2.  **Retrospective Cohort Study**

    A **retrospective cohort study**, also called a **historic cohort study**, is a longitudinal cohort study used in medical and psychological research. A cohort of individuals that share a common exposure factor is compared with another group of equivalent individuals not exposed to that factor, to determine the factor's influence on the incidence of a condition such as disease or death. Confounding variables are potential problems in retrospective cohort study.

3.  **Case-Control Study**

    In a **case-control study** people with the response of interest form a group of "cases" and are compared to a group of "controls" who are in similar circumstances except for the fact that they have the response. Notice that case-control studies are done **retrospectively** - they compare patients who have the disease today with those who don't and ask them about past exposures or behaviors.

4.  **Prospective Cohort Study**

    A **prospective cohort study** is a longitudinal cohort study that follows over time a group of similar individuals (cohorts) who differ with respect to certain exposures or behaviors (the explanatory variables) under the study, to determine how these factors affect rates of certain outcome (the response variable).
