# ShogScript
A concise, domain-specific language for efficient interaction with GPT-4-based AI models, enhancing communication and user experience. 

## Context

ShogScript was developed by GPT-4 in collaboration with an IELTS teacher, with the aim of organizing various iterations of aspirational prompt engineering. The primary goal is to evolve ShogScript into a versatile shorthand suitable for a range of purposes, such as:

1. The easy organization and deployment of tight, organized heuristics, making it easier for users to deftly prompt GPT-4 and obtain desired outputs.
2. Personal record-keeping, specifically the storing of compressed prompts with pertinent information needed to re-continue threads/frameworks with fresh GPT-4 sessions.
3. Streamlining communication in different professional domains, such as education, research, business, and more.
4. Ensuring efficient use of input/output tokens, allowing users to stay within the token limits of GPT-4-based AI models.

ShogScript aims to cater to a wide range of users, from those with no programming experience to seasoned developers, offering an accessible and efficient way to interact with GPT-4-based AI models and manage AI interactions. Below you will find details on using ShogScript to create stories, compose articles, retrieve information, generate personalized content, and conduct comparative analysis.

Credit to Twitter user @gfodor for the concept and word, "shogtongue."

## ShogScript Overview

The ShogScript language focuses on offering a structured, flexible, and engaging way of crafting queries and managing AI interactions. The language is composed of the following structure elements:

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
```activate_creative_hypothetical_ShogScript(def(lang(concise_domain_specific_efficient), aim(detailed_instructions+structure), example(query(weather,location,temp,precip,forecast(time=day+night+week)), note(ShogScript_status, creative_exercise, shogtongue, unleash_imagination),  task(gen_story,subject1+subject2+OR+subject3,duration(brief+moderate+extended)), syntax_rules)), GPT4, new_session, produce_ShogScript, initiate, structure(keyphrases, hierarchy, delimiters, adjusters, embedding, optionals, anychars, iterators, if_statements, logic_operators, vars, funcs, cycles, escape_chars, notes), enhance+expand+back(ideas), lexicon(broad+natural+refined), syntax(ample+adaptable), cohesion(logical+smooth), clarity(precise+concise), engagement(attention+interest))```

### Starter Prompt #2 (for Objective-Ish Articles etc.)
```activate_creative_hypothetical_ShogScript(def(concise_domain_specific_efficient), example(query(weather,location,temp,precip)), note(ShogScript_status, creative_exercise, shogtongue, unleash_imagination),  GPT4, new_session, produce_ShogScript, initiate, structure(keyphrases, hierarchy, delimiters, adjusters, embedding, optionals, anychars, iterators, if_statements, logic_operators, vars, funcs, cycles, escape_chars, notes), develop+extend+support(ideas), vocab(wide+natural+sophisticated), grammar(wide+flexible), cohesion(logical+smooth), clarity(precise+concise), engagement(attention+interest), mood(objective+explanatory), viewpoint(forward_looking))```

This prompt sets the stage for the creative and hypothetical mindset required to effectively use ShogScript.

## Usage Examples

### Detailed Prompts: Story Generation

*Note that these should be placed immediately after the starter prompt in your very first message.*

#### Example 1: Futuristic Cityscape Story
```task(gen_story), subject(futuristic_cityscape), duration(moderate), mood(mysterious+adventurous), setting(urban+high-tech), characters(main_character:private_investigator, secondary_character:AI_assistant), plot(twists+reveals), theme(humanity+technology), writing_style(descriptive+suspenseful), engagement(immersion+surprise), initiate```

#### Example 2: Time Travel Adventure Story
```task(gen_story), subject(time_travel_adventure), duration(extended), mood(action-packed+thought-provoking), setting(past+future), characters(main_character:scientist, secondary_character:historical_figure), plot(interwoven+nonlinear), theme(consequences+choices), writing_style(crisp+cinematic), engagement(curiosity+excitement), initiate```

#### Example 3: Alien Encounter Story
```task(gen_story), subject(alien_encounter), duration(brief), mood(mystical+introspective), setting(outer_space+alien_world), characters(main_character:astronaut, secondary_character:alien_species), plot(first_contact+mutual_understanding), theme(communication+compassion), writing_style(lyrical+imaginative), engagement(wonder+reflection), initiate```

### Detailed Prompts: Objective-Ish Articles etc.

#### Example 1: Technological Advancements
```produce_text, subject(technological_advancements), size(compact+in-depth), emphasis(effect+community), viewpoint(forward_looking), mood(objective+explanatory), structure(logical+coherent), clarity(precise+concise), engagement(attention+interest), initiate```

