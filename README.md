# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

## Aim: 
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

## Algorithm

**Input:** A set of tasks/scenarios to test AI responses</br>
**Output:** Comparative evaluation of AI responses to naïve and basic prompts

### **Step 1: Define Prompt Types**

1. Define **Naïve Prompt**: Broad, vague, minimally structured.
2. Define **Basic Prompt**: Clear, structured, detailed, with instructions, constraints, and context.

### **Step 2: Select Test Scenarios**

1. Choose 4–5 scenarios such as:

   * Creative writing
   * Factual questions
   * Summarization
   * Advice/recommendations
   * Technical explanation
2. For each scenario, define the **task goal**.

### **Step 3: Create Prompt Pairs**

1. For each scenario:

   * Write **Naïve Prompt** (simple, unstructured).
   * Write **Basic Prompt** (detailed, refined, clear instructions).

### **Step 4: Generate AI Responses**

1. For each scenario:

   * Input the **Naïve Prompt** into the AI tool.
   * Record the output.
   * Input the **Basic Prompt** into the AI tool.
   * Record the output.

### **Step 5: Evaluate Responses**

1. Compare outputs for **Quality, Accuracy, and Depth**:

   * **Quality:** Coherence, relevance, tone, readability
   * **Accuracy:** Factual correctness and appropriateness for context
   * **Depth:** Detail, examples, insights, reasoning
2. Note differences between naïve and basic prompt responses.


### **Step 6: Tabulate Results**

1. Create a table with columns:

   * Scenario
   * Naïve Prompt Response Analysis
   * Basic Prompt Response Analysis
   * Observations/Comments


### **Step 7: Analyze Findings**

1. Identify patterns:

   * Do basic prompts consistently outperform naïve prompts?
   * Are there tasks where naïve prompts work adequately?
2. Summarize how prompt clarity affects AI outputs.


### **Step 8: Draw Conclusions**

1. Highlight the **advantages of using basic prompts**.
2. Suggest **best practices for prompt design**, such as:

   * Use clear instructions
   * Provide context and persona
   * Specify output format and constraints
   * Include examples when necessary

### **Step 9: Document Report**

1. Include:

   * Experiment aim
   * AI tools used
   * Prompt types defined
   * Scenario-wise results
   * Comparative analysis table
   * Summary and insights

# OUTPUT

**AI Tools Required:**
* A Large Language Model (e.g., ChatGPT, Google Gemini)
* A text editor or document processor for recording and analyzing results.


# Explanation

## Define the Two Prompt Types:

1.  **Naïve Prompt:** This is a broad, simple, and often unstructured query. It lacks specific context, constraints, or formatting instructions. The user's intent is stated, but the model is given maximum freedom (and ambiguity) in how to respond.
    * **Characteristics:** Short, open-ended, lacks a defined persona or audience, no specific output format.

2.  **Refined Prompt (Basic Prompt):** This is a well-structured, detailed prompt that provides clear instructions, context, and constraints to guide the AI. It minimizes ambiguity and directs the model towards a specific type of output.
    * **Characteristics:** Specific, provides context (who, what, why), may assign a persona (e.g., "Act as a..."), defines the target audience, specifies tone and format (e.g., bullet points, table, word count).
<img width="1024" height="1024" alt="Gemini_Generated_Image_30yd7530yd7530yd" src="https://github.com/user-attachments/assets/1f6c08b8-16ee-4ff5-9106-c017958d4035" />


# **Experiment Execution and Scenarios**

Here are four test scenarios. For each, a naïve prompt was given to the AI, and the response was recorded. Then, a refined prompt was used for the same task, and that response was also recorded.

## Scenario 1: Generating a Creative Story

* **Task:** Write a short story.

* **Naïve Prompt:**
    > "Write a story about a lost robot."

* **AI's Response to Naïve Prompt:**
    Unit 734 awoke to the soft hum of the forest. Its memory banks were fragmented. The last clear data point was a loud crash, then darkness. It scanned its surroundings: tall trees with green canopies, chirping birds, and no sign of the Sky-Hauler X1. Its primary directive blinked in its optical sensor: "Deliver the package." But where? To whom? Unit 734 began to walk, its metallic feet clanking softly on the mossy ground, a lonely figure in a world it didn't understand.

* **Refined Prompt:**
    > "Act as a sci-fi author. Write a 200-word short story for a young adult audience about a small, timid robot named 'Bolt' who gets separated from his owner, a young girl named Lily, during a chaotic festival on a futuristic Mars colony. The story's tone should be hopeful and focus on Bolt's determination to find her, not the dangers around him."

* **AI's Response to Refined Prompt:**
    Bolt’s world was a swirl of confetti and joyous shouts, then it was a sea of legs. One moment, he was holding Lily’s hand; the next, she was gone. Panic surged through his circuits. The Mars Colony’s Founder’s Day festival was no place for a timid maintenance bot. But Lily needed him. Ignoring the towering figures and loud music, Bolt activated his homing beacon, a faint pulse only Lily’s datapad could detect. He thought of her smile and the way she’d polished his chrome chassis just this morning. Fear gave way to a quiet resolve. He dodged a bulky cargo-lifter and navigated through a crowd watching holographic fireworks. Every metallic step was a promise. He wasn't just a lost robot; he was on a mission. "I'm coming, Lily," he whispered, his tiny voice unheard in the noise, but his resolve echoed through the red dust. He would find his way back.

