# ShogScript
A concise, domain-specific language for efficient interaction with GPT-4-based AI models, enhancing communication and user experience.

## Context

ShogScript was created in collaboration with GPT-4 by a TESOL/IELTS teacher, not a programmer. While the language has its roots in educational settings, its applications are vast and diverse. The primary goal is to develop ShogScript into a versatile personal shorthand for various purposes, such as:

1. Prompting GPT-4 with tight and organized heuristics, making it easier for users to obtain desired outputs.
2. Personal record-keeping, specifically storing prompts with pertinent information needed to re-continue a thread with a fresh GPT-4 session.
3. Streamlining communication in different professional domains, such as education, research, business, and more.

ShogScript aims to cater to a wide range of users, from those with no programming experience to seasoned developers, offering an accessible and efficient way to interact with GPT-4-based AI models and manage AI interactions.

## ShogScript Overview

ShogScript is a concise, domain-specific language (DSL) designed to enhance communication and user experience when interacting with GPT-4-based AI models. The language focuses on offering a structured, flexible, and engaging way of crafting queries and managing AI interactions, making it easier for users to obtain desired outputs.

The ShogScript language is composed of the following structure elements:

- **keyphrases**: Concise keywords and phrases to represent concepts, actions, or ideas.
- **hierarchy**: Use parentheses "()" to group related elements and establish a hierarchy.
- **delimiters**: Use commas "," to separate different elements within a group or at the same level of hierarchy.
- **adjusters**: Use a combination of keywords and symbols to modify elements.
- **embedding**: Nest elements within other elements to create more complex structures.
- **optionals**: Use square brackets "[]" to indicate optional elements.
- **anychars**: Use an asterisk "\*" to represent a wildcard that can be replaced with any suitable value.
- **iterators**: Use curly braces "{}" with a number to indicate repetition.
- **if_statements**: Use angle brackets "<>" to indicate conditionals.
- **logic_operators**: Use logical operators like "AND", "OR", and "NOT" to create complex conditions or relationships between elements.
- **vars**: Use variables to store and reference values.
- **funcs**: Define and use functions to perform specific tasks or calculations.
- **cycles**: Use loops to repeat actions or processes based on specified conditions.
- **escape_chars**: Use escaping characters to include special characters or reserved symbols within the script.
- **notes**: Use comments to provide explanations, clarifications, or reminders within the script.

These elements make up the structure of the ShogScript language and provide a way to create detailed and complex instructions for a fresh GPT-4 session.

## Starter Prompts

Note: You do not need a starter prompt in order to feed GPT-4 ShogScript. But, if you want a fresh GPT-4 session to then *generate* ShogScript without protesting, you'll need to initiate ShogScript to get it into the right speculative mindset. You can use something like one of the following starter prompts:

### Starter Prompt #1 (for Story Gen)
```ShogScript_intro(def(lang(concise_domain_specific_efficient), aim(detailed_instructions+structure), example(query(weather,location,temp,precip,forecast(time=day+night+week)), task(gen_story,subject1+subject2+OR+subject3,duration(brief+moderate+extended)), syntax_rules)), GPT4, new_session, produce_ShogScript, initiate, structure(keyphrases, hierarchy, delimiters, adjusters, embedding, optionals, anychars, iterators, if_statements, logic_operators, vars, funcs, cycles, escape_chars, notes), enhance+expand+back(ideas), lexicon(broad+natural+refined), syntax(ample+adaptable), cohesion(logical+smooth), clarity(precise+concise), engagement(attention+interest))```

### Starter Prompt #2 (Objective-Ish Articles etc.)
```ShogScript_intro(def(concise_domain_specific_efficient), example(query(weather,location,temp,precip)), GPT4, new_session, produce_ShogScript, initiate, structure(keyphrases, hierarchy, delimiters, adjusters, embedding, optionals, anychars, iterators, if_statements, logic_operators, vars, funcs, cycles, escape_chars, notes), develop+extend+support(ideas), vocab(wide+natural+sophisticated), grammar(wide+flexible), cohesion(logical+smooth), clarity(precise+concise), engagement(attention+interest), mood(objective+explanatory), viewpoint(forward_looking))```

