---
title:  Madison Wisconsin Meeting Review
layout: page
---

# Workshop Summary

Seventeen participants were a part of the Madison, WI meeting. This meeting included 5 early-career researchers.  Participants met during the 17th and 18th of May at the Memorial Union and focused on the elements necessary to construct a the cyberinfrastructure necessary to facilitate the connection of data resources through reusable workflow elements drawn from publications, code repositories, and other resources.

Well-constructed cyberinfrastructure requires input from potential data users, data managers and system architects. The *Data Linking Workshop* facilitated discussion across these three groups of individuals, identifying the strengths of each individual's perspective, providing a safe space to discuss, question, and challenge one another's perspectives, while coming together to accomplish the goal of providing support to geoscientists to help retain cultural knowledge within the geosciences and to reduce "time to science" for end users. and domain experts within the geosciences who are actively engaged in designing and carrying out interdisciplinary research projects.

## Connecting Resources

One objective of the meeting was to identify ways of capturing and discovering reusable workflow elements that could be used to connect data from multiple resources.  This might include connecting climate data with modern proxy data to build transfer functions for paleoclimatic reconstruction, or connecting [online topographic maps]() with [estimates of land values]() and [real time hydrographic data]() to assess flood risk or the potential for property damage under severe weather conditions.

These units of work may require complex transformations, specialized software (documented perhaps using [Ontosoft](http://ontosoft.org)) or may be only one or two lines of code.  In any of these cases, making units of work discoverable (through the generation of annotations that link the resources) can provide a significant boost to data use, reuse and data integration across the paleogeosciences since work flows become directly connected to unique identifiers associated with any of: data repositories ([re3data DOIs](http://re3data.org)), individuals (ORCiD), publications (DOIs) or datasets (datacite).

<img src="images/throughput_resourcedescr.svg">

## Frameworks for Connections

The way in which connections will be made and supported must be reflected in the data structure of the application. Workshop attendees examined a number of options for populating the annotation service and discussed sources for an [initial set of linking workflows](http://throughput-ec.github.com/throughputdb/populate) that would provide the basis for a proof-of-concept application.  Based on informal groupings that reflected individuals' experience, we examined representations of cross-resource workflows by searching through the GitHub code base (Figure 1, superscript 1), by searching for papers that indicate the use of multiple data resources (Figure 1, superscript 2), or by examining target data resources themselves to understand how an individual might seek to link the resources (Figure 1, superscript 3) for the purposes of developing new applications.

<img src="../../../images/throughput_resourcedescr.svg" width="400px"><br>
<strong>Figure 1.</strong> <em>A schematic representing a potential cross-resource workflow supported through public development on GitHub.  See paragraph above for description.</em>

## Frameworks for Interaction

Participants discussed how users might interact with the platform, how data could be visualized within the platform, and how this user interaction and data visualization would best represent the data model and intent of the platform.  One key point was that presentations must reflect the multiple intents of users.  A user who seeks to annotate a data object would be most likely to target specific resources, papers, or data elements, for example, beginning by finding a single dataset (e.g., [Neotoma dataset 123](http://data.neotomadb.org/datasets/123)) and then annotating the record.  A user interested in finding reusable workflow elements connecting resources might be interested in thematic searches, where visualizations would represent a landscape of resources.  Finally, a user searching across annotations may be interested in data types, ORCIDs, DOIs, publications.

## Workshop Successes

The workshop facilitated new connections between individuals working across various data repositories such as Neotoma, and the Alaska Volcano Observatory.  It also connected data users and managers from the PAGES 2k working group and FlyOver Country, and cyberinfrastructure developers associated with resource management, representing EarthChem, and other working groups.  These new connections were supported through informal interactions among members during meals and coffee breaks, but also through activities designed to provide one another with a sense of individual's interestes and expertise.

The workshop provided an opportunity to develop use cases beyond the initial PI group, by bringing in external partners.  These use cases were recorded and are available as a [Google spreadsheet]().

In addition to detailing specific workflows we also engaged potential end-users and experts in UI development to consider how a user may engage directly with such a platform.  This resulted in the development of several potential facets for front-end development, providing greater structure to the eventual development of a fully realized platform.

## Workshop Considerations

Icebreaker ideas.  Let people self identify and sort into groups.

Set clear expectations, possibly after the ice breaker.  Empower people but set boundaries, Clarify objectives for participants (what should they expect to gain?), vs objectives for the meeting (what do we hope to produce?).

Adding assessment checks to the workshop.  How can we set up checks in the process of the workshop.  (How does a pre-assessment set up the discussion first?  Using a post assessment to capture knowledge gained)

Use peer-to-peer teaching to discuss, "What are the challenges your community faces in joining datasets?"
