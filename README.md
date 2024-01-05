# FinOps Custom Lens:

## General:
Use this JSON file to launch a custom lens in your AWS account's Well-Architected Review module. The service is free and should generate a report containing the recommendations based on your answers. This is an extensive questionaire designed to think about you FinOps/CFM posture and practices and identify how to go forward. The results can be used to structure a roadmap, prioritize actions, ... I used 4 Pillars to structure the review to have some form of grouping for the different things I thought were important. This is also how AWS structured the ingestion of the JSON lenses, so I had little choice. By no means do I want to create yet another framework to implement, FinOps is not about frameworks. 

Where possible, I included links to documentations for the action items and tips and tricks, but feel free to fork this repository and build on it. I wrote it because I didn't think there really was a quality assessment out there to get an idea of how one was doign in terms of FinOps on AWS. Most of the consultancy assessments or even the assessment of the Foundation are vague, high level and check more how you implement a set of principles than how you are actually solving your problem.

## The Structure:
There are four pillars (or groups of questions) that you go through in the assessment:
- Ownership & Awareness (how do you technically create mapping, structure and awareness surrounding your AWS costs)
- Cost Optimization (how do you optimize your costs)
- Cloud Spend Planning (how do you look ahead and work with finance)
- Operational Management (How do you organize your finops efforts, how much is it a part of your organization)

## Note:
I created this a while back, so I am sure it can be improved upon. I was limited by the structure of how AWS ingests the JSON. For example, the logic generating High, medium or No risk is very simplistic (though not necessarily wrong). The more things you check off your list as things that you already have covered for a question or topic, the less risk is assigned to that topic. 

Hope this little project helps people, feel free to fork and add your own tweaks!