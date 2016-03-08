# Key References #

[Delphor Website](http://www.delphor.net/) 

[Delphor Wiki](https://github.com/delphornet/Cortextual/wiki) 

[Main Project README, including licensing and resources](https://github.com/delphornet/Cortextual/blob/master/README.md)

# Delphor/Viz Project Managers #

Currently led by Rob Weiss (@3XPlo1t2) and John Eberhardt (@JohnSEberhardt3).

# Delphor/Viz Project Roadmap #

The roadmap for this project is [here.](https://github.com/delphornet/Cortextual/wiki/Project-Roadmap#delphorviz-repo-and-project-roadmap)

# Features, Functional Requirements, and Components in this Repo #

+	Feature DV1: A visual language construct that allows for the application of different visualization models to Delphor/Enrich streams
	+	Functional Requirement DV1A: Assign encoded visual symbols to specific enriched attributes 
		+ Component DV1Ai: Framework for deconstructing streams into component parts for emission into the visualization
			+ **Status: complete**
+	Feature DV2: A simple visualization interface that encodes the Delphor/Enrich streams into a simple color plot: “Close Encounters of the Data Kind”
	+ Functional Requirement DV2A: Convert enriched streams into a streaming color plot for sparse pattern recognition
		+	Component DV2Ai: A Hilbert Space Filling curve plot to support plotting data feeds onto a map
			+	**Status: complete**
		+	Component DV2Aii: Normalize enrichment values to RGBA color scheme
			+	**Status: complete**
		+ Component DV2Aiii: Image generation based on the first two components
			+ **Status: complete**

If you want to add to the roadmap, learn more [here.](https://github.com/delphornet/Cortextual/wiki/Feature-and-Release-Management)

# What's Here #

|**Package** | **What it Does** | **References** |
|-------------|----------|------------|
|framework for hilbert plotting| prepares data for a hilbert space|xxx|
|Hilbert space filling curve|plots normalized enriched values on a Hilbert curve|www|
|file generator|generates video file of Hilbert plotted enriched stream|www|
|-------|---------------|----------------|

# Contributors #

Rob Weiss (@3XPlo1t2)
