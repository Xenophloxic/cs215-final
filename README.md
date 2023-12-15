# Data Manifesto

## Context is Key
Take a look at this graph. Can you guess what data it's visualizing without any other information?

![Screenshot 2023-12-14 010833](https://github.com/Xenophloxic/cs215-final/assets/64376702/033d7c99-095e-4766-a368-13ca33e3dffa)

Maybe you guessed this was a map of the number of languages spoken (in areas with data) or annual casualties resulting from obesity. 

This actually displays the absolute number of McDonald's each country has, with the U.S. having the most. Here's the same map with the legend:

![Screenshot 2023-12-14 010833](https://i.redd.it/7j9ye12uzrg71.png)

However, it's important to include context: McDonald's was founded in the U.S. and is currently headquartered there. Also, the introduction of McDonald's led to fast food chains becoming an important part of American culture, which isn't seen in other countries.

As you can see, data is only valuable **in context** of its social, cultural, and historical significance. Without knowing what the map was plotting or how other factors could have impacted our data, we only get half the picture.

This visualization had a relatively simple data collection process, but that becomes increasingly important to consider as context as well, and this principle is covered in the next part.

In Project 8, while analyzing my partner's data, I noticed that my partner's usage spiked at night. Without context of where this data came from or why the usage spiked this way, I had to assume and make conclusions without strong evidence. Later, I found that the data was from TikTok, and my partner liked watching some before bed. This assignment, especially with the mystery-solving feel, really showed how it's easy to wrongfully analyze data without context.

In our reading of Bergstrom & West's "Selection Bias" from Calling Bullshit, we were introduced to the Portugal Children's dilema:

> In Portugal, about 60 percent of families with children have only one  child, but about 60 percent of children have siblings. This sounds impossible, but it's not. The picture below illustrates how this works. Out of twenty Portuguese families, we would expect to see about twelve with a single child, seven with two children, and one with three children. Thus most families are single-child, but because multi-child families each have multiple children, most children live  
in multi-child families.

As shown here, incomplete context and information can lead to bias for data scientists and viewers.

Bias is dangerous. In our reading of *Human-Centered Data Science,* we read about a bias in Google searches:

> This is how we get Google Images returning pictures of white men when a person types in "doctor" or highly sexualized results for the phrase "Black girls"

Bias is something every data scientist should strive to address, and a strong method is to add more context.

**Contextualization is important to understanding data completely. Always look at data through its context, being aware of its intended use and addressing potential biases.**

## Trust, but Verify

Invalid and incomplete data is as good as no data. 

In Project 4, we learned about the [Data Nutrition Project](https://datanutrition.org/) and the importance of examining datasets.

This is the nutrition label sheet that I created with my partner:

![image](https://github.com/Xenophloxic/cs215-final/assets/64376702/47f6a3aa-0dc0-45ba-bf11-633a910c2dea)

A few things are particularly important:
- The reliability of the source
- The completeness and validity of the data
- Potential weaknesses and how they were addressed
- Individuals involved, how their privacy was protected, and how different populations were represented.

Only a combination of these metrics can determine how reliable a dataset is. Without a reliable dataset, a true analysis can't be done.

In "Raw Data" Is an Oxymoron, we're introduced to the idea that no data is truly raw.

> Bowker suggests, that data are always already "cooked" and never entirely "raw."

Since no data is really raw, it's even more important to check the reliability of datasets and ensure that your dataset is strong enough to analyze.

Going back to principle one, verifying a dataset necessitates the need to learn about the context: how the data was collected, how biases were addressed, the background of the data, and more.

**Trust that data is curated well but guarantees its validity, reliability, accuracy, and privacy. Acknowledge potential weaknesses and attempt to address them.**

## Communicate

Take a look at these documents:

[https://docs.oasis-open.org/dita/v1.2/os/spec/archSpec/conref.html](url)

[https://www.nodegit.org/api/](url)

What do you notice about them?

Now take a look at this one:

[https://cloud.google.com/anthos/run/docs/configuring/using-configmaps](url)

Much better, right? The first two documentations were confusing and lacked detail, while the last one was clear, detailed, and even interactive.

Data science is very human-centered (principal 4), and communication, through documentation and narrative, is key to collaboration and analysis.

In each of our projects, we documented our steps, logic, and created a narrative in our analysis. Moving forward, it's important to continue this practice. Data science can be a storytelling tool, and communicating data insights through a narrative that resonates with people is important.

Relating back to principle two, it is also important to preserve   data for future analysis and be transparent in processes while maintaining privacy.

**Communication is key to success. Ensure documentation, transparency, and preservation of data, but maintain privacy. Create a narrative with data.**

## Data is Human

Data is human-centered; use it to do human-centered things.

Going back to Giorgia Lupi's data manifesto:

> Big Data doesn't belong to a distant dystopian future; it's a commodity and an intrinsic and iconic feature of our present 

As data scientists, we have the responsibility to use data to help us, humans, and our society.

Data collected by humans relates to us in every way. Exploring Earth's past carbon levels may seem unrelated to humans, especially ones from before we existed, but it can show our interactions and predict future situations that can very well be related to us.

Even in our first project, using First-year student data, we saw how this data, collected over twenty years, could help humans decide what classes to take what minors to consider.

It's also important to support human rights and values with our data.

*Data Feminism* brings this to light very well:

> In Data Feminism, we bring these two aspects of feminism together, demonstrating a way of thinking about data, their analysis, and their display that is informed by this tradition of feminist activism as well as the legacy of feminist critical thought.

**Data is human-driven. Create and analyze data to meet human needs and uphold human rights and values in projects.**

## Sources
[https://www.reddit.com/r/MapPorn/comments/p2jkfx/countries_by_mcdonalds_locations_around_the_world/](url)

Various Projects and Annotations from this semester
