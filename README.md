# The Modern Data Culture

I've started thinking about creating data culture within a company and how hard it is to span the length of data entry to BI and back. Most people don't think of themselves as "data" people, but they do some sort of data entry, processing, or decision-making based on data every day. The people closest to the data, whether it be data entry or decision making, have an innate feeling for the data. dbt and @Chris Jenkins tāngata(great Coalesce talk btw!) gave me a lot of inspiration about how to integrate documentation with tests, and making it accessible to everyone. Data exploration tools gave me the inspiration of tying visibility of data to better understanding. The combination of both concepts could really help define a data culture, where data entry users can see and explore the data they are entering at the source, how it is defined and tested, what is being done to it across the data pipeline, how it is being used to make decisions, and to be able to suggest changes right in that workflow.

Promoting modern data culture is all about visibility. 
It's hard to care about individual data entries.
Everyone has an innate feeling for what data is "right" vs "wrong".
All you need to do is show people the data.

Data entry is closest to the data source and should be able to define and see the data they enter.
Data Catalog - Source
- Closest to what they know
- See ranges or aggregates of what is entered as a whole
- Examples, not everything, for data security
- See definitions alongside actual data
- Be able to suggest changes to definitions right there.
- Visibility into tests? Multiple layers, the data application layer vs pipeline tests

Data entry should also know how their data is being used downstream.
Data Catalog - BI
- Can see how their data entry is defined downstream
- Can see how their data entry affects metrics, what is counted what is not counted?
- Can suggest changes to definitions based on perception vs reality of data entered.

Power data entry users can gradually gain access to more of the data pipeline (staging, warehouse, BI)
- Don't want to overwhelm up front
- More questions and suggestions should unlock deeper understanding

Business users should know how data is being entered and how it becomes available to them for decisions.
