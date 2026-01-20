

Objective: Extract structured data from unstructured input.

Choose an unstructured text (e.g., "John Doe, age 29, lives in Paris and works as a software engineer.").

Create a template prompt:

    "Extract the following fields from the text: Name, Age, Location, Occupation. Return the output in JSON format."

Validate the output and ensure consistency across multiple inputs.

John Doe, age 29, lives in Paris and works as a software engineer. { "Name": "John Doe", "Age": 29, "Location": "Paris", "Occupation": "Software Engineer" }

Sarah Smith, a 34-year-old resident of New York City, has been working as a creative graphic designer for the past 10 years at a boutique advertising firm. { "Name": "Sarah Smith", "Age": 34, "Location": "New York City", "Occupation": "Graphic Designer" }

Michael Johnson, aged 42, currently lives in London with his family and is employed as a senior financial analyst at a multinational investment company. { "Name": "Michael Johnson", "Age": 42, "Location": "London", "Occupation": "Financial Analyst" }

Emily Davis, 27, who recently moved to Toronto, works full-time as a marketing coordinator for a fast-growing tech startup while also pursuing a part-time MBA. { "Name": "Emily Davis", "Age": 27, "Location": "Toronto", "Occupation": "Marketing Coordinator" }

The output is correct and the consistency was almost correct thought the chat opened a new category at some point wich was additional info that needed to be exempt.
