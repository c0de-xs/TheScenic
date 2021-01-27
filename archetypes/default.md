---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true # Set to false to publish
 
description: "Put your description here" 
summary: "Put your summary here" 
tags: [] # Add tags inside the brackets ex. ["Tag1", "Tag2"] 
categories: [] # You can add your own, after you add them in the config.toml. 
# Using the PLURAL = ["SINGLE1", "SINGLE2"] format
## HERO IMAGE ##
# You have to fill the heroImageUrl and the heroImageDescription.
heroImage: "true" # Change to false if you want to disable hero images
heroImageUrl: "HERO IMAGE URL"
heroImageDescription: "HERO IMAGE DESCRIPTION"

---
