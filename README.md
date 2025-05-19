# Water Quality Advisory Tool

<!--
![GitHub Logo](/CASExplorer.png) 
-->
![Alt Text](/AquaAnalyzer png.png)

##

## Overview

We built an AI-powered tool that helps users assess the safety of their drinking water based on pH values from Santa Clara Valley Water. By using OpenAI’s GPT-3.5, the tool instantly evaluates whether input values fall within safe EPA drinking water standards, and offers a concise, human-readable explanation.

## Water Quality Advisory Tool: What is it?

This tool is designed to simplify complex environmental data and make it understandable to the public. Users input a pH value, and the application uses generative AI to return a safety assessment along with a clear explanation tailored to everyday users. The tool was developed using Streamlit to provide an accessible web interface.

## Why the Water Quality Advisory Tool?

Water reports often include pH and mineral values that are unfamiliar or confusing to the average person. Even though the data is public, it’s not always actionable. Residents may drink or cook with tap water without knowing whether it's safe, especially in underserved areas or after heavy storms or maintenance activity.

- Existing public water data:

- Is published in scientific units not easily interpreted by the average resident  
- Requires cross-referencing with EPA safety guidelines  
- Offers no interactive or dynamic interpretation  

Our AI-powered tool introduces a more helpful approach by:

- Accepting user-submitted pH values from Santa Clara Valley Water reports  
- Automatically generating AI-based recommendations on water safety  
- Presenting results in clear, digestible language  
- Encouraging residents to stay informed and take proactive action if water conditions are unsafe  
- Bridging the gap between raw environmental data and meaningful health awareness  

Ultimately, this project aims to democratize water safety information and empower users with insights previously buried in static reports.

## Our Solution

We developed a prototype that analyzes pH data through OpenAI’s GPT-3.5 and delivers real-time water safety insights. The tool was built using Python and Streamlit to ensure a simple and interactive experience.

There are three key components of the system:

**pH Input Tool:**  
Users input a numeric pH value taken from Santa Clara Valley Water’s public reports. The tool then validates the range and feeds it to the AI for interpretation.

**AI Safety Assessment:**  
GPT-3.5 evaluates the provided pH level against EPA drinking water standards and responds with an assessment (safe, borderline, or unsafe) along with a brief explanation of potential effects.

**Accessible Interface:**  
Streamlit provides a responsive and user-friendly platform that allows anyone to access the tool via a browser without technical expertise.

The interface and logic are structured to prioritize clarity, ease of use, and reliability. In the future, we plan to extend this system with additional metrics (e.g., mineral levels), CSV uploads, and multi-lingual support.

## See Our Demo Video
[![Watch the video](demovid_icon.png)](https://www.youtube.com/watch?v=your_demo_link_here) 

<!--
[![IMAGE ALT TEXT HERE](/CASExplorer.png)](https://youtu.be/your_demo_link_here)
-->