## Scenario 2: Answering a Factual Question

* **Task:** Explain a scientific concept.

* **Naïve Prompt:**
    > "Tell me about photosynthesis."

* **AI's Response to Naïve Prompt:**
    Photosynthesis is a process used by plants, algae, and certain bacteria to convert light energy into chemical energy. During photosynthesis, these organisms take in carbon dioxide from the air and water from the soil. Using the energy from sunlight, they convert these ingredients into glucose, which is a type of sugar that provides energy for the organism, and oxygen, which is released back into the atmosphere. Chlorophyll is the pigment that absorbs the sunlight.

* **Refined Prompt:**
    > "Explain the process of photosynthesis to a 12-year-old. Use an analogy of a factory or a chef to make it easy to understand. Break down the 'ingredients' and the 'products'. Keep the explanation under 150 words."

* **AI's Response to Refined Prompt:**
    Imagine a plant is a tiny chef! Its kitchen is inside its leaves.
    The chef’s special recipe is called photosynthesis. To cook, it needs three main **ingredients**:
    1.  **Carbon Dioxide** (from the air we breathe out).
    2.  **Water** (which it drinks up through its roots).
    3.  **Sunlight** (the energy from the sun, like the heat from an oven).

    Inside the leaf, a special green ingredient called chlorophyll helps mix everything together.
    The final **products** are two amazing things:
    1.  **Glucose** (sugary food for the plant to grow).
    2.  **Oxygen** (the air we need to breathe!).
    So, the plant chef uses sunlight to turn air and water into food for itself and air for us!

## Scenario 3: Summarizing a Concept

* **Task:** Summarize the economic principle of Supply and Demand.

* **Naïve Prompt:**
    > "Summarize supply and demand."

* **AI's Response to Naïve Prompt:**
    Supply and demand is a fundamental economic theory that explains the relationship between the availability of a product (supply) and the desire for that product by buyers (demand). It states that in a competitive market, the price of a good will vary until it settles at a point where the quantity demanded is equal to the quantity supplied, resulting in an economic equilibrium.

* **Refined Prompt:**
    > "Summarize the economic principle of Supply and Demand for a beginner with no prior knowledge. Provide one clear example for high supply/low demand and one for low supply/high demand. Structure the output as three bullet points: the core concept, the first example, and the second example."

* **AI's Response to Refined Prompt:**
    * **Core Concept:** Supply and Demand is the relationship between how much of a product is available (supply) and how much people want it (demand). This relationship determines the product's price. If more people want something than is available, the price goes up. If there's more of it than people want, the price goes down.
    * **High Supply, Low Demand Example:** Imagine a store has 1,000 winter coats in stock (high supply), but it's the middle of a hot summer (low demand). To sell them, the store will likely have a big sale and lower the price significantly.
    * **Low Supply, High Demand Example:** Think of a limited-edition sneaker that everyone wants (high demand), but only 100 pairs were made (low supply). The price for these sneakers will be extremely high because so many people are competing to buy them.

## Scenario 4: Providing Advice

* **Task:** Give recommendations for a travel destination.

* **Naïve Prompt:**
    > "Suggest a vacation spot."

* **AI's Response to Naïve Prompt:**
    You could go to Paris, France. It's known for its art, culture, and landmarks like the Eiffel Tower and the Louvre Museum. Another great option is Costa Rica, which is perfect for nature lovers with its rainforests, volcanoes, and diverse wildlife. If you prefer beaches, the Maldives offers beautiful overwater bungalows and clear blue water.

* **Refined Prompt:**
    > "Act as a travel consultant. I'm looking for a 7-day family vacation recommendation for this December. Our budget is moderate ($3,000 for a family of 4, excluding flights). We enjoy a mix of relaxation on the beach and light outdoor activities like hiking, but are not interested in big cities or nightlife. Suggest one destination and provide three reasons why it fits our criteria."

* **AI's Response to Refined Prompt:**
    Based on your requirements, I highly recommend **Puerto Viejo de Talamanca, Costa Rica.**

    Here are three reasons why it's a perfect fit for your family's December vacation:

    1.  **Perfect Blend of Beach and Nature:** Puerto Viejo offers beautiful Caribbean beaches for relaxation, but it's also right next to the Cahuita National Park and Gandoca-Manzanillo Wildlife Refuge. You can enjoy easy jungle hikes, see monkeys and sloths, and explore nature without strenuous activity, which is perfect for a family.
    2.  **Budget-Friendly:** Costa Rica, particularly on the Caribbean coast, is very affordable. A moderate budget of $3,000 is more than sufficient for a 7-day trip covering family-friendly accommodations, food, and activities. You can find charming bungalows and local restaurants (sodas) that are both authentic and inexpensive.
    3.  **Avoids Big City Bustle:** Unlike other tourist hubs, Puerto Viejo has a laid-back, small-town vibe. It's focused on nature and relaxation, completely aligning with your preference to avoid large cities and nightlife, making it an ideal, safe, and engaging environment for a family.

