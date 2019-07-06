# Technology Radar Data

[ThoughtWorks](https://www.thoughtworks.com/) has been publishing a
[Technology Radar](https://www.thoughtworks.com/radar) since 2010.
It classifies technology trends in techniques, platforms, tools and
languages/frameworks into 4 categories:

1. **Adopt**. Use whenever appropriate
2. **Trial**. Try on projects that can handle risk
3. **Assess**. Explore to understand
4. **Hold**. Proceed with caution

This repository "scrapes" the data into 2 CSV files:

- [technologies.csv](technologies.csv) has each technology listed over
  time, with these columns
    - Volume: Technology radar publication number (1, 2, 3, ...)
    - Category: Techniques, Tools, Platform or Languages
    - Index: Technology number (1, 2, 3, ...) within the volume
    - Technology: Name of the technology evaluated
    - Stage: Category (Adopt, Trial, Assess, or Hold)
- [reference.csv](reference.csv) has information about each volume
    - Volume: Technology radar publication number (1, 2, 3, ...)
    - Month: Month of publication
    - Link: Link to the publication