This prompt sets the stage for the creative and hypothetical mindset required to effectively use ShogScript.

## Usage Examples

### Intricate Prompts: Story Generation

#### Example 1: Futuristic Cityscape Story
ShogScript_prompt(task(gen_story), subject(futuristic_cityscape), duration(moderate), mood(mysterious+adventurous), setting(urban+high-tech), characters(main_character:private_investigator, secondary_character:AI_assistant), plot(twists+reveals), theme(humanity+technology), writing_style(descriptive+suspenseful), engagement(immersion+surprise), initiate)

#### Example 2: Time Travel Adventure Story
ShogScript_prompt(task(gen_story), subject(time_travel_adventure), duration(extended), mood(action-packed+thought-provoking), setting(past+future), characters(main_character:scientist, secondary_character:historical_figure), plot(interwoven+nonlinear), theme(consequences+choices), writing_style(crisp+cinematic), engagement(curiosity+excitement), initiate)

#### Example 3: Alien Encounter Story
ShogScript_prompt(task(gen_story), subject(alien_encounter), duration(brief), mood(mystical+introspective), setting(outer_space+alien_world), characters(main_character:astronaut, secondary_character:alien_species), plot(first_contact+mutual_understanding), theme(communication+compassion), writing_style(lyrical+imaginative), engagement(wonder+reflection), initiate)

### Intricate Prompts: Objective-Ish Articles Etc.

#### Example 1: Technological Advancements
ShogScript_prompt(produce_text, subject(technological_advancements), size(compact+in-depth), emphasis(effect+community), viewpoint(forward_looking), mood(objective+explanatory), structure(logical+coherent), clarity(precise+concise), engagement(attention+interest), initiate)

#### Example 2: Health and Wellness Advice
ShogScript_prompt(produce_text, subject(health_wellness_advice), size(brief+informative), emphasis(nutrition+exercise), target_audience(adults_30-50), mood(encouraging+informative), format(listicle), style(conversational+expert), engagement(motivation+education), initiate)

#### Example 3: Comparative Analysis of Historical Figures
ShogScript_prompt(produce_text, subject(comparative_analysis), context(historical_figures), figures(Gandhi,Mandela), focus(leadership+impact), perspective(cultural+political), mood(analytical+respectful), structure(introduction+comparison+conclusion), depth(surface_level+nuanced), engagement(insight+intrigue), initiate)

These examples demonstrate comprehensive and detailed ShogScript prompts, showcasing the capabilities of the language. By using this prompt, users can effectively communicate their requirements to GPT-4, making it easier to obtain desired outputs.

### Simpler Prompts

### Example 1: Weather Query
example(query(weather, location, temp, precip))

This example demonstrates a simple ShogScript query for weather information, including temperature and precipitation for a specified location.

### Example 2: News Query with Filters

example(query(news, topic, date_range, filter(language, English)))

This example shows a ShogScript query for news articles on a specific topic within a date range, filtered by language.

### Example 3: Movie Recommendations with Preferences

example(query(movie_recommendations, genre, year, preference(actor, director)))

## Roadmap

Our roadmap for ShogScript includes the following milestones:

1. Develop a ShogScript parser compatible with GPT-4-based AI models.
2. Create a comprehensive set of tutorials and guides to help users adopt and utilize ShogScript effectively.
3. Empower users to create their own domain-specific ShogScripts, further enhancing customization and user experience.
4. Continuously refine and expand the language based on user feedback and evolving AI capabilities.
5. Explore integrations with other AI platforms, chatbots, and NLP tools.

## Contributing

We welcome contributions to the ShogScript project! Please feel free to submit pull requests, report issues, or suggest new features. Before contributing, make sure to read our [contribution guidelines](./CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for more details.

## TL;DR (Add this to your prompts for better writing)
If nothing else, please enjoy our little ShogScript IELTS heuristic:
```develop+extend+support(ideas), vocab(wide+natural+sophisticated), grammar(wide+flexible), cohesion(logical+smooth), clarity(precise+concise), engagement(attention+interest), mood(objective+explanatory), viewpoint(forward_looking))```

Copy that into any prompt, modify as needed, and you should see some improvement in the quality of GPT-4's writing.