---

# Deliverables

## 1. Comparative Analysis Table

| Scenario | Analysis of Response to Naïve Prompt | Analysis of Response to Refined Prompt |
| :--- | :--- | :--- |
| **Creative Story** | **Quality:** Generic and undirected. **Accuracy:** N/A (Creative). **Depth:** Lacks character motivation and a clear plot structure. The story is a starting point, not a finished product. | **Quality:** High. Follows all constraints (persona, word count, audience, tone). Well-structured with a clear beginning, conflict, and resolution. **Accuracy:** N/A. **Depth:** Strong characterization (timid but determined) and a focused, hopeful narrative. |
| **Factual Question** | **Quality:** Technically correct but dry and academic. Not tailored to any specific audience. **Accuracy:** High. **Depth:** Superficial. It states what photosynthesis is but not *how* to understand it intuitively. | **Quality:** Excellent. Uses a specified analogy, making the concept highly accessible. The structure (ingredients/products) is clear and easy to follow. **Accuracy:** High. **Depth:** Greater depth of understanding for the target audience by relating abstract concepts to familiar ones (a chef). |
| **Summarization** | **Quality:** A dense, single-paragraph definition. **Accuracy:** High. **Depth:** Low. It defines the term but doesn't illustrate its practical application or make it easy to grasp for a novice. | **Quality:** Excellent. Uses the requested bullet-point format, making it scannable and digestible. **Accuracy:** High. **Depth:** Much deeper. The use of clear, contrasting examples solidifies the user's understanding of how the principle works in the real world. |
| **Advice** | **Quality:** Too broad to be useful. It offers a random list of disparate options without any justification or context. **Accuracy:** N/A (Subjective). **Depth:** Very shallow. It's a list, not a recommendation. | **Quality:** High. Provides a single, well-justified recommendation that directly addresses all user constraints (budget, interests, timing, group type). **Accuracy:** N/A. **Depth:** Deep and actionable. Explains *why* the destination is a good fit, allowing the user to make an informed decision. |

## 2. Analysis of How Prompt Clarity Impacts Outputs

* **Quality:** The most significant improvement was in the **quality** of the output. Refined prompts force the model to adhere to a specific structure, tone, and format. The naïve prompts often resulted in a "wall of text," whereas the refined prompts produced structured, well-organized, and more readable content (e.g., bullet points, a story with a clear arc). The persona instruction (`Act as a...`) dramatically improved the tone and style to be more appropriate for the task.

* **Accuracy:** While the AI was factually accurate in both prompt types for the scientific question, the refined prompt increased the **contextual accuracy** and relevance. By specifying the audience (a 12-year-old), the refined prompt ensured the information was not just correct, but also appropriate and understandable. For tasks like providing advice, the refined prompt is the only way to get a truly "accurate" or relevant answer that fits the user's hidden context.

* **Depth:** Refined prompts consistently produced responses with greater **depth**. Naïve prompts receive superficial, definitional answers. By asking for examples, reasons, or analogies, the refined prompts compelled the model to go beyond the "what" and explain the "why" and "how." This moves the response from simple information retrieval to genuine explanation and insight.

## 3. Summary of Findings and Insights

This experiment consistently demonstrates that **the quality of the output from an LLM is directly proportional to the quality of the input prompt.** While naïve prompts can work for very simple, factual lookups, they fail in any task requiring nuance, structure, or creativity.

## Key Findings:

* **Refined Prompts Yield Superior Results:** Across all scenarios, refined prompts produced outputs that were more useful, relevant, and aligned with the user's intent.
* **Specificity Reduces Ambiguity:** The more specific the prompt, the less the model has to "guess" what the user wants. This leads to more precise and reliable answers.
* **Naïve Prompts are Inefficient:** A naïve prompt often requires several follow-up prompts to refine the answer, a process that could have been avoided by creating a single, well-structured prompt from the start.

## How to Structure Prompts for Optimal Results:

1.  **Assign a Persona:** Begin with `Act as a...` (e.g., travel consultant, sci-fi author, expert programmer). This sets the tone and context immediately.
2.  **Provide Context:** Explain the "why" behind your request. Who is this for? What is the goal? (e.g., "...for a family with young children," "...for a presentation to executives").
3.  **Give Explicit Instructions:** Clearly state the task. Use action verbs (e.g., Summarize, Explain, Compare, Generate, List).
4.  **Set Constraints and Specify Format:** Define the desired output structure.
    * **Length:** "Keep it under 200 words."
    * **Format:** "Use bullet points," "Provide the answer in a table with two columns," "Write it in a professional tone."
5.  **Provide Examples:** If the task is complex, give an example of the kind of output you want. This is one of the most effective ways to guide the model.

# RESULT: 
The prompt for the above said problem executed successfully
