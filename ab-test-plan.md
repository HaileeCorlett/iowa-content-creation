
# A/B Test Plan: Heartland Behind The Lens

## 1. Page and Element Being Tested

The page being tested is the homepage of Heartland Behind The Lens, an Iowa wedding content creation website. The single element being changed is the main homepage headline.

- **Version A (Original):** "Iowa wedding content creator"
- **Version B (Variant):** "Iowa Wedding Content Creator: Relive Your Day, Instantly"

All other homepage elements, including the subheading, buttons, layout, and content, will remain the same. This will allow me to isolate the effect of the headline wording.

## 2. Hypothesis and Reasoning

I predict that Version B will produce a higher inquiry rate than Version A because it communicates both the service being offered and the emotional benefit of being able to relive wedding-day moments immediately. Couples may find this benefit-focused headline more compelling than a headline that only identifies the service. However, Version B may perform the same as or worse than Version A.

## 3. Model, Persona, Prompt, and Assignment

**AI Model:** OpenAI ChatGPT (GPT-6)

**Persona:** A 25-year-old engaged woman planning a wedding in Iowa City within the next year. She is interested in capturing candid wedding moments and is considering hiring a wedding content creator. She is comparing local wedding vendors and wants to understand whether the service is worth the cost.

**Exact Prompt:**

"You are a 25-year-old engaged woman planning a wedding in Iowa City within the next year. You are interested in capturing candid wedding moments and are considering hiring a wedding content creator. You are comparing local wedding vendors and want to understand whether the service is worth the cost.

Read the following homepage as if you were a potential customer.

[INSERT VERSION A OR VERSION B HOMEPAGE CONTENT]

Based only on the information provided, would you inquire about this wedding content creation service? Answer YES or NO, followed by one sentence explaining your decision."

Each trial will be conducted in a fresh conversation with no memory of previous trials. A random number generator will assign each trial to Version A or Version B before it is run. The same model, persona, prompt, and settings will be used for all trials. Only the headline will differ.

## 4. Primary Outcome and Measurement

The primary outcome is the percentage of AI visitors who indicate that they would inquire about the service. Each response will be recorded as YES (1) or NO (0). The inquiry rate will be calculated by dividing the number of YES responses by the total number of trials in each version and multiplying by 100.

## 5. Sample Size and Stopping Date

I will conduct 100 total trials, with 50 assigned to Version A and 50 assigned to Version B. I expect to complete data collection by November 24, 2026. I will stop once all 100 trials are completed, regardless of the results.

## 6. Comparison and Criteria for Support

I will compare the inquiry rates of Version A and Version B by calculating the percentage-point difference between them. A higher inquiry rate for Version B will support my hypothesis. I will also use a statistical test to evaluate whether the observed difference could reasonably be due to chance. If Version B has an equal or lower inquiry rate, the results will not support my hypothesis. Any results will be reported honestly, including the possibility of no meaningful difference.