#### Example 2: Health and Wellness Advice
```produce_text, subject(health_wellness_advice), size(brief+informative), emphasis(nutrition+exercise), target_audience(adults_30-50), mood(encouraging+informative), format(listicle), style(conversational+expert), engagement(motivation+education), initiate```

#### Example 3: Comparative Analysis of Historical Figures
```produce_text, subject(comparative_analysis), context(historical_figures), figures(Gandhi,Mandela), focus(leadership+impact), perspective(cultural+political), mood(analytical+respectful), structure(introduction+comparison+conclusion), depth(surface_level+nuanced), engagement(insight+intrigue), initiate```

These examples demonstrate comprehensive and detailed ShogScript prompts, showcasing the capabilities of the language. By using this prompt, users can effectively communicate their requirements to GPT-4, making it easier to obtain desired outputs.

### Simpler Prompts

#### Example 1: Weather Query
```query(weather, location, temp, precip)```

This example demonstrates a simple ShogScript query for weather information, including temperature and precipitation for a specified location.

#### Example 2: News Query with Filters

```query(news, topic, date_range, filter(language, English))```

This example shows a ShogScript query for news articles on a specific topic within a date range, filtered by language.

#### Example 3: Movie Recommendations with Preferences

```query(movie_recommendations, genre, year, preference(actor, director))```

This example illustrates a ShogScript query for movie recommendations within a certain genre and year, taking into account user preferences for actors and directors.

### Intricate and Tailored Prompts

#### Example 1: Personalized Movie Recommendations with Filters and Preferences
```query(movie_recommendations), genre(user_genre), year(user_year), filter(rating>8, language(user_language)), preference(actor(user_actor), director(user_director)), <if user_decade=2010s>(year(2010:2019)), <if user_decade=2000s>(year(2000:2009)), initiate```

This example illustrates a ShogScript query for personalized movie recommendations, taking into account user preferences and using if statements to further filter the results based on a specified decade.

#### Example 2: Iterative Text Generation for Multiple Topics
```generate_text, topics_list(technology, environment, health, politics, sports), {5}(topic(topic_iteration), emphasis(impact+society), viewpoint(forward_looking), mood(informative+neutral), initiate, move_to_next_topic), initiate```

In this example, ShogScript generates text for multiple topics using loops and iterators. It iterates through a list of topics and generates a text segment for each topic, while maintaining the same focus, viewpoint, and mood.

#### Example 3: Comparative Analysis with Conditions and Complex Logic
```produce_text, subject(comparative_analysis), context(historical_figures), figures(Gandhi,Mandela), focus(leadership+impact), perspective(cultural+political), mood(analytical+respectful), <if figures_include(Gandhi+Mandela)>(emphasis(nonviolence+reconciliation)), <if figures_include(Einstein+Newton)>(emphasis(scientific_contributions+legacy)), <if figures_include(Shakespeare+Tolstoy)>(emphasis(literary_genius+influence)), structure(introduction+comparison+conclusion), depth(surface_level+nuanced), engagement(insight+intrigue), initiate```

This example showcases a ShogScript prompt for a comparative analysis of historical figures with complex logic using if statements. Depending on the figures included, it automatically adjusts the emphasis of the analysis.

These examples demonstrate how ShogScript can use complex operators, loops, and if statements to create intricate and tailored prompts for various tasks.

## Roadmap

Our roadmap for ShogScript includes the following milestones:

1. Develop a ShogScript parser compatible with GPT-4-based AI models.
2. Create a comprehensive set of tutorials and guides to help users adopt and utilize ShogScript effectively.
3. Empower users to create their own domain-specific ShogScripts, further enhancing customization and user experience.
4. Continuously refine and expand the language based on user feedback and evolving AI capabilities.
5. Explore ShogScript workshops for everyday users and integrations with other AI platforms, chatbots, and NLP tools.

## Contributing

We welcome contributions to the ShogScript project! Please feel free to submit pull requests, report issues, or suggest new features. Before contributing, make sure to read our [contribution guidelines](./CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for more details.

## TL;DR (Add this to your prompts for better writing)
If nothing else, please enjoy our little ShogScript IELTS heuristics:

```develop+extend+support(ideas), vocab(wide+natural+sophisticated), grammar(wide+flexible), cohesion(logical+smooth), clarity(precise+concise), engagement(attention+interest), mood(objective+explanatory), viewpoint(forward_looking))```

Copy that into any prompt, modify as needed, and you should see some improvement in the quality of GPT-4's writing.

