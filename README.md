# ShogScript: Expressive Pseudocode for GPT-4 AI Interactions

ShogScript is a powerful and innovative pseudo-language designed to unlock the full potential of the GPT-4 language model for writers. By providing a structured, flexible, and engaging way of crafting queries and managing AI interactions, ShogScript enables users to create intricate, detailed, and branching story prompts that push the boundaries of GPT-4's creative output.

The language itself is half-baked, but I hope you will find, besides a little inspiration, two concretely useful takeaways:
1. An idea of the kind of starter/activation/initialization prompts you’ll need to design in order to consistently jump a fresh GPT-4 into a custom pseudocode session.
2. My shogtongued writing teacher heuristics-injections to help improve your GPT-4 output, located at the very bottom of this file.

## Overview

ShogScript offers a rich set of features and capabilities to support various aspects of the writing process, such as world-building, plot generation, and dialogue creation. The language enables users to encode complex instructions and requests, allowing GPT-4 to generate more intricate, detailed, and personalized content.

### Features

- Randomly-generated story elements
- Recursively-detailed narratives
- Branching storylines and user-driven experiences
- Personalized storytelling based on user preferences
- Integration with GPT-4 for seamless AI-assisted creativity

### Applications

- World-building and character development
- Plot generation and story outlines
- Dynamic dialogue and conversation generation
- Reader-driven narrative choices
- Adaptive storytelling based on user input

Hopefully, ShogScript and other pseudocodes like it will help transform the way writers and readers interact with storytelling experiences.

## Starter Prompts

_Sometimes_ you can get away without a starter prompt, especially with smaller snippets. But, if you want a better chance of your ShogScript prompt working on a fresh ChatGPT GPT-4 session, and certainly if you want your machine to then *generate* ShogScript without protesting, you'll need to initiate ShogScript to get it into the right speculative mindset. You can use something like one of the following starter prompts:

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

1. Create a comprehensive set of tutorials and guides to help users adopt and utilize ShogScript effectively.
2. Empower users to create their own domain-specific ShogScripts, further enhancing customization and user experience.
3. Continuously refine and expand the language based on user feedback and evolving AI capabilities.
4. Explore ShogScript workshops for everyday users and integrations with other AI platforms, chatbots, and NLP tools.

## Contributing

We welcome contributions to the ShogScript project! Please feel free to submit pull requests, report issues, or suggest new features. Before contributing, make sure to read our [contribution guidelines](./CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for more details.

## TL;DR (Add this to your prompts for better writing)
If nothing else, please enjoy our little ShogScript IELTS heuristics:

```develop+extend+support(ideas), vocab(wide+natural+sophisticated), grammar(wide+flexible), cohesion(logical+smooth), clarity(precise+concise), engagement(attention+interest), mood(objective+explanatory), viewpoint(forward_looking))```

Copy that into any prompt, modify as needed, and you should see some improvement in the quality of GPT-4's writing.

